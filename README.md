# bricksperience-models

Models in ldr and Bricksperience format for importing or just plain copying into Bricksperience.

Only the Bricksperience .sav file is stored here since it is only a small binary and the screenshots are large ones that can be recreated by the user with the inbuilt editor if they want.

Check the last commit comment for whether the file is a perfect reproduction or if the ldr had to be changed to accomodate missing bricks (see "missing_bricks.txt" for an ordered list of brick numbers that are missing from Bricksperience but available in Stud.io / LDraw).


NOTE: As per the author's request, all models have their minifigs (and held objects) removed from ldr files and bricks with images or stickers are swapped for their blank versions as Bricksperience has none of these due to the bloat it would cause for little benefit since most are only used for very few models.


PostScript: If anyone has contact with the author of the indiedb models I can add in the bs-format ones (though I don't have the ldr's they were created from, of course, so attribution would be hard to source?)


PostPostScript: Some bricks are in BS but have a different ID... in all cases I've found if the letter is removed from the ID (almost always "a") then the correct brick is used. The .ldr's here are inconsistent on this point but generally use the ID from LDraw and I feel that is better in case this oversight is changed to match... Stud.io has more recently started deprecating some IDs and defaulting to saving new IDs which makes creating .ldr's for BS a triffle annoying... I have a list of IDs that cause problems which I'll upload once I've cleaned it up (there are a few false positives - the naming of bricks is a complete mess if you ask me though I'm sure there is a consistent ID system somewhere, it's just it isn't generally used...)


PostPostPostScript: BS_palette is for Stud.io, place it into your user's AppData/Local/Stud.io/Buckets/Folders directory and then click the "Main" dropdown list above the list of bricks to select it, it currently contains every brick in BS so that you can design things in Stud.io and then import them into BS without having to worry whether the piece exists or not in BS. (Please report any mistakes as some of the number IDs between Stud.io and BS are known to be mismatched or changed due to time and whyever people keep changing these things even when the part remains the same!) - I should note that I'm not confident that Stud.io upgrades don't mess up this file... if you have problems trying replacing it with a clean copy as I occassionally find bricks missing from the list that were there before.