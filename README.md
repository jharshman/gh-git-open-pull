# gh-git-open-pull
A GitHub CLI Extension implementation of jehiah/git-open-pull

## Installation

Requirements:
* fzf (https://github.com/junegunn/fzf)
* Github CLI (duh)
* Git (also duh)

```
gh extension install jharshman/gh-git-open-pull
```

## Usage
gh git-open-pull

## Older Git Versions
The included patchfile will need to be applied if using older versions of `git` that do not have the `git branch --show-current` option.
```bash
$ patch -i 001-older-git-versions.patch
```
