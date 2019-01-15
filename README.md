# need-some-git.bash
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![need-some-git.bash](https://img.shields.io/badge/need--some-git-ff69b4.svg?logo=github&logoColor=white)](https://github.com/need-some/need-some-git.bash)

_need-some_ is a collection of small yet useful functions.

The git package provides enhanced commands to use with git on the command line


## Syntax

### git all
Apply command to sub directories.
If in the current directory a .git exists, the command is applied to this directory, 
otherwise to all sub directories that contain a .git dir. 
Only direct child directories are checked, the directories are not searched recursively.

	git all pull

### git qstat
Get a quick status of the branch.