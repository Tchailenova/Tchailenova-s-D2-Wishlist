# Tchailenova's D2 Wishlist
*Created for use with DIM's wishlist feature, each entry in this list has been calibrated to fulfill the maximum potential for each gun. This list contains weaponry regardless of game-type or intended usage scenario.*

-------------------
### Acknowledgements
- DIM for having this feature
- D2Foundry for letting me build custom rolls
- 48klocs for the multi-roll bloc-maker
- my friends who love theory-crafting like I do
  - Zanithar
  - Darms
  - Kinsmarck
  - The [WOLF] clan!

### Resources:
* https://d2foundry.gg/
* https://d2foundry.gg/w/weaponhash?p=0,0,0,0&m=0&mw=0
* https://48klocs.github.io/wish-list-magic-wand/fingerwave.html
* https://data.destinysets.com/
* https://raw.githubusercontent.com/Tchailenova/Tchailenova-s-D2-Wishlist/main/Tchailenova's%20D2%20Wishlist%20Content

# GUIDE
- comment-lines do not require escape characters
- notes (visible in *triage* panel of weapon in DIM) may be appended at the end of the wishlist hash-data.
	- in-line `#notes:`
- whitespace between hash-data and in-line notes will confuse the DIM wishlist reader and your notes will not be included
- the "notes" section will be input as-is, it will be ended before \nl with `|`
- \nl is the escape character for each entry
- Block Notes apply to a contiguous section of entries
	- block-note `//notes:`
	- a new block-note line or non-item line ends that contiguous entry-set
	- in-line notes will override the block-notes that might have applied to that entry
- entries do not require a certain number of perks to be treated as a wishlist item
	- in this way you can wishlist any iteration of a gun with "outlaw" on it, regardless of what else it does(n't) have
- WILDCARD for item: `-69420`
  - use this to wishlist any iteration of ANY item that matches the specified perks
- ItemCategoryHash may also be used in place of the wildcard or specific item-hash (IE: any MG with Target Lock and Fourth-Time's)
  - Hashes may be found using the Destiny Sets Data Explorer (contains items, item categories, perks, and more)
- If there are multiple perks for a given slot that you'd be happy to get, and further there are multiple slots where multiple perks would be nice, 48klocs built a little tool that will help you build out all of those permutations (see link above)
- To Trash-List an entry, prefix the item hash with `-` this will be searchable in DIM via `is:trashlist`
-------------------
### Organization of the wishlist::
(alphabetic within general sections; put the specific wish list versions at the top of the file and the generic versions at the bottom; the first roll DIM comes across that matches will be the one DIM applies.)

Godrolls at the top

Trash-items at the bottom
