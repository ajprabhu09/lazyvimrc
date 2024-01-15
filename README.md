# 💤 LazyVim

A starter template for [LazyVim](https://github.com/LazyVim/LazyVim).
Refer to the [documentation](https://lazyvim.github.io/installation) to get started.





# Custom Dependencies that need to be installed:


[ ] Vim-Fugitive
[X] LazyGit
    - This uses depends on installing `https://github.com/jesseduffield/lazygit`
  
[X] RipGrep - fast grepping
    - `https://github.com/BurntSushi/ripgrep`
[X] FD
    - for finding files `https://github.com/sharkdp/fd`

[X] Semshi for python
    - better syntax highlighting 
    - `https://github.com/numirias/Semshi`

# Shell

[X] Oh-My-Zsh `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
[X] Terminal Colors 
```
NEWLINE=$'\n'
DISABLE_UNTRACKED_FILES_DIRTY="true"
DIVIDER=$'------------$NEWLINE'
PROMPT="%{$fg_bold[white]%}%n %{$fg[blue]%}@ %{$fg_bold[yellow]%}%m"
PROMPT+=' %{$fg[cyan]%}%d'
PROMPT+=' $(git_prompt_info)'
PROMPT+=" $NEWLINE%(?:%{$fg_bold[green]%}➜ :%{$fg_bold[red]%}➜ ) %{$reset_color%}"
```


# Copying to system clipboard

- looking at `lua/config/options.lua` `vim.o.clipboard="unamedplus"` yanks directly to clipboard
- disable this if this is not wanted


# TODO

[] Need to create a ansible playbook to automate installing the above crap

