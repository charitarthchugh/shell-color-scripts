# Shell Color Scripts

![Screenshot of shell-color-scripts](https://gitlab.com/dwt1/dotfiles/raw/master/.screenshots/dotfiles12.png)

Fork of Derek Taylor (DistroTube)'s colorscripts on [Gitlab](https://gitlab.com/dwt1/shell-color-scripts)
Included are 50+ beautiful terminal color scripts.

> I have removed his PACKAGEBUILD, but theoretically that should work (cannot test, not on Arch Linux).
> 
> I have also removed some of the colorscripts that he included to my personal liking and added new ones. 

# Dependencies

- sh

- lolcat(for pacman-large variations)
  
# Usage  
    
  ```sh  
   Usage: colorscript [OPTION] [SCRIPT NAME/INDEX] 
   -h, --help, help        Print this help.  
   -l, --list, list        List all color scripts.  
   -r, --random, random    Run a random color script.  
   -e, --exec, exec        Run a spesific color script by SCRIPT NAME or INDEX.  
  ```    
For even more fun, add the following line to your .bashrc or .zshrc and you will run a random color script each time you open a terminal:  
```
### RANDOM COLOR SCRIPT ###
colorscript random
```  
# Credits

This is essentially a compilation of other people's work, so here are some credits:

* [Derek Taylor](https://gitlab.com/dwt1/shell-color-scripts)

* [joshdk/hedgehogs](https://github.com/joshdk/hedgehogs)
