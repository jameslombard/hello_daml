# hello_daml

Project for getting to know DAML.

- https://docs.daml.com/getting-started/index.html
- https://docs.daml.com/cheat-sheet/

## Pre-requisites

- Install DAML SDK: `curl -sSL https://get.daml.com/ | sh`

Output:

``` sh
Determining latest SDK version...
Latest SDK version is 1.16.0
Downloading DAML SDK 1.16.0. This may take a while.
######################################################################## 100.0%
Extracting SDK release tarball.
Installing SDK release from directory.
Please add /home/james/.daml/bin to your PATH.
Bash completions installed for Daml assistant.
Zsh completions installed for Daml assistant.
To use them, add '~/.daml/zsh' to your $fpath, e.g. by adding the following
to the beginning of '~/.zshrc' before you call 'compinit':
fpath=(~/.daml/zsh $fpath)

Successfully installed DAML.
```

## Run App

- Create app: `daml new create-daml-app --template create-daml-app`
