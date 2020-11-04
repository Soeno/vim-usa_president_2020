# vim-usa-president-2020

Indicate USA President 2020 in Vim

![vim-usa-president-2020](https://raw.githubusercontent.com/mattn/vim-usa_president_2020/master/misc/screenshot.png)

## Usage

set `usa_president_2020#status()` into you `statusline` like below.

```vim
set statusline=%<%f\ %h%m%r%=%-14.(%l,%c%V%)\[%{usa_president_2020#status()}\]\ %P
```

## License

MIT

## Author

Yasuhiro Matsumoto (a.k.a. mattn)