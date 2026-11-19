## Dotfiles

blah

### Installation

```sh
rm -rf ~/dotfiles && git clone https://github.com/ayuxsys/dotfiles ~/dotfiles --depth=1
```

update `~/.gitconfig`

```ini
[include]
    path = ~/dotfiles/.gitconfig
```

update `~/.bashrc` (or `.zshrc`)

```sh
source ~/dotfiles/.shellrc
```

#### Prerequisites

- [fzf](https://github.com/junegunn/fzf)
- [bat](https://github.com/sharkdp/bat)
- [fd](https://github.com/sharkdp/fd)
- [yt-dlp](https://github.com/yt-dlp/yt-dlp)
- [ffmpeg](https://ffmpeg.org/download.html)
