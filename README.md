# MG3
## Devlog
1. The default value for a float is 0.0, for an int is 0, and for a bool is false. A string is null by default, although it may appear empty in the Unity Inspector.
2. I think I do not need to call the Update() method ourselves. Unity automatically calls Update() every frame while the script is enabled. 
3. The TimerText class uses the Timer to keep track of how time is left. The Timer's Update() method decreases the remaining time every frame using Time.deltaTime. The TimerText class also uses Update() to display the remaining time and check if the timer has finished. When the time ends, it calls GameOver() to stop the player and show the game over message.

## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)
