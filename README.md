REGOVAR
=======

This repository contains the source code of REGOVAR's official website: https://regovar.org/

## Install and configure git LFS to contribute to the Regovar website
We use git LFS for large file storage. Therefore, if you clone the repository to contribute to the Regovar website, it is necessary to install it.
### 1. Install git LFS

For Debian (10 and after) and Ubuntu (17.10 and after)
```sh
sudo apt install git-lfs
```

For ArchLinux and derivatives
```sh
sudo pacman -S git-lfs
```

### 2. Configure git to use LFS
```sh
git lfs install
```
## Add files to LFS
If you want to add big files in Regovar, you can add them to LFS
```sh
git lfs track 'path/file.extension'
```
