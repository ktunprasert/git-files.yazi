# git-files.yazi

> Basically [`vcs-files`](https://github.com/yazi-rs/plugins/tree/main/vcs-files.yazi) but with untracked using `git status`

Show Git file changes in Yazi.

## Installation

```sh
ya pkg add ktunprasert/git-files
```

## Usage

```toml
# keymap.toml
[[mgr.prepend_keymap]]
on   = [ "g", "c" ]
run  = "plugin git-files"
desc = "Show Git file changes"
```

## License

This plugin is MIT-licensed. For more information check the [LICENSE](LICENSE) file.
