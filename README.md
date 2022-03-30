# fish-homebrew-apple-silicon

Fish shell integration for [Homebrew][1] users on Apple Silicon.

## Install

Assuming that you are using a fish shell plugin manager such as [Fisher][2]:

```
$ eval (/opt/homebrew/bin/brew shellenv)
$ # install fisher
$ fisher install dteoh/fish-homebrew-apple-silicon
```

... then start a new shell.

The initial `eval` is required so that the plugin manager can find `fish`.
Otherwise, installing this plugin will most likely fail.

[1]: https://brew.sh/
[2]: https://github.com/jorgebucaran/fisher
