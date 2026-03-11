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

## Week 6

### Activity 1
Profiler: Demonstrates the stats of fps in your game and calls out what certian functions are taking longer to execute and run- this would be useful to figure out why the game might be glitching upon running it. 

Gizmos: To detect collisions and interactions within the game and being able to see that visually.

Breakpoints: A deeper way to look into debugging and managing errors.

### Activity 2 
Team members present : Alejandra, Gianine
[Here is the link to our project proposal's final draft](https://docs.google.com/document/d/1zNEI6Q6prvof6MZBIPg397B4LSM3YyidLB--5WPzAQw/edit?usp=sharing)

## Week 7

### Activity 1

- The Red Raycast shows interaction and how the duck percieves/sees depending on if the player is in the line of sight or not.
- Use of state machine to dictate how the duck moves if it moves around or pursuses the player
- Raycast throws an arrow into the scene to visualize if it hit something. Red ray cast specifically in that method draws the length to which the duck is able to see/interact with. 
- out hitinfo (raycast is filling in with that info) hitinfo.point - tells where in the world the raycast hit if anywehre. 
- yellow dot, shows an indication where the duck collides with which then triggwers it to move elsewhere. 
- sphere cast- area contained within a sphere - checking for obstacles. 


### Activity 2

Team members present : Alejandra, Gianine

### Activity 3
![Breakdown Final](https://github.com/user-attachments/assets/114765d7-02d8-46d4-a575-d34c37f803e8)



### Acvtivity 4

[Here is the link to our trello board](https://trello.com/b/Xaon9XV2/gdim-32-group-board)

### Activity 5

[Link To Commit](https://github.com/Winterfall4/GDIM32-Final/commit/13e6168e44bb52679e080d272ef520419e6bd966)

During the class period the commit I contributed to our final project is some code to make the player move from a third person perspective and have added background music into the scene. 

## Week 8 

### Activity 1
- rendering pipeline- sequence of instructions of how things will be drawn on the screen
- check what pipeline you are using and make sure your assests fit into that pipeline. 
- built in a different unity vers. can still work
- post processing: affects the look of your game through shaders.
- color settings: changing visual tone of your game
- run the itch game after putting a post processing to see if it runs okay. 


### Activty 2

Team members present : Alejandra, Gianine 

### Activity 3
- lagging 
- hard time with camera
- sensitivity issue 
- Make setting where players could change sensitivity 
- Rocks are launching people
- people like the enviornment and UI.

### Actvity 4

Im going to make the inventory UI 

### Activty 5 

[Link to Commit](https://github.com/Winterfall4/GDIM32-Final/commit/c053160f0a77bb12b8b11b9ac6019ff874e067a6)

During class I imported the inventory UI and imported it within the scene.

## Week 9

### Activity 1

- scaling: good scaling handles a LOT of data!
- dialogue nodes being used for each possible interactions 
- Dialogue Controller cs if using multiple npcs with unique dialogue. > SetActive npc variable that tracks when the player interacts with an npc and checking WHICH npc it is talking to before sending the game to that npcs dialogue logic. 
-  public void SetActiveNpc (NPC npc) " _activeDialogue = npc._dialogueStartNode" when the player begins interaction with npc sets the node to that particulaur node. 
	- 
### Activity 2
Team members present : Alejandra.

### Activity 3 
Playtesting Notes:
Goal: Is pressing Q a good way to drop the flowers? is the inventory system understandable and practical?

- inventory system works well
- issues still with canmera on player- move to left or right.
-  click e to interact with flowers instead of mouse click?

### Activity 4

In terms of our project's scope I think we are doing really good with our progress, we are pratically half way through our game's project and with a new understanding towards the dialogue system, since 
dialogue is the main mechanic of our game we are postive that we can get through and complete the game on time.

### Activity 5

[Link to Commit](https://github.com/lindenreid/GDIM32-Final/commit/10cb0a102403c9f46d63cfbebcdea5b016e28287)
In this Commit I started on creating the ScriptableObjects for one of the NPCs as well as setting up the required scripts for the dialogue. 


## Week 10

### Activity 1

Team members present : Alejandra, Gianine 

### Activity 2

Playtesting Notes:
- Camera is still wonky
- Npc feature is cool
- Alt = mouse leaves, weird. 
- Nice UI.
- inventory is 50/50 when picking stuff up.

### Activity 3

I believe that our final project is around 70 percent complete. I will say that the final things that need to be done are very time consuming to figure out which is the dialogue and figuring out how to mix different methods together but 
I am positive that we are able to make it by the deadline.

### Activity 4

[Link to Commit](https://github.com/Winterfall4/GDIM32-Final/commit/6963ab87a483bc181a26acca7f82363629889891) 
In this commit I had done some tweaking with the Dog's dialogue to try to get it to activate within the game and hve tried to assign it's properties though it needs to still be reworked. 