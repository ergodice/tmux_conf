# Installation

Clone repository into config directory.

```bash
git clone git@github.com:ergodice/tmux_conf.git ~/.config/tmux/
```

Install tpm and load configration.

```bash
mkdir ~/.config/tmux/plugins/
git clone https://github.com/tmux-plugins/tpm ~/.config/tmux/plugins/tpm
tmux souce-file ~/.config/tmux/tmux.conf
```

# Usage

## Keymap

The prefix is assigned to `C-Space`.

| Key                    | Command                    |
| ---------------------- | -------------------------- |
| `[h, j, k, l]`         | split window on direction  |
| `C-[h, j, k, l]`       | move focus between windows |
| `C-Space [h, j, k, l]` | swap panes                 |
| `[`                    | enter copy mode            |
| `c`                    | create new window          |
| `n`                    | next window                |
| `p`                    | previous window            |
