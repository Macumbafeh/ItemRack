ItemRack
========

Fork of ItemRack ver. 2.23 addon. [Wow 2.4.3]

Improvements
------------

### Preview

You can easily preview how the set looks like in two ways:

- control-click a set in the set drop-down menu,
- with `/itemrack tryon set_name` slash command.

### Edit items by ID

While in set edit view, you can middle-click the chosen slot to display
a prompt for numerical item ID to be set.

### Inspect sets

You can quickly save the item set of inspected character. Just use the
`/itemrack saveinsp` slash command while inspecting someone. The created
set will be named after the inspected character and talent spec.

### Tooltip info

When hovering over an item, the list of all user sets containing it will appear
in the game tooltip. Think of it this way: define your wish list set and you'll
see this set's name when looting items from bosses!

### Set pool

Now you can move sets around characters with ease! Just use the `/itemrack pool`
slash commands:

```
/itemrack pool push set_name      Moves the set from user set list to the pool.
/itemrack pool pop set_name       Moves the set back from set pool.
/itemrack pool list               Lists all saved pool sets by name.
```
