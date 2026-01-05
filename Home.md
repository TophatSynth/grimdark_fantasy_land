# Our super-secret Homepage and workshop headquarters

---
```base
filters:
  and:
    - file.tags.contains("todo")
    - not:
      - file.infolder("Atlas")
properties:
  file.folder:
    displayName: Folder
  file.name:
    displayName: To work on
views:
  - type: table
    name: Table
    order:
      - file.folder
      - file.name
    sort:
	  - property: file.folder
	    direction: ASC
      - property: file.ctime
        direction: DESC
    columnSize:
      file.folder: 175

```

```base
filters:
  or:
    - file.tags.contains("toDecide")
properties:
  file.folder:
    displayName: Folder
  file.name:
    displayName: To decide on
views:
  - type: table
    name: Table
    order:
      - file.folder
      - file.name
    sort:
	  - property: file.folder
	    direction: ASC
      - property: file.ctime
        direction: DESC
    columnSize:
      file.folder: 175

```
---
## Notes here:

## TechSavvySynth's Notes:
- Need to read up on all the lore so far, then re-organise them so it's a lil clearer
 - [x] Use bases to make TOC 
	- [ ] Show number of todo tags per file?
	- MN: That would be cool and helpful!
- Work on alchemy 
- Spirit fragment types need thinking
- [x] Add my fireflower idea to [[Ironkeep (Name Placeholder)]] 
	- MN: {{It is fire. Literally}}
	- TH: {{lmao, ty}}

---
## BoomerNoiza's Notes:


> [!WARNING|no-t] Title
> The "Publish"-Frontmatter is used for Quartz-publishing shenanigans
> The "index" File is needed for Quartz also

- [[Ironkeep (Name Placeholder)]] has a Infobox, let me know if you like it (Needs ITS Snippet to work)

- Should one of the Towns be a little bigger? Maybe the Ocean one, so you have more room to play with? Have a couple other fitting maps too

- Would like an Alchemy-System (Tophead hard at work - Nice!)

- Flora & Fauna: Should we go full fantastical or use real world animals at least to keep things grounded (and less work)?
	- TH: {I'd say go with what we did for Vilenought. Real world animals, corrupted by the veil}
		- MN: {{I agree. Easier for immersion and less Exposition also}}



- Ideas to add for the Sandbox/Brainstorm Area:
	- Fortified Inns along the roads (The chain broken and Inns varying widely in architecture and state of repair)
	- "The Paladins" (Name pending) have a smallish keep in the area
	- There is at least one Thin-veiled area in the valley, allowing the "Predators" easy access

