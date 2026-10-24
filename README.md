# CoreProtect Casebook

A field manual for Minecraft server staff who use [CoreProtect](https://docs.coreprotect.net/).

**Live site:** https://magomedovex-code.github.io/coreprotect-casebook/

## What's inside

- **Case walkthrough:** a player is killed, the loot is hidden in a buried chest, and some of it is duped. Ten steps cover finding the death spot, following the loot, proving the dupe, cleaning the stash and returning the items, without rolling back anyone else's things. Type your own suspect, victim and time window and every command updates.
- **Fast lane:** the whole case as a checklist with copy buttons, plus habits that make in-game investigations quick.
- **Radius lab:** an animated map that shows what a rollback reaches as you change `u:`, `r:` and `a:`.
- **Command builder:** builds a `/co` command, explains it in plain words and warns when it reaches further than intended.
- **Reference:** every `/co` command, all parameters, all 22 actions, purge rules, database migration and permissions.

## Ground rules it teaches

1. Run the exact parameters as `/co lookup` first, then swap `l` for `rb`.
2. Every rollback names who (`u:`), when (`t:`) and where (`r:`).
3. Remove loot from the thief's stash before returning it to the victim.
4. `/co undo` reverses a rollback or restore.

## Notes

- Built from the official [commands](https://docs.coreprotect.net/commands/) and [permissions](https://docs.coreprotect.net/permissions/) pages.
- Example chat output is illustrative. Wording differs between CoreProtect versions.
- An independent guide. Not affiliated with CoreProtect.

It is a single `index.html` with no build step. Open it in a browser to use it locally.
