# Overview

Base structure for an Obsidian vault containing templates, snippets, note bases, and auxiliary scripts. Designed as a reusable skeleton for personal organization, Zettelkasten, project management, and automations (Python scripts).

This folder already includes a ready-to-use `.obsidian` configuration (plugins, snippets, themes) plus collections of templates / CSS / scripts to speed up the creation of new vaults.

## Folder Structure

```
.obsidian  
│  
├── Plugins  
├── Themes  
├── Snippets  
└── Workspaces  

X  
│  
└── Additional collections, assets, and optional Dataview queries  

	Assets  
	│  
	├── Hotkeys  
	├── Dataview Collections  
	├── CSS Snippets  
	└── Other assets  
	
	Templates  
	│  
	├── Format — formatting structures and molds  
	└── Snippet — small reusable blocks  
	
	Bases  
	│  
	└── .base files used as starting points for notes and boards  
	
	Scripts  
	│  
	├── processamento_audio — audio transcription and processing  
	├── ferramentas_diversas — conversions and utilities (ipynb → md, EPUB, etc.)  
	└── organizacao_obsidian — scripts for vault manipulation  
```

## Common Issue Fixes

- Plugins not showing: move the `.obsidian` folder into the vault directory and restart Obsidian.
    
- CSS snippets not applying: Settings → Appearance → CSS snippets → enable the desired snippet.
    
- Templater not running: confirm the Templates folder path in the plugin settings.
    

## Key Files / Resources

- `.obsidian/` — configuration and installed plugins.
    
- `Templates/Format/_ base template.md` — base template for new notes.
    
- `Scripts/organizacao_obsidian/ChanGe-Templates-Folder.py` — script to reorganize templates (read before running).
    
- `Assets/Dataview/` — ready-to-use queries and dashboards for Dataview.
    
