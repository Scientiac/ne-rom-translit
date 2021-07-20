ne-roman-translit
===========

m17n input method for nepali similar to  Google transliteration and unicodenepali.com

Full documentation [here](https://thescientiac.blogspot.com/2021/07/ne-roman-translit-roman-transliterated.html)

## Feedback and reporting issues 
This layout is still in early stages of development. Use Issue Tracker for this project to report issues and send suggestions. 
 
## installation instructions for Ubuntu 
- install packages `ibus` and `ibus-m17n`
- download and extract `ne-roman-translit.zip` from [latest release](https://github.com/scientiac/ne-roman-translit/releases)
- go to `relese(extracted folder)/src/main/mim`
- copy `ne-roman-translit.mim` to `/usr/share/m17n` (installation dir of m17n) 
- to copy,type `sudo cp ne-roman-translit.mim /usr/share/m17n`
- copy `icons/ne-roman-translit.png` to `/usr/share/m17n/icons` 
- to copy, type `sudo cp icons/ne-roman-translit.png /usr/share/m17n/icons`
- restart ibus engine
- new layout roman-translit should be available under Nepali Language in IBus preferences

## installation instructions for Arch 
- install packages `ibus` and `ibus-m17n` type `sudo pacman -S ibus ibus-m17n`
- download and extract `ne-roman-translit.zip` from [latest release](https://github.com/scientiac/ne-roman-translit/releases)
- go to `relese(extracted folder)/src/main/mim`
- copy `ne-roman-translit.mim` to `/usr/share/m17n` (installation dir of m17n) 
- to copy, type `sudo cp ne-roman-translit.mim /usr/share/m17n`
- copy `icons/ne-roman-translit.png` to `/usr/share/m17n/icons` 
- to copy, type `sudo cp icons/ne-roman-translit.png /usr/share/m17n/icons`
- restart ibus engine
- new layout roman-translit should be available under Nepali Language in IBus preferences
