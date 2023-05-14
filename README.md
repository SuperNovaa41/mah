# M.A.H.
A minimal AUR helper.

Aims to provide an extremely simple way to automate simple AUR package installation.

## Installation
Use the `install.sh` script.
It will install mah to /usr/bin, you can change that by changing `$INSTALL_DIR`.

## Dependencies
Requires `git`.

## Usage
The default text editor can be changed by editing `$EDITOR`.

The default package install directory can be changed by editing `$DOWNLOAD_DIR`.

**Note**: $DOWNLOAD_DIR defaults to $HOME/downloads, and then to /tmp.
    


```
mah <package>           | Installs the given package.

mah -v -k <package>     | Installs the given package, with a far more verbose message output, 
                        | doesn't delete the installed package's folder upon completetion.

mah --version           | Prints the programs version information.

mah --help              | Prints a message detailing how to use the program.
```

## Troubleshooting
This program does not provide a method of package searching, it assumes you know the package you are searching for prior to usage.
If the script fails to work for specific packages, you may have to do it manually.
