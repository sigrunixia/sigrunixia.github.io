---
has_children: true
has_toc: true
layout: default
nav_order: 3
permalink: /:path/:basename
title: "The Basics of Fantasy Statblocks"
---

# Using Fantasy Statblocks

The majority of your interactions with Fantasy Statblocks will start and end with this piece of code block language:

````yaml
```statblock
monster:
```
````

Within statblock, 


All fields are optional - if not provided, that Statblock will simply not render them.

The monster field may be combined with other fields to override the field. See Overriding Fields.

The spellcasting trait requires a special field (spells) - See Spellcasting

⚠️ YAML Syntax

Please note that the parameters provided in the statblock are parsed as yaml.

YAML is incredibly powerful, but you must pay attention to your syntax or you may get errors!

Common errors include: not putting quotes around parameters with : or * (such as Melee Weapon Attack:) and not indenting properly.