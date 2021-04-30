# my-cheat-sheet-2021

### vim
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
- Shift + F10 : right click

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

### nvim-tree.lua
https://github.com/kyazdani42/nvim-tree.lua  
- C-n : toggle NvimTree
