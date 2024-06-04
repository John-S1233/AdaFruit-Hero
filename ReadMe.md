# Interactive Music Game

## Game Description
This project is an interactive music game inspired by Guitar Hero, where players respond to descending lights by pressing corresponding buttons. The game features three primary states:

- **Home**: Introduces the game rules and allows the selection of songs.
- **Playing**: Plays the selected song and prompts user interaction.
- **End**: Displays the final score and offers the option to continue playing.

### Game States
1. **Home**: Displays rules and song choices.
2. **Playing**: Executes song gameplay.
3. **End**: Shows scores and restarts or exits options.

### Inputs
- **Left Button**: Trigger the note associated with the left LED string.
- **Right Button**: Trigger the note associated with the right LED string.

### Outputs
- **Left LEDs**: Illuminate descending pixels on the left.
- **Right LEDs**: Illuminate descending pixels on the right.
- **Speaker**: Plays back the musical notes of the chosen song.

## Hardware Requirements
- Adafruit Circuit Playground
- Optional: External buttons and LEDs for enhanced gameplay

## Software Requirements
- Arduino IDE or compatible IDE for editing and uploading the firmware.

## Code Overview
The core functionalities include managing game states, handling inputs through interrupts, and controlling outputs like LEDs and speaker based on the game logic.

### Key Functions
- `setup()`: Initializes the game settings and hardware configurations.
- `loop()`: Contains the game logic cycling through different states.
- `changeState(GameState state)`: Manages transitions between game states.
- `displaySongs()`: Displays the current song selections.
- `leftButton()`, `rightButton()`: Interrupt service routines for button presses.

### Game Songs
- **Hot Cross Buns**
- **Enter Sandman**

Each song has defined properties for duration, pitch, and associated LED strip.

## Installation
1. Connect the hardware as per the schematics provided in the `schematics` folder.
2. Open the Arduino IDE and load the game code.
3. Compile
