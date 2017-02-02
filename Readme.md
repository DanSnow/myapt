myapt - apt without root
========================

myapt is a script that help you to install a software from apt without root permission.  
It install all the depencies under `$HOME/.local` and patch the exectuable file.  

## Usage ##

```sh
$ myapt init # Only need by the first time, it will set up environment
$ myapt install some-package
```

## Install ##

Just download the scripts and place in your PATH.  

## Commands ##

- init
  Usage: `myapt init`
  Set up environment for `myapt`
  Current only support `bash` and `zsh`
- install
  Usage: `myapt install <package-name>`
  Install package under `$HOME/.local`

## Depencies ##

- patchelf (But this can be install with `myapt` too)
