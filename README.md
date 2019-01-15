# searchdeb
Python script to search for the most recent debian file of a package on a ppa.

The names of the packages to search for and the debian style source strings (like "deb foo.bar stable main") have to be
added to the automatically created `~/.searchdeb/repos.yaml`. The script will print the name, latest version number and link
to the `.deb` file of every package found in `repos.yaml`.

## Installation
Download the repo and run `./install.sh`

## Uninstall
Run `./remove.sh` on the local copy of the repo.

## Usage
Modify `~/.searchdeb/repos.yaml` to contain all the ppa packages you want to get the latest `.deb` file of.
Then, run `searchdeb` on the CLI. This will print the names, versions and download links of all packages to the command line.
