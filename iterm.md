Guide to my iTerm setup
========================
## Let's begin!
Install [oh-my-zsh] (http://ohmyz.sh/) and [iterm2] (https://www.iterm2.com/)

## Let's pimp it out some more!
Install [powerline9k] (https://github.com/bhilburn/powerlevel9k#option-2-install-for-oh-my-zsh) and a [nice font](https://github.com/powerline/fonts). 

Personally, I think Source Code Pro is the best font ever, but try them out!

## Setup oh-my-zsh (the boring part)
1. ```vim ~/.zshrc```

2. Insert at first line: ```export DEFAULT_USER=nameofcomputeraccount``` (e.g. ```export DEFAULT_USER=nate```)

3. After ZSH_THEME, add:
```
ZSH_THEME="powerlevel9k/powerlevel9k"
POWERLEVEL9K_LEFT_PROMPT_ELEMENTS=(context dir vcs)
POWERLEVEL9K_RIGHT_PROMPT_ELEMENTS=(status)
POWERLEVEL9K_SHORTEN_DIR_LENGTH=2
```

4 Make sure git is in the plugins section (and git-flow if you're using that). There's a ton more plugins if you so desire!
```plugins=(git git-flow)```

## Time to prettify iTerm!
1. Download either [Solarized Dark](https://raw.githubusercontent.com/altercation/solarized/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) or [Solarized Light](https://raw.githubusercontent.com/altercation/solarized/master/iterm2-colors-solarized/Solarized%20Light.itermcolors). Save anywhere. 

2. Open up iterm > preferences > profile > import (in a dropdown somewhere)

3. Choose the file you just saved.

4. Let's add the font you downloaded earlier: iterm > preferences > profiles > text. Add it as the regular font and as the non-ascii font. You'll probably want to adjust the font size as well. (I personally like 14px)

## Bonus: where to go from here...
- [Play with more coloring options!](http://iterm2colorschemes.com/)
- [Add more plugins to oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh/tree/master/plugins)
- [Add even more awesome icons to your terminal!](https://github.com/gabrielelana/awesome-terminal-fonts) They looks like [THIS!](https://github.com/bhilburn/powerlevel9k#symbols)
- [Customize powerlevel9k](https://github.com/bhilburn/powerlevel9k#segment-customization)
