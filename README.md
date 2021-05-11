# my-cheat-sheet-2021

### vim
https://devhints.io/vim
- ci" : change inside " (" can be '{[ etc...)
- ca" : change outside " (" can be '{[ etc...)
- C-w : split pane
- C-O / C-I : jumping to and from previously visited locations
- :m-2 / :m+ : move line up / down
- . : repeat last change made in normal mode
- @: : repeat last command
- :noh : clear highlights
- "+y : copy to clipboard
- "+p : paste from clipboard

- Copy a word to multiple locations  
  Copy a line to multiple locations  
  https://vim.fandom.com/wiki/Repeat_last_change
  
### vim plugins
- vim-surround
https://github.com/tpope/vim-surround/blob/master/doc/surround.txt

### alacritty
- C-l : clear
- Command + N : new instance

### hammerspoon
- hs.hotkey.bind({"cmd", "ctrl"}, "I", alacritty_move_focus)

### tmux + alacritty
- Shift + Click : open url

### tmux
https://devhints.io/tmux
- prefix -> x : kill pane
- prefix -> v : horizontal split
- prefix -> V : vertical split
- prefix -> j/k/h/l : select pane
- prefix -> J/K/H/L : resize pane
- prefix -> c : new window
- prefix -> n : next window
- prefix -> prefix : toggle last window
- C-Shift + Left/Right : move current window
- prefix -> r : reload
- prefix -> [ : enter copy mode
- (in copy mode) v : begin selection
- (in copy mode) y : copy selection and cancel

### VS Code
https://www.git-tower.com/learn/cheat-sheets/vscode/
- Shift + F10 : right click
- Ctrl + Enter(File Explorer) : Open in second editor
- Command + Enter(Quick Open) : Open in second editor

### zsh-autocomplete
- https://github.com/marlonrichert/zsh-autocomplete

### tmux plugins

#### tpm
https://github.com/tmux-plugins/tpm  
- prefix -> I : install plugins


#### tmux-sessionist
https://github.com/tmux-plugins/tmux-sessionist  
- prefix -> @ : promote current pane into a new session

#### tmux-copycat
https://github.com/tmux-plugins/tmux-copycat  
- prefix -> C-u : url search

#### tmuxinator
-

#### tmux-resurrect
https://github.com/tmux-plugins/tmux-resurrect  
- prefix -> C-s : save tmux environment
- prefix -> C-r : restore tmux environment

#### nvim-tree.lua
https://github.com/kyazdani42/nvim-tree.lua  
- C-n : toggle NvimTree

#### vim-smoothie
https://github.com/psliwka/vim-smoothie  
- let g:smoothie_experimental_mappings=0

#### nvim-treesitter
https://github.com/nvim-treesitter/nvim-treesitter

#### dashboard-nvim
https://github.com/glepnir/dashboard-nvim

### Markdown / GitHub Flavored Markdown
https://devhints.io/markdown
- [Markdown Guide](https://www.markdownguide.org)
- [Writing on GitHub](https://docs.github.com/en/github/writing-on-github)
- \[title](https://www.example.com) : Link
- \![alt text](image.jpg) : Image
- \`code` : Code
- \``` fenced ``` : Fenced Code Block

### vim-easy-align
https://github.com/junegunn/vim-easy-align  
- vipga*| : Align all around |

### Readline
- https://readline.kablamo.org/emacs.html
- https://readline.kablamo.org/vi.html

### less
- https://gist.github.com/glnds/8862214

### Mac Keyboard Shortcuts
- https://support.apple.com/en-us/HT201236
- https://devhints.io/vscode

### Makefile
- https://devhints.io/makefile

### bash scripting
- https://devhints.io/bash

### zsh scripting
- https://devhints.io/zsh

### vimscript
- https://devhints.io/vimscript
- https://devhints.io/vimscript-functions
- https://devhints.io/vimscript-snippets

### Lua
- https://devhints.io/lua
