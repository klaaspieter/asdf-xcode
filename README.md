# asdf-xcode

Xcode plugin for [asdf] version manager

⚠️ Work in progress. This supports downloading and installing Xcodes but not setting their version using `.tool-versions`. See [#2] for more information. In the meantime I suggest using [xcodes] combined with [chxcode].

## Install

Install [xcodes] if necessary:

```sh
brew install robotsandpencils/made/xcodes
```

Add asdf-xcode to asdf:

```sh
asdf plugin-add xcode https://github.com/klaaspieter/asdf-xcode.git
```

## Use

See [asdf documentation] for instructions on how to install and manage Xcode versions. Make sure to look at [`.tool-versions`] to configure an Xcode version per project/directory.

[asdf]: https://github.com/asdf-vm/asdf
[asdf documentation]: https://asdf-vm.com/#/core-manage-versions
[`.tool-versions`]: https://asdf-vm.com/#/core-configuration?id=tool-versions
[xcodes]: https://github.com/RobotsAndPencils/xcodes
[#2]: https://github.com/klaaspieter/asdf-xcode/issues/2
[chxcode]: https://github.com/klaaspieter/chxcode
