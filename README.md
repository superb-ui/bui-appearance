<h1 align="center"><code>bui-appearance</code></h1>
<p align="center">BUI for widget toolkit (GTK)</p>
<p align="center"><img src="https://img.shields.io/github/license/NNBnh/bui-appearance?labelColor=073551&color=4EAA25&style=for-the-badge" alt="License: GPL-3.0"> <img src="https://img.shields.io/github/last-commit/NNBnh/bui-appearance?labelColor=073551&color=4EAA25&style=for-the-badge"></p>
<p align="center"><img src="https://img.shields.io/github/watchers/NNBnh/bui-appearance?labelColor=073551&color=4EAA25&style=flat-square"> <img src="https://img.shields.io/github/stars/NNBnh/bui-appearance?labelColor=073551&color=4EAA25&style=flat-square"> <img src="https://img.shields.io/github/forks/NNBnh/bui-appearance?labelColor=073551&color=4EAA25&style=flat-square"> <img src="https://img.shields.io/github/issues/NNBnh/bui-appearance?labelColor=073551&color=4EAA25&style=flat-square"></p>

## About
`bui-appearance` is an UI tool written in [`portable sh`](https://github.com/dylanaraps/pure-sh-bible) that change widget toolkit like [GTK](https://gtk.org) and [QT](https://www.qt.io) setting using [BUI environment variables](https://github.com/NNBnh/dots/wiki/bui).

## Contents
- [About](#about)
- [Contents](#contents)
- [Setup](#setup)
  - [Dependencies](#dependencies)
  - [Installation](#installation)
- [Usage](#usage)
- [Credit](#credit)

## Setup
### Dependencies
- `sh` to process

### Installation
#### Manually
- Option 1: using `curl`

```sh
curl https://raw.githubusercontent.com/NNBnh/bui-appearance/main/bui-appearance > ~/.local/bin/bui-appearance
chmod +x ~/.local/bin/bui-appearance
```

- Option 2: using `git`

```sh
git clone https://github.com/NNBnh/bui-appearance.git ~/.local/share/bui-appearance
ln -s ~/.local/share/bui-appearance/bui-appearance ~/.local/bin/bui-appearance
```

#### Package manager
For [`bpkg`](https://github.com/bpkg/bpkg) user:

```sh
bpkg install NNBnh/bui-appearance
```

For [Basher](https://github.com/bpkg/bpkg) user:

```sh
basher install NNBnh/bui-appearance
```

###### If you can and want to port BUI appearance to other package managers, feel free to do so.

## Usage
Run `bui-appearance` in the terminal:

```sh
bui-appearance
```

## Credit
Special thanks to:
- [**LXAppearance**](https://wiki.lxde.org/en/LXAppearance) by [The LXDE Team](https://www.lxde.org), This project inspired me to make this tool.

<br><br><br><br>

---

> <h1 align="center">Made with :heart: by <a href="https://github.com/NNBnh"><i>NNB</i></a></h1>
>
> <p align="center"><a href="https://www.buymeacoffee.com/nnbnh"><img src="https://img.shields.io/badge/buy_me_a_coffee%20-%23F7CA88.svg?logo=buy-me-a-coffee&logoColor=333333&style=for-the-badge" alt="Buy Me a Coffee"></p>
