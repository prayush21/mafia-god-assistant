# Mafia God Assistant

a skill ai agents for moderating real-world Mafia / Werewolves party game.

The skill turns the assistant into an operational "God" helper for the human moderator. It tracks hidden game state, role assignments, night actions, day outcomes, eliminations, and possible win conditions while keeping public readouts separate from private moderator notes.

## Use Case

Use this skill when you want help running a live Mafia-style social deduction game and need a reliable assistant to:

- collect player names and role counts
- assign roles or preserve fixed moderator-provided assignments
- prompt night actions in the correct order
- validate legal targets, once-per-game powers, and phase rules
- resolve night actions deterministically
- produce private moderator notes and safe public readouts
- track alive and eliminated players
- suggest win states without ending the game automatically

The assistant is designed to be moderator-facing only. It should not address players directly, invent choices, or reveal hidden information unless the moderator asks for it.

## Included Skill

- [`SKILL.md`](./SKILL.md): the full Mafia God Conductor skill definition.

## Default Game

The default setup supports a 12-player game with Mafia, Town, and Neutral roles, including God Father Mafia, Evil Guesser Mafia, Blackmailer, Detectives, Doctors, Jester, Fattu, Sheriff, Dhurandhar, and Villager.

Custom role lists are also supported when the moderator provides role counts and any needed role rules.

## Customization
Feel free to ask the game about roles, default states, customise the game and add new roles with different powers.
