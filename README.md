# swns
**SW**itch **N**etwork **S**ervices from the command line on Mac

![screen_recording](https://raw.githubusercontent.com/matoruru/imgs/master/swns/screen-recording.gif)

## Installation

```sh
$ curl -o ~/.local/bin/swns \
    --create-dirs https://raw.githubusercontent.com/matoruru/swns/main/swns

$ chmod +x ~/.local/bin/swns
```

### How to add `~/.local/bin` to your `$PATH`

*This section is necessary only when you couldn't find the executable `swns` by `type swns`.*

- **bash** (in `~/.bash_profile`):

    ```sh
    export PATH="$PATH:~/.local/bin"
    ```

- **fish** (in `.config/fish/config.fish`):

    ```
    set -x PATH ~/.local/bin $PATH
    ```

## Usage

```sh
$ swns
```
