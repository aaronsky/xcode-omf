![][license-badge]

<div align="center">
  <a href="http://github.com/oh-my-fish/oh-my-fish">
  <img width=90px  src="https://cloud.githubusercontent.com/assets/8317250/8510172/f006f0a4-230f-11e5-98b6-5c2e3c87088f.png">
  </a>
</div>
<br>


# xcode-omf

A plugin for Oh My Fish that provides some handy Xcode utilities. Ports some helpers from the [Oh My Zsh][oh-my-zsh] [xcode plugin][omz-xcode-plugin], and provides some new ones of its own.

## Install

```fish
$ omf install xcode
```

## Usage

### xc

Opens the first xcworkspace/xcodeproj matched in the specified directory. You can pass a directory if you'd like, otherwise it defaults to the current working directory. Returns 1 if it fails to find anything.

```fish
$ xc
```

# License

[MIT][mit] © [aaronsky][author] et [al][contributors]

[oh-my-zsh]:         https://github.com/robbyrussell/oh-my-zsh
[omz-xcode-plugin]: https://github.com/robbyrussell/oh-my-zsh/blob/master/plugins/xcode/xcode.plugin.zsh

[mit]:             http://opensource.org/licenses/MIT
[author]:          https://github.com/aaronsky
[contributors]:    https://github.com/aaronsky/xcode-omf/graphs/contributors
[omf-link]:        https://www.github.com/oh-my-fish/oh-my-fish

[license-badge]:   https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square