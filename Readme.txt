﻿   _      ___   __                _      _  __                          _     
  /_\    /___\ /__\  __ _  _ __  (_)  __| |/ _\  ___   __ _  _ __  ___ | |__  
 //_\\  //  /// \// / _` || '_ \ | | / _` |\ \  / _ \ / _` || '__|/ __|| '_ \ 
/  _  \/ \_/// _  \| (_| || |_) || || (_| |_\ \|  __/| (_| || |  | (__ | | | |
\_/ \_/\___/ \/ \_/ \__,_|| .__/ |_| \__,_|\__/ \___| \__,_||_|   \___||_| |_|

By Trypha

	Homepage: https://code.google.com/p/aorapidsearch/
	Download link: https://www.dropbox.com/s/shfp8fvws4jvx0m/AORapidSearch%20Beta.rar
	
Installation:
-------------
Unrar (use your favorite rar program, like WinRAR from rarlab.com) to any location on your drive.

Usage:
------
On execution, AORapidSearch (AORS) will load its item database, which may take a few seconds. The "Search" button will activate when loading finishes. Select your desired breed, profession, faction, level, expansions, and the skill you want to buff and hit Search.

AORS will generate results and populate whatever slots it finds an item for. The item with the highest buff will be automatically selected. To see what else is available, right click the slot and choose one of the other items, if there are more for that slot. Double clicking an item will launch one of the AO database web pages (AOItems.com by default) for that item.

You must be aware of certain provisos for this tool, and they reflect a cardinal rule:
- THIS TOOL DOES NOT REPLACE COMPREHENSIVE GAME KNOWLEDGE. IT MERELY SPEEDS UP SEARCHES AND KEEPS YOU FROM FORGETTING ABOUT CRITICAL ITEMS. -

1. Some items are unique, and only one such item can be equipped at a time. AORS will display that item in whatever slots it can be equipped in. It is left to you both to know which items are unique and to pick which slot is best for that item. 
2. Some items cannot be equipped by certain characters for reasons other than skill requirements. For example, some Zodiac loot will appear to be equippable by free characters, and items from the LoX expansion will appear equippable by level 200 characters, despite the fact that these characters can never enter the zones to loot those items. Again, it is left to you to know the game well enough to determine this.
3. A skill might in some cases be buffed more by trickle, but AORS will not calculate trickle. You will have to run separate searches for ability boosting items and determine which will work better for your needs. 
4. As of now, AORS does not search for perks, nanos, or org benefits. I may implement this in the future.

Advanced Features:
------------------
1. File->Update DB will update the database. The database and icon set included with this installation is generated from the 18.6.9 database. I have attempted to make the database upgrade procedure as smooth as possible, but I admit it is far from user-friendly at this point. You will need a working, updated installation of Anarchy Online Item Assistant and AOSkills3 (links in Acknowledgements). Perform the steps in order, and read carefully.
2. Options: These should be mostly self-explanatory. The Custom DB site option is provided in case someone creates a new database site in the future. Load the page for an item, copy the URL minus the AOID into the box.
3. Advanced->Excluded Items: if you get frustrated by items showing up that you know to be not ingame, or items that you will never acquire, you can add them to a list by AOID and they will be excluded from searches. If you change your mind, you can remove them from the list. You can also import a comma-separated-value list (a plain text file of AOIDs separated by commas, no spaces or newlines) to save time.
4. Advanced->Custom Skills: You should never need this option unless Funcom changes the game drastically. It is provided merely for the sake of extra future-proofing flexibility.

Known Issues:
-------------
1. Some items have conditional stats, such as Maria's Fashion items, which only work when certain conditions are met, and AORS does not detect this yet. For example, the Yellow Tank Top of Sirillion buffs Complit for Bureaucrats only, but will show up in AORS for all professions.

Awaiting bug reports from testers.
For bug reports, PM Trypha on the official forums.

Acknowledgements:
-----------------
Program icon borrowed from Docaholic (http://forums.anarchy-online.com/showpost.php?p=6053472&postcount=10).
Concept, GUI design and some code borrowed from Zacix's AOTwinker (http://aotwinker.codeplex.com/, now abandoned).
Icons extracted with Darkbane's ExtractIcons tool, bundled with AOSkills3 (http://www.lastmanut.pwp.blueyonder.co.uk/AOSkills3CP2WebPage/aoskills3.html).
SQL database provided by Morten Fjeldstad's Anarchy Online Item Assistant Plus (http://sourceforge.net/projects/aoiaplus/).