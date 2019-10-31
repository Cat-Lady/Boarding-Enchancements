# Boarding Enhancements

This plugin integrates boarding enhancements (doh!) into FOSS game "Endless Sky". It adds various human-space boarding related outfits, balanced around vanilla experience and fully integrated into game (purchase availability, usage by AI fleets, licenses required) - everything should perfectly fit into base game's feel. 

![BetterBoardingPirates](https://github.com/Cat-Lady/BetterBoardingPirates) is highly recommended to use in tandem.

![Boarding Enhancements Image](/boarding-enhancements/icon.png?raw=true "Boarding Enhancements Image")


## Features
- 8 new types of gear for your (and enemy) crew to use during boarding - ranging from Dirt Belt's hunting rifles and small sidearms, to full fledged Navy's Advanced Tactical Battle Suit.

- 2 ship's outfits that greatly increase battle readiness of crew stationed aboard vessel's sporting them.

- Full and seamless integration into rest of the game. Stuff is available for purchase in sensible places (if you meet the criteria - for more powerful ones), AI ships use it - progressively integrating more numerous and powerful outfits as certain in-game war event unfolds - and overall, strong gear is in possession of forces that you would expect them to do so (be sure to expect certain renegade warlords to be armed to teeth).

- For the first time in _**Endless Sky**_ - quasi-random distribution of boarding outfits on AI controlled ships. Even when meeting "same" or similarly constructed fleet, you can never be sure if you will encounter only token defense or full-fledged boarding regiment (especially on warships) - or, anything in between. 

**Hint:** As an effect, "Outfit Scanner" becomes much more useful thing to have. Knowing what you expect might now be a difference between choosing vulnerable targets and diving head-on into suicidal boarding attempt.

- As indirect effect, boarding military targets or well-defended merchant fleets is now much more challenging... But also, much more rewarding, if you are prepared and act wisely.

![Sidearm Image](/boarding-enhancements/images/outfit/sidearm.png?raw=true "Sidearm Image")


## Installing

Check:
https://github.com/Cat-Lady/Boarding-Enhancements/releases

...for latest, pre-packaged version.


**1.** Unpack ``boarding-enhancements`` to your ES plugins folder. Be sure that you have single ``boarding-enhancements`` directory inside your plugins folder, containing ``data`` and ``images`` folders. Directory structure should look like:

```(...)/plugins/boarding-enhancements/(.../data/, /images/ and other stuff)```


It **won't** work if the directory structure will be anything like:

```(...)/plugins/Boarding-Enhancements/boarding-enhancements/(...)```


**2.** Use files from ``vanilla-files-replace`` directory to replace files in your ES installation's ``/data/`` directory. Overwrite files when prompted.

Do **not** put ``vanilla-files-replace`` inside your ``/data/`` directory - it won't work like that. You need to directly replace approriate files with plugin's ones.

You can skip step **#2.**, but some variants of Marauder ships (that should be one of toughest nuts to crack while boarding) won't have new outfits. This step of replacing vanilla files is (hopefully) temporary workaround around limitation in ES plugin's framework - I'm already actively working with upstream to fix it, so there is a chance it won't be necessary in future (instructions and "Release" notes will higlight when that will become reality).

![Stun Grenades Image](/boarding-enhancements/images/outfit/stun%20grenades.png?raw=true "Stun Grenades Image")


## Author

* **Cat Lady**

*Initial work* - [TimButterworth](https://github.com/tmbutterworth/hand-to-hand-outfits)


## License

This project is licensed under the GPL3 License - see the [LICENSE.md](LICENSE.md) file for details


## Acknowledgments

"Endless Sky" Development Team and Michael Zahniser; For maintaining and creating the game

Lleyton, KIV King from "Endless Sky" Chat Community - for proofreading and error-correcting outfit's descriptions.

"Endless Sky" Chat Community - for patiently explaining how stuff works - without it, the outfits would be never integrated into AI's usage.

Timothy Butterworth; for the initial base of the plugin

Phil Morley, Rafael Ramawadh, kisspng.com - for base artwork.

![Battle Armor Image](/boarding-enhancements/images/outfit/flack%20vest.png?raw=true "Battle Armor Image")
