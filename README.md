# nvim_setup_2

### Structure of this Repo
.
├── after
│   └── plugin                      # Specifications and configurations to the single plugins. New keybinds and further customizations
│       ├── copilot.lua
│       ├── harpoon.lua
│       ├── lsp.lua
│       ├── nvimtree.lua
│       ├── telescope.lua
│       └── treesitter.lua
├── init.lua                        # entry point for the setup, define the theme and the other config files it should look into
├── lua
│   ├── init.lua                    # basic nvim/vim configurations 
│   ├── plugins.lua                 # all installed plugins, including the plugin manager are defined here. Use the 'PackerSync' to install new plugins 
│   └── remap.lua                   # remaps for commands that are basic vim commands
└── plugin
    └── packer_compiled.lua         # compiled by the system. Dont touch
