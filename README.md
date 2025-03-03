[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MjLLqDcN)
# HW1
## W1L2 In-Class Activity

Put your notes from the W1L2 (Thurs, Jan 9) in-class activity here.


1 How would you describe this game world in objects?

There is the player as a bunny sprite, and a green flower sprite 


2 What attributes and actions do these objects have? 

You as the bunny are able to move in cardinal directions of. Up is W down is S left is A and 
Right is D. You can use the spacebar to make a plant sprite aper. And the are two counters one for seeds remaining and one for planted once seeds 


3 How do these objects act on or affect each other 

As you plant a seed the number of seeds remaining goes down and the number of seeds planted goes up as the number of seeds remains reaches 0 you can’t plant anymore 


## Devlog

On the player script to detect the inputs, I used the update to check each frame to see if the player moves using input.getkeycode W A S D and space. On the start function I setup _numSeedsLeft and the UI.
To move the player I used the translate function inside of the transform of the player and I multiplied the time by the speed on each frame on the appropriate axis. Then On the PlantSeed function I check is the _numSeedsLeft > 0 meaning I have seeds to plant using Instantiate to spawn it.
Using the player transform to access the player position and I -1 away from _numSeedLeft to get it to reach 0 at that point the if statement stops the PlantSeed from working. While this is happening I give a +1 to the _numSeedsPlanted and I reuse the UpdateSeeds from the plant count UI the UI
Finally on the PlantCountUI I received the two numbers related to seedsLeft and seedsPlanted I convert those numbers to a string and assign it to the _plantedText and _remainingText

For the Week 1 in-class activity, we were asked how we would describe this game world in objects. Simply put, there is the player as a bunny sprite and a green flower sprite. The attributes and actions these objects have are as follows: You as the bunny are able to move in cardinal directions of up is W, down is S, left is A, and right is D. You can use the spacebar to make a plant sprite appear. And there are two counters– one for seeds remaining and one for planted seeds. 

These objects act on or affect each other because as you plant a seed, the number of seeds remaining goes down and the number of seeds planted goes up. When the number of seeds remaining reaches 0, you can’t plant anymore. 
docs
The plan I wrote down connects to the code as the playerTransform moves the player and the PlantCountUI, seeds remaining and seeds planted, show how many seeds you have left.

## Open-Source Assets
If you added any other outside assets, list them here!
- [Sprout Lands sprite asset pack](https://cupnooble.itch.io/sprout-lands-asset-pack) - character and item sprites
