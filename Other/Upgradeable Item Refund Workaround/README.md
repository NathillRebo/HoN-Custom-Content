To install the patch fully:
* Copy the content of "items" folder into the game's "items" folder.
* Copy the "buildings" content into the game's "buildings" folder.
* For each line in the "remove from entities_en.txt", remove the appriopriate line from the "entities_en" file in the stringtables folder.
* Add the content of "add to entities_en.txt" to the "entities_en" file in the stringtables folder. Added lines would be good somewhere between the entries for items, but must be above the "// End - do not delete this line" entry.

<<<<<<< Updated upstream
This patch will work for english language only - to make it compatible with other languages, repeat the third and fourth step for each language, then replace each added entry from english to appriopriate language.  
For example:  
Item_Nuke_IMPACT_effect&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Deals ^o350 Magic Damage^* to target.  
should look like:  
Item_Nuke_IMPACT_effect&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Verursacht beim Ziel ^o350 Magischen Schaden^*.  
=======
This patch will work for english language only - to make it compatible with other languages, repeat the third and fourth step for each language, then replace each added entry from english to appriopriate language.
For example:  
Item_Nuke_IMPACT_effect											Deals ^o350 Magic Damage^* to target.  
should look like:  
Item_Nuke_IMPACT_effect											Verursacht beim Ziel ^o350 Magischen Schaden^*.  
>>>>>>> Stashed changes
