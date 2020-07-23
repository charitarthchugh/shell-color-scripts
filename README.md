
# Shell Color Scripts

![Screenshot of shell-color-scripts](https://gitlab.com/dwt1/dotfiles/raw/master/.screenshots/dotfiles12.png)

Fork of Derek Taylor(DistroTube)'s colorscripts on [Gitlab](https://gitlab.com/dwt1/shell-color-scripts)
Included 45+ beautiful terminal color scripts.

| I have removed his PACKAGEBUILD, but theoretically that should work.(cannot test, not on Arch)

# Usage

    colorscript --help
    Description: A collection of terminal color scripts.

    Usage: colorscript [OPTION] [SCRIPT NAME/INDEX]
      -h, --help, help    	Print this help.
      -l, --list, list    	List all color scripts.
      -r, --random, random	Run a random color script.
      -e, --exec, exec    	Run a spesific color script by SCRIPT NAME or INDEX.

For even more fun, add the following line to your .bashrc or .zshrc and you will run a random color script each time you open a terminal:

	### RANDOM COLOR SCRIPT ###
	colorscript random
