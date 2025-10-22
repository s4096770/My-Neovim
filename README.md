# NeoVim
The config is split into 4 files, the root init.lua which calls lua/nvim/plugins.lua, lua/nvim/settings.lua and lua/nvim/keymaps.lua. The config is prioritised to be simple and readable.

I took inspiration from configs most recently like from Sylvan "Vimothee" Franklin aswell as initially learning alot about configuring nvim from kickstart.nvim and YouTubers like The Primagen.

Installation and setup
Important

Neovim <=v0.12 is required for this config to work, as the config uses the newly built in vim.pack. nvim v0.12 is currently only available in the nightly branch which i am using bob to switch to and from

To install the config, clone the repo to your config folder, typically ~/.config/nvim. Nvim will then prompt to install all plugins

git clone https://github.com/s4096770/nvim.git ~/.config/nvim && nvim
Linters, LSP's, DSP's and formatters
mason.nvim is used to install LSPs, linters etc and as such can be installed using :Mason, or to get help :help mason
