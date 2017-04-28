# Quick map changer

Tired of typing full map name to change it (`!map map\_name`)? Don't like
setting up aliases for maps (`!cm map\_shortcut`)?

I've got you covered! Quick map changer is what you're looking for.


## Usage

1. Just type in chat: `!qmc lkn`
2. ???
3. Profit, you are now playing on dm\_lockdown and you've saved 8 keystrokes!

Note: You might have to type more letters if you have a lot of maps with similar names.

...So you've noticed you'd save 9 keystrokes with `!cm ld`? Yep, that's true,
but if you have some (exotic?) map you don't have shortcut for in pms.cfg you'd
have to type the whole map name (or just set up a shortcut). If that suits you,
then just use `!cm`. (`!cm` is a command from Public Match Server Pack from
<http://hl2dm.net>)


## More info

* No configuration needed
* It's case sensitive
* Of course you need sourcemod installed on your server to use this plugin
* You can send PR with your translations
* I used this algorithm: <https://github.com/bevacqua/fuzzysearch>


## Installation

* Put scripts/qmc.sp into addons/sourcemod/scripts
* Put plugins/qmc.smx into addons/sourcemod/plugins (or compile it yourself :^)
* Put translations/qmc.phrases.txt into addons/sourcemods/translations
* Also put other qmc.phrases.txt files into their respective folders


## License

MIT
