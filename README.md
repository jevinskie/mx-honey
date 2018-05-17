<p align="center">
  <img width="600" src="https://cdn.rawgit.com/mukel/mx-honey/demo/demo.svg">
</p>

This plugin provides completions for [mx](https://github.com/graalvm/mx); a command-line tool used for the development of Graal projects.
It's meant to improve the usual workflow `build unittest benchmark ...` ease discovery and provide handy aliases.

# Features 
  - [X] [mx aliases](./mx.plugin.zsh)
  - [X] mx global-options
  - [X] sub-command completion
  - [X] `mx benchmark` completions

# Manual install
```bash
git clone --depth 1 https://github.com/mukel/mx-honey.git ~/.oh-my-zsh/plugins/mx
```
Then add `mx` to your `~/.zshrc`:
```bash
plugins(git sudo archlinux mx)
```
