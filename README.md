# Diskusage

Shows your diskusage in your zsh prompt.

```shell
# markus @ kari in ~ disk:27% [23:36:00] 
```

```shell
# markus @ kari in /tmp disk:46% [23:36:10] 
```

## Installation

1. `git clone https://github.com/mritzmann/zsh-diskusage.git ~/.oh-my-zsh/plugins/diskusage`
2. Add diskusage to your plugin array in your zshrc file: `plugins=( diskusage )`
3. Add `$(DISKUSAGE)` to your `PROMPT=`

There is also a Pull Request: [https://github.com/robbyrussell/oh-my-zsh/pull/7334](https://github.com/robbyrussell/oh-my-zsh/pull/7334)

## Dependencies

Df, sed, awk and tr. Testet on Debian Jessie and Stretch.

## FAQ

Q: Prompt only updates when zsh is first started  
A: https://github.com/olivierverdier/zsh-git-prompt/issues/55#issuecomment-77440662

Q: Which theme was used in the example?  
A: https://gist.github.com/mritzmann/85946d9ea5ca8bc2d07a7ab02947bead
