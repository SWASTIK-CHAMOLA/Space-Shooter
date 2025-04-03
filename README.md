# Space Shooter Game

A fast-paced space shooter game built using Pygame. Dodge meteors, shoot enemies, and survive for as long as possible while increasing your score!

## Features

- **Smooth player movement** using directional keys
- **Laser shooting mechanics** with cooldown system
- **Randomly spawning meteors** with increasing difficulty
- **Score tracking system** with difficulty progression
- **Animated explosions** upon meteor destruction
- **Background music and sound effects**

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/space-shooter.git
```

Navigate to the project directory:

```bash
cd space-shooter
```

Run the game:

```bash
python main.py
```

## Controls

- **Arrow Keys**: Move the spaceship
- **Spacebar**: Shoot laser
- **R**: Restart the game (when in menu)
- **Q**: Quit the game (when in menu)

## Game Mechanics

- **Meteors spawn at intervals**, increasing in frequency as the score increases.
- **Colliding with a meteor** results in game over.
- **Shooting meteors** increases the score and triggers an explosion animation.
- **Difficulty increases over time** by reducing meteor spawn intervals and increasing their speed.

## Gameplay

![alt text](<Screenshot 2025-04-03 215633.png>) 
![alt text](<Screenshot 2025-04-03 220255.png>)
 ![alt text](<Screenshot 2025-04-03 220243.png>)
## Assets

- **Images** (Spaceship, Meteors, Laser, Stars, Explosions) in `images/` folder
- **Audio** (Laser sound, Explosion sound, Background music) in `audio/` folder
- **Font**: `Oxanium-Bold.ttf` located in `Rename/` folder

## Future Improvements

- Add power-ups and different weapon types
- Introduce enemy ships for more challenging gameplay
- Implement a high score tracking system
- Improve UI with more game modes and settings

## License

This project is open-source.

## Contributing

Feel free to fork this repository, improve the game, and submit a pull request!
