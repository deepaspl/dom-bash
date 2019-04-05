# dom-bash
dom Theme for Bash

# README

In order for this theme to render correctly, you will need a
[Powerline-patched font](https://gist.github.com/1595572).
I recommend: https://github.com/powerline/fonts.git
```
git clone https://github.com/powerline/fonts.git fonts
cd fonts
sh install.sh
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
export THEME=$HOME/.bash/themes/dom-bash/dom.bash
if [[ -f $THEME ]]; then
    export DEFAULT_USER=`whoami`
    source $THEME
fi
```

Install powerline:

If you are running a Debian or Ubuntu based Linux distribution, there should
be a package available to install the Powerline Fonts with the following command:
```
	sudo apt-get install fonts-powerline
```

For fedora (tested on 28) or redhat based Linux distribution, there should also be a package available to install with the following command:
```
	sudo dnf install powerline-fonts
```

