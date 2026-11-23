# Melvor Lookup

A **Lookup** tab for **Melvor Idle 2** on Linux. It sits next to Bank and opens a page
where you can search every item by name, type or use ("mining gear", "food",
"bronze"), filter by type, skill and where it comes from, and see every way to get
an item: drop chances, shops and costs, recipes, thieving loot, containers, quests.

It's part of the game's own interface, using the game's own tabs, tooltips and
styles, so it looks and works like the rest of Melvor.

## Install

1. Download **Install.Melvor.Lookup.zip** from the [latest release](../../releases/latest).
2. Extract it and double-click **Install Melvor Lookup**.
3. If it asks to restart Steam, say yes (Steam saves the game's launch options when it closes).
4. Start Melvor Idle 2 from Steam. The **Lookup** tab is next to Bank.

It updates itself from then on.

## Uninstall

Double-click **Install Melvor Lookup** again and choose **Uninstall**.

## How it works

The installer puts the mod's files in `~/.local/share/melvor-lookup/mod/` and adds
the mod's loader to Melvor Idle 2's launch options in Steam, keeping any options you
already had. Each launch, the mod reads the item data from your own copy of the game,
so it ships none of the game's files and keeps up with game updates. If a game
update ever breaks it, the tab simply doesn't appear until a fixed version arrives;
the game itself is never affected.

## Notes

- Melvor Idle 2 from Steam on Linux (the Flatpak version of Steam isn't supported).
- Not affiliated with Games by Malcs.
