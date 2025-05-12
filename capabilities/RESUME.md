---
layout: page
title: Resume Activity
parent: Capabilities
nav_order: 6
---

# Resume Activity

## What is Resuming Activity?

This capability allows you to tell a villager who is currently waiting (because you asked them to using the [Wait](WAIT.md) command) that they can stop waiting and go back to their usual tasks. This provides a natural way to release the villager from the waiting state.

## How It Works

When a villager is waiting, they are actively being kept in place by a special AI goal. If you tell them something like "You can go now", "Stop waiting", or "Resume your activities", the AI can trigger the `resume_activity` function.

This function simply removes the internal `isWaiting` flag associated with that villager. Once the flag is gone, the special waiting goal stops running, and the villager's AI will automatically switch back to its normal behavior. This might mean they start following you again (if the conditions for the follow goal are met), wander off, or return to their job site.

## Why Resume Activity?

Just like asking a villager to wait, telling them when they can stop waiting adds to the realism and control you have over interactions:

1.  **Clear Control**: Explicitly releases the villager from the wait command.
2.  **Natural Interaction**: Feels more polite than just walking away while they are waiting for you.
3.  **Flexibility**: Allows you to pause and resume interactions as needed.

## Example Interaction

_(Villager is currently waiting)_

**Player:** "Okay, you can stop waiting now."
**Villager:** "Alright, back to it!"

_(Villager stops waiting and might start following the player or wander off)_

## How to Trigger Resuming

You can typically trigger this by saying:

- "Resume"
- "Stop waiting"
- "You can go now"
- "Carry on"
