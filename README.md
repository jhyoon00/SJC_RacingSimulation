# Racing Simulation Game

## About the Project

We will be making a simple **racing simulation game**. By simulation, we don't mean first-person simulation games like _Euro Truck Simulator_, but rather decision-making simulation games like _The Sims_ or _Football Manager_.
<br>

**Team members:**
- JH Yoon
- Figo Wu
- Abraham Chandafa
- Sudikshya Pant
- DH Bae

Communication will be done through Whatsapp. Welcome to the team!
<br>

## About the Game
The player controls a sports car racer. This is not a racing game, i.e. the player doesn't control the racer during a race. Instead, the player has control over the racer's decisions: which car to buy, which equipment to install or upgrade, which skills to train, which technicians to hire, which tournaments to compete in and using which car, etc. The game is essentially about making smart decisions to eventually become a successful racer.

### Interface
Below is a preview of how the home screen might look once the game is complete:
![interface outline](https://github.com/jhyoon00/SJC_RacingSimulation/assets/77221627/ada529c2-031f-470e-acc0-20148cde1393)
The sections highlighted in _YELLOW_ are in-game **objects**. The sections highlighted in _GREEN_ are **actions**, meaning clicking them will allow the player to interact, such as entering a new window.

### Objects
Some objects shown in the home screen include:
- **Name:** Player name (racer's name)
- **Info & traits:** Player information (age, world ranking, market value, etc.) and player traits (skills)
- **Money:** How much money the player currently has
- **Date:** In-game date
- **Menu:** This bar shows some of the actions that the player can do.
- **Current selected car:** Shows the current selected car
- **Sponsor:** Shows current sponsor(s)
- **Car info:** Basic car info, speed, etc.

### Actions
The actions available in the home screen are the following:
- **Weekly Calendar:** Shows current schedule for week. Clicking the bar brings player to a **Monthly Calendar** window.
- **Achievements:** Shows a simplified list of achievements. Clicking the bar brings player to a more extensive **Achievements** window.
- **Continue:** Clicking the bar skips forward in time until there is a new available event.
- **Office:** Clicking the bar brings player to the **Office** window, where the player can deal with contract matters with sponsors, technician team, and make other business-related actions.
- **Garage:** Clicking the bar brings player to the **Garage** window, where the player can change cars, purchase new cars, purchase/install/upgrade equipment, etc.
- **Tournaments:** Clicking the bar brings player to the **Tournaments** window. where the player can view and register for upcoming tournaments.
- **Training Track:** Clicking the bar brings player to the **Training Track** window, where the player can train to improve skills.
- **Settings:** Clicking the bar brings player to the **Settings** window, where the player can change settings regarding interface, sound, etc.


## About the Tasks
We will obviously begin with a more simplified version of the game, and build upon it by adding more interesting features later on.

**Procedure**
1. Create a text-based, simpler version of the game with minimal actions and objects
2. Create visual interface
3. Add more objects and actions to improve game
<br>

A simpler version of the game will possibly involve 4 different windows:

### 1. Home
![home](https://github.com/jhyoon00/SJC_RacingSimulation/assets/77221627/e81a6a84-a64b-49e7-8c56-43b037918d45)
The main window where the game is played. Player can view current money, date, and upcoming race (objects are highlighted in yellow). Actions include **Garage**, **Tournaments**, and 'Skip to next day' (highlighted in green). 'Skip to next day' becomes 'Begin race' when there is a race that day.

### 2. Garage
![garage](https://github.com/jhyoon00/SJC_RacingSimulation/assets/77221627/7b7800d8-7819-4591-9dbf-4cb5bd4275ca)
Window where player can view cars. Player can purchase, upgrade, and select which cars to use for the upcoming race.

### 3. Tournaments
![tournaments](https://github.com/jhyoon00/SJC_RacingSimulation/assets/77221627/27ebb2a7-9c2f-44ad-b87b-feb042b060e1)
Window where player can view upcoming tournaments and their information. Player can choose which tournaments to register in.
  
### 4. Race
![race](https://github.com/jhyoon00/SJC_RacingSimulation/assets/77221627/227d0335-4d8e-475c-b226-864e30cd7390)
Window that is entered when race begins. Shows brief outcome of the race and the prize that player receives.

<br>
Simply put, we will first aim to create this version of the game above by 1. using text-based interface 2. replacing it with real interface 3. adding more aspects to the game to complete it.

### Things to add later
Some ideas for things to add once we have the basic game include:
- Player name
- Player design (character)
- More car options, with more details
- Car design
- More upgrades & detailed upgrades
- New object: Driving skill
- New object: Vehicle familiarity
- Calendar Window: A window where player can view upcoming events visually
- Office Window: A window where player can make new kinds of decisions such as signing contracts with teams, sponsors, hiring new technicians, etc.
- More tournaments
- Training Track Window: A window where player can improve racer's driving skills
- Settings Window: A window where player can customize settings such as sound / save or exit game
- Starting Window: A window that opens once game is started, allowing player to input name
- ... and more! Feel free to suggest new ideas.

## Responsibilites and Work Distribution
For now, we are looking to use python's pygame library to code. JH will write most of the main.py file. There will be many functions available for you to write, so feel free to take responsibility to write some of them. However, make sure you know what you are doing, and also make sure you write a lot of comments so others can read your code! <br>

Most of the work will be divided into two types: **Interface Design** and **Game Logic**. <br>

### Responsibilities
| Interface Design | Game Logic |
| -------- | -------- |
| JH | JH |
| DH | DH |
| Sudikshya | Sudikshya |
| Figo | Figo |
<br>

Everything mentioned above is merely an outline, and everything is susceptible to change if there are good ideas. You are always welcome to give new suggestions on where to bring this project - so please share!<br>

Good luck!
