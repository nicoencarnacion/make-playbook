# Sketch Design Process

## General
- Arrangement groups from top to bottom, left to right
- Group everything on an Artboard
- Group related Artboards into Pages
- Use **_Rename It_** for renaming layers (e.g. Find and Replace Layer Names).
- Avoid using Plugin-based Layout Functions (e.g. Auto Layout) for Symbols. As much as possible, use vanilla Sketch functions.
- Only use Auto Layout for **_Compositions_** (reference to **_Compositions_**).
- Arrange icons by artboard size depending on categories/use. This makes the use of icons for certain symbols stricter.
- Symbol naming should have a maximum of four levels. The last layer is always the modifier.

## Layer Names
- **_00-artboard-name_** - Artboard names must have numbers as prefixes. The number depends on the group where the Artboard belongs to. It is important to make Artboard names unique because these will be used when creating issues (revisions, edits, etc.) in Jira.
- **_group / type / modifier_** - Symbol naming (e.g. Icon / Arrow / Active)
- **_group-name_** - Group names (e.g. news-grid)
- **_name_** - Children names (e.g. card)

## Symbol/Component Categories
- Identity - e.g. background, icons, type
- Elements - e.g. icon + type, type + background
- Components - e.g. cards, checkbox
- Composition - e.g. list of cards, list of checkboxes
- Pages - Well, pages. Duh.

## Editing Symbols (For Testing)
 - Designer makes a copy of the symbol edited.
 - Designer documents list of all edited symbols.
 - Everyone aligns every week.
 - Manager polishes library.
