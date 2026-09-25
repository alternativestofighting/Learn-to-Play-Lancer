# Recommended Setup Guide
While I've designed this mission to work right out of the gate without any modules (or with only those you are comfortable with), I've also set things up to be a showcase of how **surprisingly easy** it is to set up and use powerful, awesome automation and VFX modules. The Lancer VTT community generally recommend to avoid using complicated or advanced modules, like Lancer Automations, Grid-Aware Auras, or Carolingian UI, without spending time learning the basics of Foundry, Lancer's system on Foundry, and even pre-reading the entire documentation of these modules. I believe that if you can learn how to use them early and are willing to ask for help, you don't need to fear them - or run/play in a game that doesn't look damn incredible.
Here's a step-by-step guide to how to set up this adventure with all of the modules I designed it with:
1. Create a new world.
   When you log in for the first time, you're going to be barraged by tutorials, tours, pop-ups, etc. Feel free to follow them or close them out, but watch for one called "Lancer Compendium Manager."
2. Use the "Lancer Compendium Manager" tool to import all freely-available LCP content.
   All you need to do is click the "Import/Update Selected" button on the prompt without configuring anything. It will take a few minutes. Close it when it finishes!
3. Click the "Game Settings" button on the sidebar (the 'gear' icon) and click the Manage Modules button on that page. In the pop-up that appears, check "Module Profiles", then click the "Save Module Settings" button.
   This will **restart the world**.
4. Return to the Game Settings page, click the "Manage Modules" button again, then click the "Manage Module Profiles" button.
5. Click the "Import Profiles" button. Paste the entire contents of the [Module Profiles](/foundry-configs/module-profiles_learn-to-play-lancer.txt) list into the empty box here, then click the "Import Profile" button.
6. Click the green "Activate" button for the Learn to Play Lancer profile.
   This will **restart the world**.
7. Download the [Foundry Settings Export JSON](/foundry-configs/foundry-settings-export_learn-to-play-lancer.json) file from this repository.
8.  Go to the Game Settings page, then right-click the upper-right area (where you see "Foundry Virtual Tabletop, the Build Version, the Lancer system version, and the Active Module count) and choose "Import Settings" from the drop-down menu.
9.  Select the file you just downloaded and click the "Import Settings" button.
    This will **restart the world**.
11.  Click the "Compendium Packs" button on the sidebar (the "closed book" icon), then the "Adventures" entry below. In the window that appears, open the "Learn to Play Lancer" adventure.
12.  Click the "Import Adventure" button. This will load everything you need to run the mission!

## How to Run the Mission
I'll try to expand this as I can, but for now, just run the game as you like! Here are some tools I've added for your use:
* The "Journals" button in the sidebar (the 'open book' icon) has tons of helpful information for you and your players.
* The "C1" and "C2" folders have journals that will walk you through both of the combat scenes. There is a unique journal for each scene for three, four, or five players. Open the one that matches your player count, read the "Description" page for setup and operational instructions, and use the "Monsters" list to drag-and-drop enemies onto the map.
* NPCs will each have a number and/or letter in their name in the Actors sidebar tab and the encounter journals. The first number notes the number of players for which the enemy will be deployed, and the number after 'R' notes the number of players required for that NPC to be in the Reinforcements pool for the mission.
* The "Campaign Notes" folder in the Journal sidebar tab is basically a starting point for making narrative journals for your game. The Mission Objectives entry is handy for letting players track their goals and progress towards them. They can see these quests and their progress when they use the "Journal Notes" tool on the left of their screen.
* The "GM Resource" folder in the Journal sidebar tab has general instructions and help for you running the game. Particularly, the Macro Instruction entry explains the five custom VFX modules I've added to the adventure. They don't mechanically change the game, but they are extremely helpful for keeping track of targets of Covering Fire and Projected shield, who is protected by Smoke Grenades & Mines, and... making your Hive: Razor Swarms look very cool.
* The "Player Resource" folder in the Journal sidebar tab has references for your players to use while playing. I have simple guides for how to use Foundry tools in this game, Action options available in combat, what happens in a Skill Trigger during Narrative Play, and a list of common terms and concepts in the Lancer setting. If you want them to have a durable Notes page/Personal Journal that isn't overwritten when the players update character sheets from Comp/Con, I strongly recommend making a copy of the "Player Journal Template" for each player and assigning them "Owner" permission for it.

Have a good time!
