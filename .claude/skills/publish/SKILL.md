---
name: publish
description: Publish a blog post — updates the date to now, sets draft to false, commits, and pushes to GitHub. Use when the user wants to publish a post in content/posts/.
disable-model-invocation: true
---

Publish the blog post. If $ARGUMENTS names a specific file or slug, use that. Otherwise find the most recently modified `.md` file under `content/posts/` that still has `draft: true`.

## Current timestamp
- Date: !`date -u +"%Y-%m-%dT%H:%M:%S+00:00"`

## Steps

1. **Identify the file.** If $ARGUMENTS is non-empty, glob `content/posts/` for a file whose name contains those words. Otherwise run: `grep -rl "draft: true" content/posts/` and pick the most recently modified result (use `ls -t` to sort).

2. **Read the file** to confirm it is the right post (show the title to the user).

3. **Check and fix the filename.** The file must be named `YYYY-MM-DD_slug.md` (e.g. `2021-02-03_my-post.md`). Check whether the current filename matches that pattern (starts with a date in `YYYY-MM-DD` format followed by `_`).
   - If it does NOT match, derive the date portion from the frontmatter `date:` field (or use today's date if none is set), and derive the slug from the existing filename (strip any leading date-like prefix, strip the `.md` extension, lowercase, replace spaces with hyphens). Rename the file with `mv` to the new name. Use the new path for all subsequent steps.

4. **Update the frontmatter** using the Edit tool:
   - Replace the existing `date:` line with `date: <current timestamp from above>`
   - Replace `draft: true` with `draft: false`

5. **Commit.** Stage only that file and commit with the message: `publish: <title of post>`

6. **Push** to origin with `git push`.

7. Report the file path, the new date, and the commit hash.
