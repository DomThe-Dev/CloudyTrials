# Cloudy Trials
My first proper 2D game!
## What is this?
![image](https://github.com/DomThe-Dev/CloudyTrials/assets/122572944/c638dcd0-9d53-480c-a9e4-d219f20d4052)
</br>
This is a simple game made in Construct 3, as part of my Games Technology Level 3 course. It had to meet some certain requirements set by the college, which are listed here:
1) The game has to be 2D
2) The prompt for the game is **Sheep**
3) It must be a platformer game </br>
</p>With all those requirements set out, I set out to brainstorm some ideas!</br>
Ideas ranged from a myltiplayer competitive game, like Smash, to a simple story driven game, about a gaelic shepherd. However, I settled on a bullet hell!

## Notable Features
This project contains many features, and most the cool features required interesting ways of being implemented! Here are some of my favourite.
### Dialogue Box
![image](https://github.com/DomThe-Dev/CloudyTrials/assets/122572944/d10a0cb2-3796-45db-aae6-1a67cc6f9b16)
One of the most interesting features was the dialogue box by Aries! I love how it pops in smoothly, and the text appears letter by letter! It ended up being quite a simple feature to include, thanks to all the mechanics that Construct 3 already has.</br>
&nbsp;&nbsp;However, after some testing, I decided it would be best if the dialogue didn't trigger again if a player dies, even if the entire scene is technically reset. This is accomplished via a global variable flag which doesn't get reset after a scene reset, thanks to how Construct 3 works.
### Falling Platform
![image](https://github.com/DomThe-Dev/CloudyTrials/assets/122572944/8022cc8a-ae4e-441f-ab2a-329389bdabf8)
The falling platforms work by falling a bit, then falling completely, which was slightly annoying to implement. Due to everything being random, both platform halves could fall, so after a decent bit of trial and error, I got it to work perfectly.
## Poisoned Bullets
![image](https://github.com/DomThe-Dev/CloudyTrials/assets/122572944/90585584-56e1-4f7a-93b3-1cbd0099b296)
These function by having an invisible object at the center constantly spinning, and whenever the bullet attack is triggered, the bullets are fired out of the rotating secret piece, and due to the spawning being in random intervals, the bullets fire everywhere. Best of all, it gives the player a speed debuff!
## Dashing
![image](https://github.com/DomThe-Dev/CloudyTrials/assets/122572944/8c6ce126-359b-456d-a7c7-8b92e67de4f3)
Dashing qas quite fun to implement! Double tapping A or D allows the player to dash in that direction, but of course with a minor cooldown. Ended up being a crucial part of the game!
