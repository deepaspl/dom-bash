# dom-bash
dom Theme for Bash

# README

In order for this theme to render correctly, you will need a
[Powerline-patched font](https://gist.github.com/1595572).
I recommend: https://github.com/powerline/fonts.git
```
git clone https://github.com/powerline/fonts.git fonts
cd fonts
install.sh
```

Install:

I recommend the following:
```
cd $HOME
mkdir -p .bash/themes/dom-bash
git clone https://github.com/deeppanara/dom-bash.git .bash/themes/dom-bash
```

then add the following to your .bashrc:

```
export THEME=$HOME/.bash/themes/dom-bash/dom_bash.bash
if [[ -f $THEME ]]; then
    export DEFAULT_USER=`whoami`
    source $THEME
fi
```

# Goals

![ScreenShot](dom-bash-sshot.png)
