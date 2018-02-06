# Design Process

## General
- Arrangement groups from top to bottom, left to right
- Group everything on a Frame/Artboard
- Group related Artboards/Frames into Pages

## Branch Names
- **_branch_name - modifer_** - Branch names (e.g. landing_page - regine)
- **_Adds new page_** - Commit titles

## Layer Names
- **_00-artboard-name_** - Artboard names must have numbers as prefixes. The number depends on the group where the Artboard belongs to. It is important to make Artboard names unique because these will be used when creating issues (revisions, edits, etc.) in Jira.
- **_component-name / modifier_** or **_symbol name / modifier_** - Symbol/Component naming (e.g. Button / Blue / Big)
- **_group-name_** - Group names (e.g. news-grid)
- **_name_** - Children names (e.g. card)

## Layer Names - Jira
- **__**

# Symbol/Component Categories
- Identity - e.g. background, icons, type
- Elements - e.g. icon + type, type + background
- Components - e.g. cards, checkbox
- Composition - e.g. list of cards, list of checkboxes
- Pages - Well, pages. Duh.

# Sketch
- Use **_Rename It_** for renaming layers (e.g. Find and Replace Layer Names).
- Avoid using Plugin-based Layout Functions (e.g. Auto Layout) for Symbols. As much as possible, use vanilla Sketch functions.
- Only use Auto Layout for **_Compositions_** (reference to **_Compositions_**).
- Arrange icons by artboard size depending on categories/use. This makes the use of icons for certain symbols stricter.
- Symbol naming should have a maximum of four levels. The last layer is always the modifier.
<!-- - When adding new symbols, add mini-instructions (e.g. use this button on yellow backgrounds) -->

# Editing Symbols (For Testing)
 - Designer makes a copy of the symbol edited.
 - Designer documents list of all edited symbols.
 - Everyone aligns every week.
 - Manager polishes library.

# Sketch -> Flinto

# Sketch -> Framer
- Rename all layers. Use camelCase.
- Minimize nested symbols unless it's a list of related items (e.g. card composition, checkbox composition, navigation items).

# Sketch -> InVision

# Flinto

# Framer

# Abstract
