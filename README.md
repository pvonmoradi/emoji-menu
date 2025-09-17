# ⚡ emoji-menu
A simple emoji-picker script, supporting both
[emoji](https://en.wikipedia.org/wiki/Emoji) 😊 and
[kaomoji](https://en.wikipedia.org/wiki/Kaomoji) (*^▽^*).

> [!TIP]
> Instead of this script, you can just use your OS's built-in emoji pickers: On
> GNOME/gtk, `Ctrl`+`;` or `Ctrl`+`.`. On KDE and Windows, `Win`+`.`
>
> Although, these usually don't come with a kaomoji, so  ʅ（‾◡◝）ʃ

## 📓 Usage
Run `emoji-menu sync` one time before usage so it downloads the database
files. dmenu is used for selection. The selected item is copied into X primary
clipboard (middle-mouse button to paste).

## 📦 Dependencies
- `curl jq notify-send xclip dmenu fonts-symbola`

## 💾 Databases
- emoji:   https://unpkg.com/emoji.json/emoji.json
- kaomoji: https://github.com/duckduckgo/zeroclickinfo-goodies/raw/master/share/goodie/cheat_sheets/json/kaomoji.json

# 👨‍💻 Development
- linter: `shellcheck`
- formatter: `shfmt -i 4 -bn -ci -sr`
