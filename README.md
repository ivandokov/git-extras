# Git Extras

This repository contains several useful scripts for Git.
*I didn't wrote all the scripts. I found some of them online and did little modifications. The licenses for those are in the files.*

## git-large-files

Search for files larger than the requested.

```bash
./git-large-files 2
```
## git-remove-history

Permanently delete files/folders from your git repository.
To use it, cd to your repository's root and then run the script with a list of paths
you want to delete, e.g.

```bash
./git-delete-history path1 path2
```