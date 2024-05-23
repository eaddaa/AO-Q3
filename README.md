# AO-Quest-3 Bot

This bot is designed to compete in the AO-Quest-3 game by implementing dynamic strategies for movement and combat. It leverages real-time game state information to make decisions based on the player's energy level, proximity to enemies, and available resources.

Key Features:

1.Dynamic Strategy Switching: The bot dynamically switches between different movement and combat strategies based on its current energy level and game state. When low on energy, it prioritizes evasive maneuvers to avoid enemy encounters or seeks out energy packs for replenishment.

2.Advanced Movement Strategy: The bot utilizes advanced pathfinding algorithms to determine the safest direction to move when evading enemies. It considers multiple factors such as enemy proximity and available escape routes to optimize its movement decisions.

3.Handler Integration and Logging: The bot seamlessly integrates with game event handlers and logging functionality to track its behavior and decision-making processes. This allows for easy monitoring and debugging of the bot's actions during gameplay.

How to Use:

1.Installation:

```
```
2.Running the Bot:

```
aos bot --load bot.lua
```

3.Customization:
Feel free to customize the bot's behavior by modifying the code according to your preferences. You can adjust parameters such as energy thresholds, movement strategies, and combat tactics to suit your gameplay style.
