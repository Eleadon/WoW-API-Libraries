# WoW-API-Libraries
This is my own personal collection of spreadsheets that provides reference information for anyone developing World of Warcraft related add-ons or websites.

<b><a href="https://github.com/Eleadon/WoW-API-Libraries/blob/master/battlepets.xlsx?raw=true">battlepets.xlsx</a></b><br>
This spreadsheet contains detailed information on every battle pet in the game. For my own internal record keeping I've assigned each pet a unique identifying number (similar to an item id) that would not conflict with any existing item ids. These id's are not used by Blizzard or Wowhead in any way, only by me. For each pet it includes the following pieces of information:<br>
`id, pet name, zone, coords, speciesid, creatureid, typeAbilityId, petType, strongAgainst, weakAgainst, summonedBy, breeds, rarities, cageable, patch, canBattle, icon, description, source, abilities`<br>

<b><a href="https://github.com/Eleadon/WoW-API-Libraries/blob/master/item_api_cache.7z?raw=true">item_api_cache.7z</a></b><br>
This is a 7zip file containing all of Blizzard's Item API JSONs and all of Wowhead's Item API XMLs for all items in the game (as of patch 6.2.2). It includes info from both APIs because sometimes Blizzard is missing data that Wowhead has and sometimes Wowhead is missing data that Blizzard has. Downloading this one file is the equivalent of downloading 100,000 individual JSON files from Blizzard and 100,000 individual XML files from Wowhead. Because some file systems might choke when there are too many files in a folder I've separated all the files into groups of 1,000 items per folder. All battle pet JSONs are also included.<br>

<b><a href="https://github.com/Eleadon/WoW-API-Libraries/blob/master/items.craftable.xlsx?raw=true">items.craftable.xlsx</a></b><br>
This spreadsheet contains details on every craftable, auctionable item in the game. It is meant to be used by AH applications that are trying to calculate what it costs to craft an item. For each item it includes the following pieces of information:<br>
`item id, item name, created by spell, required mats`<br>

<b><a href="https://github.com/Eleadon/WoW-API-Libraries/blob/master/items.disenchantable.xlsx?raw=true">items.disenchantable.xlsx</a></b><br>
This spreadsheet contains all disenchantable BOEs in the game and what they disenchant into. It is meant to be used by AH applications that are trying to calculate what items are profitable to disenchant. These numbers are not official numbers from Blizzard, they are simply "best estimates" calculated from Wowhead and player submissions.<br>

<b><a href="https://github.com/Eleadon/WoW-API-Libraries/blob/master/items.millable.xlsx?raw=true">items.millable.xlsx</a></b><br>
This spreadsheet contains all millable items in the game and what they mill into. It is meant to be used by AH applications that are trying to calculate what items are profitable to mill.<br>

<b><a href="https://github.com/Eleadon/WoW-API-Libraries/blob/master/items.prospectable.xlsx?raw=true">items.prospectable.xlsx</a></b><br>
This spreadsheet contains all prospectable items in the game and what they prospect into. It is meant to be used by AH applications that are trying to calculate what items are profitable to prospect.<br>

<b><a href="https://github.com/Eleadon/WoW-API-Libraries/blob/master/items.xlsx?raw=true">items.xlsx</a></b><br>
This spreadsheet contains detailed information on every item in the game. It includes all of the info from Blizzard's Item API merged with all of the info from Wowhead's Item API plus a ton of manual additions. Includes the following pieces of information about each item:<br>
`ItemID, ItemName, InBlizzardAPI, InWowheadAPI, isAuctionable, inSnatchList, GlobalMedianUS, GlobalMedianEU, icon, itemLevel, quality, patch, alchemy, archaeology, blacksmithing, cooking, disenchanting, enchanting, engineering, firstaid, herbalism, inscription, jewelcrafting, leatherworking, milling, mining, prospecting, skinning, tailoring, disenchantingSkillRank, description, stackable, itemBind, bonusStats, itemSpells, buyPrice, sellPrice, itemClass, itemSubClass, itemType, inventoryType, equippable, transmoggable, itemset, containerSlots, weaponInfo, maxCount, maxDurability, minFactionId, minReputation, side, requiredSkill, requiredLevel, requiredSkillRank, createdBy, source, sourceId, sourceType, sourceDesc, deprecatedMsg, baseArmor, hasSockets, armor, displayInfoId, nameDescription, nameDescriptionColor, upgradable, heroicTooltip, bonusLists, context, defaultBonusLists, chanceBonusLists, bonusChances`<br>

