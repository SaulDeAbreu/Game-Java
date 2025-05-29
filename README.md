# Game-Java: 2D Action Game with libGDX

This is a 2D action game developed with Java and libGDX where you control a character that must collect items and avoid obstacles.

## Game Features

- Fluid character movement control
- Shooting system
- Scoring system
- Health system
- Item collection
- Visual effects and animations
- User interface with score and game status

## Prerequisites

To run the game, you'll need:

1. Java Development Kit (JDK) 8 or higher
2. Gradle (the project includes Gradle Wrapper, so manual installation is not necessary)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/SaulDeAbreu/Game-Java.git
cd Game-Java
```

2. Build the project using Gradle:
```bash
# On Windows:
gradlew desktop:build

# On macOS/Linux:
./gradlew desktop:build
```

## Running the Game

To run the game:

```bash
# On Windows:
gradlew desktop:run

# On macOS/Linux:
./gradlew desktop:run
```

## Game Controls

- **Movement**: Use arrow keys to move the character
- **Shoot**: Press spacebar to shoot
- **Exit**: Press any key after winning or losing

## Game Objective

- Collect all items to win
- Avoid losing all your health
- Achieve the highest score possible

## Project Structure

The project is organized into two main modules:

- `core/`: Contains the main game logic
- `desktop/`: Contains desktop-specific configuration

## Development

The game is developed using:

- Java
- libGDX 1.9.12
- Gradle as build system

## Troubleshooting

If you encounter any issues running the game:

1. Make sure Java is installed correctly
2. Verify you're using the correct JDK version
3. Clean and rebuild the project:
```bash
# On Windows:
gradlew clean desktop:build

# On macOS/Linux:
./gradlew clean desktop:build
``` 