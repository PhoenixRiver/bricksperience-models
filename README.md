# bricksperience-models

Models in ldr and Bricksperience format for importing or just plain copying into Bricksperience.

Only the Bricksperience .sav file is stored here since it is only a small binary and the screenshots are large ones that can be recreated by the user with the inbuilt BS editor if they want.

Check the last commit comment for whether the file is a good reproduction or if the .ldr had to be changed to accomodate missing bricks (see "missing_bricks.txt" for an ordered list of brick numbers that are missing from Bricksperience but available in LDraw).


NOTE: As per the author's request, bricks with images or stickers are swapped for their blank versions as Bricksperience has none of these due to the bloat it would cause for little benefit since most are only used for very few models.


Nota Bene: Some (.ldr) files are postpended with the string "-fake"; this means that the file used to create the BS file is this "-fake" file and I did this due to the differences with the official model being not subtle at all due ot missing pieces in BS. If these pieces are added to BS then use the (.ldr) file without the postpend to more easily recreate the original official model. Needless to say; there are no BS versions of the original filebut the one there can be replaced without changing the name should this issue be solved :)


PostScript: If anyone has contact with the author of the indiedb models I can add in the bs-format ones (though I don't have the ldr's they were created from, of course, so attribution would be hard to source?)


PostPostScript: Some bricks are in BS but have a different ID... in all cases I've found if the letter is removed from the ID (almost always "a") then the correct brick is used. The .ldr's here are inconsistent on this point but generally use the ID from LDraw and I feel that is better in case this oversight is changed to match... Stud.io has more recently started deprecating some IDs and defaulting to saving new IDs which makes creating .ldr's for BS (and LDraw) a triffle annoying... I have a list of IDs that cause problems which I'll upload once I've cleaned it up (there are a few false positives - the naming of bricks is a complete mess if you ask me though I'm sure there is a consistent ID system somewhere, it's just it isn't generally used... or even used by anyone outside of Lego!)