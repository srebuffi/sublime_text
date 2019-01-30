# sublime_text

Keybindings:
	{"keys": ["ctrl+2"], "command": "insert_snippet", "args": {"name": "Packages/User/ipdb.sublime-snippet"}},
	{ "keys": ["f4"], "command": "expand_region" },
	{
	  "keys": ["super+u"],
	  "command": "expand_region",
	  "args": {"undo": true},
	  "context": [{ "key": "expand_region_soft_undo" }]
	},
	{
    "keys": [ "f1" ],
    "command": "run_macro_file",
    "args": { "file": "res://Packages/Macros/selectline.sublime-macro" },
},


Packages:
AlignTab
ExpandRegion