Custom fields (that are not from Blizzard or Wowhead):<br>
`InBlizzardAPI` - This is set to 1 for items that exist in Blizzard's Item API<br>
`InWowheadAPI` - This is set to 1 for items that exist in Wowhead's Item API<br>
`inSnatchList` - This is set to 1 for items that are in my own personal snatch list (these are rare, hard-to-acquire items)<br>
`patch` - The patch the item was added into the game<br>
`GlobalMedianUS` - The Global Median Price of the item (in copper) for all US realms (from Wowuction)<br>
`GlobalMedianEU` - The Global Median Price of the item (in copper) for all EU realms (from Wowuction)<br>
`profession_name` - If the item is crafted by a profession this field contains the skill level required to craft it<br>
`itemType` - This field describes what type of item it is such as "Cloth Legs" or "Leather Waist".<br>
`transmoggable` - This is set to 1 for items that can be used as a source for transmog<br>
`sourceDesc` - This is a custom field that describes the source of the item (if known)<br>

<b><a href="https://github.com/Eleadon/WoW-API-Libraries/blob/master/realms.cn.xlsx?raw=true">realms.cn.xlsx</a></b><br>
This spreadsheet contains a list of all Chinese realms and details about each one.<br>

<b><a href="https://github.com/Eleadon/WoW-API-Libraries/blob/master/realms.eu.xlsx?raw=true">realms.eu.xlsx</a></b><br>
This spreadsheet contains a list of all European realms and details about each one.<br>

<b><a href="https://github.com/Eleadon/WoW-API-Libraries/blob/master/realms.kr.xlsx?raw=true">realms.kr.xlsx</a></b><br>
This spreadsheet contains a list of all Korean realms and details about each one.<br>

<b><a href="https://github.com/Eleadon/WoW-API-Libraries/blob/master/realms.tw.xlsx?raw=true">realms.tw.xlsx</a></b><br>
This spreadsheet contains a list of all Taiwanese realms and details about each one.<br>

<b><a href="https://github.com/Eleadon/WoW-API-Libraries/blob/master/realms.us.xlsx?raw=true">realms.us.xlsx</a></b><br>
This spreadsheet contains a list of all US realms and details about each one.<br>

<b><a href="https://github.com/Eleadon/WoW-API-Libraries/blob/master/ref.breedids.xlsx?raw=true">ref.breedids.xlsx</a></b><br>
This is a reference lookup table for battle pet breed ids.<br>

<b><a href="https://github.com/Eleadon/WoW-API-Libraries/blob/master/ref.inventorytypes.xlsx?raw=true">ref.inventorytypes.xlsx</a></b><br>
This is a reference lookup table for inventory types.<br>

<b><a href="https://github.com/Eleadon/WoW-API-Libraries/blob/master/ref.itemclasses.xlsx?raw=true">ref.itemclasses.xlsx</a></b><br>
This is a reference lookup table for item classes and sublasses.<br>

<b><a href="https://github.com/Eleadon/WoW-API-Libraries/blob/master/ref.playerclasses.xlsx?raw=true">ref.playerclasses.xlsx</a></b><br>
This is a reference lookup table for player classes.<br>

<b><a href="https://github.com/Eleadon/WoW-API-Libraries/blob/master/ref.qualities.xlsx?raw=true">ref.qualities.xlsx</a></b><br>
This is a reference lookup table for item qualities.<br>

<b><a href="https://github.com/Eleadon/WoW-API-Libraries/blob/master/ref.randomenchants.xlsx?raw=true">ref.randomenchants.xlsx</a></b><br>
This is a reference lookup table for random enchants.<br>

<b><a href="https://github.com/Eleadon/WoW-API-Libraries/blob/master/ref.skilllines.xlsx?raw=true">ref.skilllines.xlsx</a></b><br>
This is a reference lookup table for skill lines.<br>

<b><a href="https://github.com/Eleadon/WoW-API-Libraries/blob/master/ref.stattypes.xlsx?raw=true">ref.stattypes.xlsx</a></b><br>
This is a reference lookup table for stat types.<br>

<b><a href="https://github.com/Eleadon/WoW-API-Libraries/blob/master/spells.xlsx?raw=true">spells.xlsx</a></b><br>
This spreadsheet contains details on every spell in the game that yields an item. This includes all items crafted by all professions. Includes the following pieces of information about each spell:<br>
`spell id, spell name, spell icon, associated profession, profession level, red difficulty, yellow difficulty, green difficulty, grey difficultly, yielded item, required mats`<br>

<b><a href="https://github.com/Eleadon/WoW-API-Libraries/blob/master/tooltips.xlsx?raw=true">tooltips.xlsx</a></b><br>
This spreadsheet contains html tooltips for every item, item spell, and battle pet in the game. It was placed in a separate file because it's rather large and only meant to be used for offline testing and debugging. A developer could just as easily use <a href="http://www.wowhead.com/tooltips">Wowhead's live tooltips</a> instead.<br>
