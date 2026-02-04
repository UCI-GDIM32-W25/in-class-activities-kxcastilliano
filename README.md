# GDIM32 In Class Activities
## Author: Kai Castilliano


## Week 1
### Activity 1

Some advice that my table and I had came up with would be :

- Take good notes that you can look back to come time where we need to apply our learning
-  Take advantage of support when in need of assistance: peers, LAs, Office hours. 
- Don't wait last minute to do things, don't procrastinate minigames because you never know if you have to get extra assistance 
- Take the time to read the pre-learnign slides. 
- Ask Questions if unclear about something. 
- Look for resources out of class for more details about something you're confused about. (Youtube, Unity Documents)
- Map out concepts in order to condense anything confusing. 
- Create metaphors. 

### Activity 2
	
	1. 1. 10 ( x is being multiplied by 5 )
	2. 2 
	3. The words "hello world" are shown in the console. 
	4. MonoBehavior
	5. The words "x = 10" print in the console.
	6. Argument = (10) value that is used for method  Parameters: Set Boundaries to methods/ Blueprint of method  (" x= + x").
	7. The _playerTransform variable is instantiated but never used.
	8. Transform.Translate should be replaced with _playerTransform.Translate.

### Activity 3
	[Here is the Link to our Google Doc observations](https://docs.google.com/document/d/1hYNliasaT5HCwedvTw8yrg4QrNS10bXhExGOnQw6uGg/edit?usp=sharing)

## Week 2
### Activity 1

![M2 BREAKDOWN ](https://github.com/user-attachments/assets/5eeefc24-666b-42ac-8200-3e7efcf74706)

### Activity 2
[Here is the link to the progress I made in MG2](https://github.com/UCI-GDIM32-W25/mg2-kxcastilliano/commit/ef0f744b5eea515811ec948e213fb6c4d6505cd2)

In this commit I had created the scene for my game and establihed the hiearchy by makign gameobjects such as the player, the canvas, the ground etc. I had then proceeded to make the two classes for the minigame (player and Gamecontroller) and
once that was completed I had spent my time breaking down the player script and working on the player's jump function (also added all colliders to objects).

## Week 3
### Activity 0-2

Partner Name: Gianine Umali

### Activity 3

![W3 BREAKDOWN](https://github.com/user-attachments/assets/1503d119-ce46-43c5-b51e-b3720134e7b9)

## Week 4
### Activity 0 

Worked with table members (Bella, Alejandra, Laura, Bilal)

### Activity 1

If you add multiple locators into the gameobject, all locators will delete until their is only one locator left in the scene.

### Activity 2
![MG4 BREAKDOWN](https://github.com/user-attachments/assets/7f59b9f4-d191-446c-8240-0e602bee4ab3)


### Activity 3

[Here is the progress I made for MG4](https://github.com/UCI-GDIM32-W25/HW4/commit/d1c244212df4e002b2bd378ff4b05404b2a7f6fb)
In my committ for MG4, I couldn't get anything code wise but I did get all my sprites and scripts situated. Other than that I made a player Ganmeobject that can be used for reference when I do get to coding. 
>>>>>>> 0747efce619acccdaa6413a2ed37b54eebe4f4d2


## Week 5

### Activity 1
I believe that the structure of these classes does get the job done however it feels very overly complicated and the scripts look very jam packed with code- I wonder if we 
could implmenet scriptable objects or if we just made two seperate scripts for the parent class- just so that visually the code looks more organized and understandable from a programmers perspective.

### Activity 2

In the Demo 2, the classes that represent the model of the game would be the scriptable objects (item, Enemeny) as well as the Enemy classes- these classes cary data that happen within the game even when they aren't present to the player. The view classes in this system
would be the dialogue bubbles, the sprites and the inventory UI- these classes ae shown visibly to the players when they interact with the game; The players are able to see the enemy's sprites on their screen, their dialogue when the player gets close
and the inventory when space is pressed. The control class of this system is the player considering that the player's actions determine the outcome of how the game behaves (for example: Player must be in a certain range in order to activate the enemy dialogue).

### Activity 3

#### Scenario 1
- Prefab for click or to show players a beat needs to be hit 
- Scriptable object for data of where the beat needs to be in the song, for each particulaur beat


#### Scenario 2
Ideas:
- Possible scriptable objects for each character in order to easily assign unique behavior 
- Events that trigger certain eleements Ex: When the player is shooting it deals damage to opposing player , when the player dies it shows the UI to the other players that the player hd been killed and sends the dead player to respawn or a seperate spectating area
- Singleton use for the UI as a locator that way the game is able to store all their ui events and such in one place
- parent class that can inherit behaviors from all players with their shared mesh, health, movement,  and attack. 
- Enum: Need certain states such as Dead, Alive, Respawn, Shooting, etc...
#### Scenario 3

- State machine- the state of the plant's growth or the player's current action within the game 

### Acvivity 4

Team Members: Alejandra, Gianine
[Here is the link to our project proposal](https://docs.google.com/document/d/1zNEI6Q6prvof6MZBIPg397B4LSM3YyidLB--5WPzAQw/edit?usp=sharing)