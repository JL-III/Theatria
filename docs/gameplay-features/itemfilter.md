# Item Filter

The `/itemfilter` command allows players to manage an item filter, a feature designed to make inventory management more efficient by automatically ignoring unwanted items when picked up. You can customize what items are filtered and toggle the filter on or off as needed.

## Command Overview

- **Command**: `/itemfilter`, `/if`
- **Available At**: Rank **Paragon**
- **Subcommands**:
  - `/itemfilter menu`: Opens the filter menu.
  - `/itemfilter toggle`: Toggles item filters on or off.
  - `/itemfilter reset`: Resets all filters.
  - `/itemfilter add <item>`: Adds an item to your filter.
  - `/itemfilter remove <item>`: Removes an item from your filter.

## Related Commands

- **/trash**: Discards items from your inventory permanently. Available at rank \*\*Eques\*\*.
- **/clearinventory**: Clears your entire inventory instantly. Use with caution. Available at rank \*\*Hero\*\*.

For a complete list of commands and their availability, visit the [Commands Page](commands.md).

## Why Use Item Filters?

Managing your inventory can be challenging, especially when collecting large amounts of materials or farming in specific areas. The item filter feature ensures you only pick up the items you need, reducing clutter and saving time. Here are some common use cases:

- **Mining**: Avoid collecting excessive cobblestone or other common blocks you don’t need. Add them to your filter so you can focus on rare resources like ores.
- **Farming**: Filter out seeds if you’re only interested in crops, or toggle the filter off temporarily when you need seeds for replanting.
- **Mob Grinding**: Ignore junk drops like rotten flesh while focusing on valuable loot like rare mob drops.

## Example Usage

### Filtering Cobblestone While Mining

1. Add cobblestone to your filter: `/itemfilter add cobblestone`
2. Enable the filter: `/itemfilter toggle`
3. Mine as usual, and cobblestone will be left on the ground.

### Gathering Seeds While Farming

1. Disable your filter: `/itemfilter toggle`
2. Collect seeds for replanting.
3. Re-enable your filter once done: `/itemfilter toggle`

## Notes

- Try `/itemfilter menu` to filter out various common items. If the item isn't listed in the menu, you can use `/itemfilter add` to add other items by name.
- Toggling the filter does not affect your list; it simply enables or disables the filtering behavior.

Use the item filter feature to keep your inventory organized and your gameplay experience smoother!

---

[Gameplay Features](./README.md)