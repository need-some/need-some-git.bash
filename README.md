# need-some-git.bash
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version: 0.0.1](https://img.shields.io/badge/version-0.0.1-yellowgreen)](0.0.1)
[![need-some-git.bash](https://img.shields.io/badge/need--some-git-ff69b4.svg?logo=github&logoColor=white)](https://github.com/need-some/need-some-git.bash)

_need-some_ is a collection of small yet useful functions.

The git package provides enhanced commands to use with git on the command line

## Installation
See the Installation in [need-some-init.bash](https://github.com/need-some/need-some-init.bash "need-some-init.bash")

## Syntax

### git all
Apply command to sub directories.
If in the current directory a .git exists, the command is applied to this directory, 
otherwise to all sub directories that contain a .git dir. 
Only direct child directories are checked, the directories are not searched recursively.

	git all pull

### git qstat
Get a quick status of the branch.

