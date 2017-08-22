# Knowledge of X Window System
## Environment Variable
### Display Manager's resource file
`~/.Xresources`
### xinit's resource file
`~/.xinitrc`
`[[ -f ~/.Xresources ]] && xrdb -merge -I$HOME ~/.Xresources`

## unclutter
remove mouse pointer

## Xresources
preference
`name.Class.resource: valueA: valueB:...`
load
`xrdb -merge ~/.Xresources`

## urxvt
`urxvtd` →daemon load
`urxvtc` →open client
### powerlineのシンボルが豆腐になる問題
fontsizeとlettersizeの組み合わせが良くないと出る・・・
というより成功した例が11と2の組み合わせでとてもじゃないがまともに使えない


