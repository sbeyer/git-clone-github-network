# git-clone-github-network

Usage: `git-clone-github-network <username>/<repository> <clone-directory>`

A Ruby script that clones all forks of a repository on GitHub.
All forks are cloned into one repository.

Note that no local branches are constructed during forking.
Every forks' branch can be found using `<username>/<repository>/<branch>`
naming scheme.
You can use `git branch -va` or `gitk --all` to see all the branches.
Maybe the `git-analyze-cloned-github-network` script is also useful.

The scripts in this repository are released into the public domain.
There is no warranty for any damage that may occur by using them!
