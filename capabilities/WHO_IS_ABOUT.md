---
layout: page
title: Who Is About
parent: Capabilities
# nav_order: TBD (Will determine based on alphabetical or logical order later)
---

# Who Is About Function

## What Is the Who Is About Function?

The Who Is About function allows the AI entity (the villager you are interacting with) to provide a summary of other known villagers who are currently present in the world. Unlike "Look Around," this function focuses specifically on villagers listed in the mod's internal data store and checks if they are currently loaded, regardless of their distance.

## How It Works

When you ask the AI entity "Who is about?" or a similar question, it uses this function. The AI checks its list of known villagers (from the `EntityDataStore`) against the entities currently loaded in the world. It then uses its language capabilities to generate a natural summary of which known villagers are present, mentioning their names (if available) and professions.

## Benefits of Using Who Is About

- **Presence Check:** Quickly find out which known villagers are currently loaded and active in the world.
- **Role-Playing:** Get a conversational update on the status of other villagers in the community.
- **Information Gathering:** Useful for understanding which key villagers are available without needing to search visually.

## How to Trigger Who Is About

You can ask the AI entity about other villagers by:

1.  **Direct Question:** Ask "Who is about?" or "Which villagers are around right now?"
2.  **Chat Suggestions:** Click on a suggestion related to checking who is present if one appears.

## Example Who Is About Interaction

**You:** "Who is about today?"
**AI Villager:** "Let's see... Bob the Farmer and Alice the Librarian are currently around."

**You:** "Are any other villagers here?"
**AI Villager:** "It seems only Nitwit Ned is present right now."

**You:** "Who is about?"
**AI Villager:** "Hmm, I don't see any of the other villagers I know in the world at the moment." (If no known villagers from the store are currently loaded).

## Tips for Using Who Is About

- This function relies on the villagers being registered in the `EntityDataStore`.
- It only reports villagers who are currently loaded in the game world. Villagers in unloaded chunks won't be listed.
- The AI generates a summary, so the exact wording may vary.

The Who Is About function provides a dynamic way to check on the presence of known villagers through conversational interaction.
