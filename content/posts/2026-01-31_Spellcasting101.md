---
title: "Thoughts on Spellcasting 101 by Steve Meretzky"
date: 2026-01-31T11:30:43+11:00
draft: false
tags: ["puzzle", "game", "interactive fiction", "word play"]
---
**Spoiler alert** This post is my thoughts on the puzzle design in Steve Meretzky's 1990 adventure game [Spellcasting 101: Sorcerers Get All the Girls](https://en.wikipedia.org/wiki/Spellcasting_101:_Sorcerers_Get_All_the_Girls).  It is **NOT** a spoiler-free review. If you haven't played the game, stop right here. It's a game worthy of playing, so you should enjoy it yourself. Reading further will absolutely spoil the fun for you. 

Jimmy Maher at the [Digital Antiquarian](https://www.filfre.net/tag/spellcasting/) has wrote about the historical context of this game in great detail, so I won't repeat it here. Briefly, Spellcasting 101 was game designer [Steve Meretzky](https://en.wikipedia.org/wiki/Steve_Meretzky)'s first published game after the demise of [Infocom](https://en.wikipedia.org/wiki/Infocom). Although billed as a graphical adventure game, it is an Infocom-style text adventure through and through. The graphics are worthless add-ons. During my 2025 holidays, I decided to play this game  instead of Meretzky’s Infocom-era oeuvre, because I'm not quite ready to tackle the proper Infocom catalog yet.

It worked out well. I managed to "solve" the game in several evenings without too much frustration. I did use hints, but I was never completely stuck or felt hopeless. The game world is mostly divided into small, self-contained sections, so the complexity is manageable for casual gamers. I was worried that this game was going to be the result of snack-size puzzles thrown together, but in the end, I was pleasantly surprised that there is enough substance in it to feel some of the joy and cleverness of text games. Otherwise I wouldn't be bothered to write about it.

## Overall design

You are a wannabe sorcerer starting your first year in a sorcerer university. There are lots of sorcery classes to take, and in the end you have to save the world... it's like Harry Potter... if Harry Potter were full of sex. The soft porn setting mixed with magic doesn't make a lot of sense. It's written that way because in the post-Infocom era, what the game publishers wanted the most from Meretzky was another [Leather Goddesses of Phobos](https://en.wikipedia.org/wiki/Leather_Goddesses_of_Phobos) - one of his most commercially successful games. He was probably not terribly excited about repeating his one-off parody of male-centric pulp Sci-Fi, but for a couple of years in the 90s, he had to make do playing the role of a Douglas Adams with dirty jokes. It's not an inspiring premise, but I was curious about how Meretzky dealt with it.

Very surprisingly, most of the game does not take place in _Sorcerer U_! Only a couple of days after the school had begun, the university was attacked by evil forces, and you have to roam the game world to prevent the bad guy from collecting 5 nonsensical objects to complete a powerful magical weapon. This sounds very similar to _Leather Goddess of Phobos_, except that Meretzky doesn't seem to be very enthusiastic about it. The 5 objects are random and forgettable. 

## Can you do something clever with sex in interactive fiction?

The comedic potential of sex in games is enormous, so it's a little disappointing that the obligatory sex scenes in this game are merely mildly amusing. They are not particularly witty or subversive but it's not the point of Meretzky's games anyway.

However, I think he did manage to do something clever with sex that can only be done with interactive fiction.

On **The Island where Time Runs Backwards**, you begin at the conclusion of a series of events, and have to work backwards in time, inferring the action that must have taken at the previous turn, which leads to the current condition. It's a very interesting idea in puzzle design that opens up new possibilities, but Meretzky decided to keep this segment short and sweet, using it only to tell a simple dirty joke: you figure out that you must have jumped out of the window of a building, but you don't know exactly why. Working backwards, you realize later that it's because you got somebody pregnant! 

Another funny gag is the **Island of the Amazons**, where you have to accomplish your goal within a fixed number of turns. Ticking clock puzzles are not new in interactive fiction, but in this case, you have to do everything quickly, because wherever you go on this island, women come to copulate, and you quickly die from exhaustion.  _Futurama_ does [this joke](https://en.wikipedia.org/wiki/Amazon_Women_in_the_Mood) better, but it's one of the more amusing situations that I've run into in interactive fiction. 

Like _Leather Goddess of Phobos_, the game has a _naughty_ and a _nice_ mode. I naturally played the game _naughty_ but was curious about playing it _nice_, because with clever writing, the over-the-top sex scenes could be potentially made a lot funnier if everything is all wink wink, nudge nude. Alas! The nice mode doesn't add much to the humor - sex is merely replaced by random activities.

## The "stunning climax"

I sleepwalked through most of the game. There was fun to be had here and there, but it was nothing too exciting. The end game ("the stunning climax"), however, changed everything. It's still a short endgame that can be completed in a small number of turns, but the puzzles are more involved. They are integrated to the logic of the game world and cannot be solved by short-term, local thinking. I was taken by surprised and couldn't solve them without resorting to hints. I regret that I didn't spend more time on the puzzles because the solutions are interesting.

**The pressure plates puzzle**: In a castle, I needed to open 3 doors simultaneously, each controlled by a pressure plate on the floor.  Obviously I needed 3 persons to stand on the 3 plates, but where to find two additional persons?

**Ticking clock puzzle #1**: In the tower of the castle, a woman was found dead - killed by a swinging pendulum. It turns out that if I had reached the castle sooner, the woman would be alive and could stand on one of the pressure plates. For that to happen, I needed to take an optimal sequence of actions once I am near the castle - not a turn could be wasted.

I feel that this puzzle is slightly unfair, because it wasn't obvious to me that if I hadn't deviated from the optimal sequence, I would arrive at the castle sooner to save the woman. However, very early on in this game, in Wizard U, there is a teaching "simulator" with exactly the same situation (the same castle, the same swinging pendulum... even the same woman) that allows you to go over this scenario again and again until you find the optimal sequence. So, the puzzle should be solvable as long as the player remembers that scene in Wizard U. It still doesn't make logical sense. Why would the university have a simulator for exactly the same situation? 

**A mechanical puzzle solved by punning**: We still need something on the third pressure plate to open the third door. Suspiciously, there is a painting in the room, so I thought that I could find a way to use it to depress the third pressure plate while I stand on another. That proved to be completely off the track. Instead of an object manipulation puzzle, it's a language puzzle in the tradition of [Nord and Bert Couldn't Make Head or Tail of It](https://en.wikipedia.org/wiki/Nord_and_Bert_Couldn%27t_Make_Head_or_Tail_of_It). The solution: There is a soul trapped in that painting. A spell can be cast to release the man so that he can stand on the third pressure plate, but to cast that spell, you need to know his name. The wizard who magically transformed the man into the painting was a punster, who turns the person into an object that is a pun of his name. Since the painting is a piece of art, we need to cast the inverse spell on "Art" (short for Arthur). 

That sounds like the most ridiculous puzzle ever, but it's not. Earlier in the game, I visited **The Island of Lost Soles** - the name in itself suggests punning. It just so happens that the wizard mentioned above had previously turned all the 80 residents of the island into objects, so before I reached the end game, I had already practiced solving this pun puzzles... 80 times (!). It's easily the most memorable part of this game.  I should have been able to solve the pressure plate puzzle myself, but I was so concentrated on the mechanical solution that the punning solution never occurred to me. 


**Ticking clock puzzle #2**: The very last puzzle of this game is another ticking clock puzzle. The course of action is very obvious: I knew that I had to open a "spell box" to transcribe the spell into my spell book, and then cast the spell. However, that sequence of actions required one more turn than what's allowed by the ticking clock: by the time I completed the sequence, the villain would have already done the unthinkable. There must be a way to reduce the number of actions by one turn, but what could it be?

I'm glad that I used the hint book this time because I think the solution is unfair. It turns out that if the spell book was destroyed before the spell box was opened, the energy of the spell (which normally flows into the spell book) had nowhere to go, so it would be activated automatically, saving us one turn. That would be an acceptable solution if there was some rationale behind this logic.  For example, Wizard U has a _General Magic_ class, which explains the mechanics of magic in this world.  I don't remember anything from that class suggesting that a spell could be activated without being cast. Maybe I am supposed to experiment with magic myself to figure this out myself.

## Summary

It's an accessible, fun little game. It's not Meretzky's best, but there are some clever ideas that are worthy of his name.

## Additional thoughts on The Island where Time Runs Backwards

I didn't mention that on this island, we are suddenly in a movie shoot. So it's not like we _actually_ got somebody pregnant. It's just the plot of a movie. Why is the director shooting a movie on an island where time runs backwards? It's a very abrupt change of point of view with no explanation. 

On this island, there is only one correct action for every turn. Any deviation leads to the end of the game. It would be much more interesting if multiple actions are allowed, but then, why are we making decisions for actions that have already been taken? Maybe this movie shoot was put in there to justify the design decision to allow only one possible sequence of event? Time travel is hard in game design.



