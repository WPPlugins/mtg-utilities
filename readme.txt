=== MTG Utilities ===
Contributors: amuseum
Tags: mtg, magic the gathering, mana, card, autocard, deck
Requires at least: 3.8.1
Tested up to: 4.7
Stable tag: 2.0
Version: 2.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Basic utilities for Magic: the Gathering related websites. Use BBC code to display mana symbols, card links, and deck lists within posts and comments.

== Description ==

Basic utilities for Magic: the Gathering related websites. Use BBC code to display mana symbols, card links, and deck lists within posts and comments.

Usage:

* [mana]MANA COST[/mana]
* [card]CARD NAME[/card]
* [deck]DECK LIST[/deck]

For more detailed instructions and advanced options, visit http://www.shenafu.com/wp/mtg-utilities-overview/

== Installation ==

1. Copy files to /plugins/mtgutil
2. Configure URL to card database query, such as http://magiccards.info/query?q=!
3. Configure URL to card image query, such as http://gatherer.wizards.com/Handlers/Image.ashx?type=card&name=

== Screenshots ==

1. Mana symbols
2. Sample deck list with comments beside the cards
3. Full deck list

== Changelog ==

= 2.0 =

* prep plugin for submission to wordpress.org

= 1.4.2 =

* added 'image' toggle option to card tag : [card image=1]
* added colorless mana: c
* changed old chaos symbol to 'h'
* added energy counter (mana): e

= 1.3 =

* autocard_mtg.js updated to 1.58

= 1.2.1 =

* fixed decklists in comments
* added mana symbols: i(nfinite), c(haos), p(laneswalk), y, z
* changed old 'p' symbol to 2/p and p/2

= 1.2 =

* shortcode applied to comments (optional)

= 1.1 =

* autocard_mtg script to display card on mouseover

= 1.0 =

* card, deck, mana shortcodes
