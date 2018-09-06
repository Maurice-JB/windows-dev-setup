# Git Setup

## SSH Keys

Setting up SSH keys on computer and adding them to GitHub account
[https://help.github.com/articles/connecting-to-github-with-ssh](Connecting to GitHub with SSH)

## HTTPS Setup

If connecting via HTTPS (GitHub recommended), GitHub will request credentials for every request unless the following command is run:

```shell
git config --global credential.helper cache
```

Can be further customized with a timeout set (in seconds):

```shell
git config --global credential.helper "cache --timeout=28800"
```