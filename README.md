# .tmux.conf.local file backup

A backup repository I created to be able share my .tmux.conf.local.rep setup across machines while keeping track of any changes I made.

## Installation


### Dependencies
This tmux setup depends on the following packages:

- [Oh My Tmux custimization repository](https://github.com/gpakosz/.tmux).
- [powerline fonts](https://github.com/powerline/fonts).
- [tmux plugin manager](https://github.com/tmux-plugins/tpm).

### Installation instructions
If you installed the dependencies you can install my .tmux configuration by running the following commands in your terminal:

```
$ cd
$ git clone https://github.com/rickstaa/.tmux.conf.local_rep
$ ln -s -f .tmux.conf.local_rep/.tmux.conf.local
```

### Notes
If the symbolic link is colored red when you run the `ls -a` command you might need to use the `sudo ln -s -f .tmux.conf.local.rep/.tmux.conf.local` instead of `ln -s -f .tmux.conf.local.rep/.tmux.conf.local`.
