---
layout: page
title: Game Modes
parent: Getting Started
nav_order: 3
---

# Adventure vs. Creative Mode

Alive mod offers two distinct modes of operation: Adventure Mode and Creative Mode. Each provides a different experience and level of interaction with villagers.

## Adventure Mode

Adventure Mode is the default setting for Alive mod, designed to provide an immersive, seamless experience with minimal setup.

### Key Features of Adventure Mode

- **Automatic Character Activation**: Villagers are automatically enabled as interactive AI characters.
- **Direct Interaction**: Simply Shift + left-click on any villager to start a conversation.
- **Seamless Integration**: Works naturally within the game world without requiring additional items.
- **Immersive Experience**: Villagers have personalities, backstories, and knowledge based on their profession.

### When to Use Adventure Mode

Adventure Mode is ideal for:

- Players who want an immersive roleplaying experience
- Survival or adventure gameplay where natural villager interactions enhance the world
- Those who prefer a "plug and play" experience without additional setup

## Creative Mode

Creative Mode offers more control and customization but requires additional steps to interact with villagers.

### Key Features of Creative Mode

- **Manual Character Activation**: Villagers are not automatically enabled as AI characters.
- **Book and Quill Required**: You must use a Book and Quill to create custom prompts for villagers.
- **Greater Customization**: More control over how villagers respond and what knowledge they have.
- **Targeted Interactions**: Only villagers you specifically configure will have AI capabilities.

### Using Books and Quills in Creative Mode

1. **Create a Book and Quill**: Craft or obtain a Book and Quill in-game.
2. **Write Your Prompt**: Write instructions for how the villager should behave, what they know, etc.
3. **Name a Villager**: Use a Name Tag to give a villager a unique name.
4. **Sign the Book**: Sign the book with the exact same name as the villager.
5. **Apply the Prompt**: Sneak-click the book in the air to set the prompt for that named villager.

### World Prompts

In both modes, you can create a Book and Quill titled "World" to apply prompts to all non-named villagers, allowing for broad creative storytelling.

### When to Use Creative Mode

Creative Mode is ideal for:

- Map makers and server administrators
- Custom adventure maps or scenarios
- Players who want precise control over villager behavior
- Those creating specific storylines or quests

## Switching Between Modes

You can switch between Adventure and Creative modes by editing the configuration file:

1. Open the `config/alive.json` file
2. Change the `"mode"` value to either `"adventure"` or `"creative"`
3. Save the file and restart Minecraft

For detailed configuration instructions, see the [Configuration Guide]({{ site.baseurl }}/getting_started/CONFIGURATION).

## Comparison Table

| Feature                 | Adventure Mode          | Creative Mode          |
| ----------------------- | ----------------------- | ---------------------- |
| Automatic villager AI   | ✓                       | ✗                      |
| Requires Book and Quill | ✗                       | ✓                      |
| Custom prompts          | ✓ (with Book and Quill) | ✓ (required)           |
| World prompts           | ✓                       | ✓                      |
| Best for                | Immersion, simplicity   | Customization, control |

Choose the mode that best suits your gameplay style and creative needs!
