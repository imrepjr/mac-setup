# Mac preferences

I store some of my preferences related to setting up my Mac according to my own taste easily.

## Tools

- [iTerm2](https://iterm2.com/)
- [oh-my-zsh](https://ohmyz.sh/) with [powerlevel10k](https://github.com/romkatv/powerlevel10k#getting-started) theme

## Steps

1. [Optional] Download and install iTerm2.
2. Install `oh-my-zsh`.
3. Install `powerlevel10k` theme.
4. Download `.p10k.zsh` to `~/.p10k.zsh` from this repo or run `p10k configure` in the terminal
5. Import corresponding terminal preferences from here

## Installing Oh My Zsh

```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## Installing p10k for Oh My Zsh

1. Clone the repository:

```shell
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```

2. Set `ZSH_THEME="powerlevel10k/powerlevel10k"` in `~/.zshrc`.

## Setup p10k

Wizard options:

1. nerdfont-complete + powerline,
2. small icons,
3. ascii,
4. lean,
5. 24h time,
6. 1 line,
7. compact,
8. concise,
9. transient_prompt,
10. instant_prompt=verbose.

## Preferences

- .gitconfig
- iTerm2 profile
- Terminal profile
