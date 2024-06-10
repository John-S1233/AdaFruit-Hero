# AdaFruit Hero

## Game Description
This project is an interactive music game inspired by Guitar Hero, where players respond to descending lights by pressing corresponding buttons. The game features three primary states:

- **Home**: Allows the selection of songs.
- **Playing**: Plays the selected song and displays cascading pixels.
- **End**: Displays the final score and offers the option to continue playing.

### Game States
1. **Home**: Displays song choices.
2. **Playing**: Executes song gameplay.
3. **End**: Shows scores and prompts user to restart.

### Inputs (While Playing)
- **Left Button**: Trigger the note associated with the left LED string.
- **Right Button**: Trigger the note associated with the right LED string.

### Inputs (While Home)
- **Left Button**: Shifts selection left.
- **Right Button**: Shifts selection right.
- **Right & Left Button**: Selects song.

### Outputs 
- **Left LEDs**: Illuminate descending pixels on the left.
- **Right LEDs**: Illuminate descending pixels on the right.
- **Speaker**: Plays back the musical notes of the chosen song and says message at the end of game. 
- **Serial Monitor**: Displays song selection and score.

## Hardware Requirements
- Adafruit Circuit Playground

### Key Functions
- `setup()`: Initializes the game settings and hardware configurations.
- `loop()`: Contains the game logic cycling through different states.
- `changeState(GameState state)`: Manages transitions between game states.
- `displaySongs()`: Displays the current song selections.
- `leftButton()`, `rightButton()`: Interrupt service routines for button presses.

### Game Songs
- **Hot Cross Buns**
- **Twinkle Twinkle Little Star**
- **Mary Had A Little Lamb**

Each song has defined properties for duration, pitch, and associated LED strip.

