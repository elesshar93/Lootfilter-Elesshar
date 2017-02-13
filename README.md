# Lootfilter-Elesshar
Show
	Class "Divination"
	BaseType "The Wolf's Shadow"
	SetFontSize 38
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 Cosmetic: Black Text
	SetBorderColor 0 100 150 255         # BORDERCOLOR:	 Cosmetic: T4 Divination
	SetBackgroundColor 145 215 230 225   # BACKGROUND:	 T4 Divination
	PlayAlertSound 2 300                 # DROPSOUND:	 Value Drop: Currency, fragments

#------------------------------------
#   [1202] T1 - Top tier cards
#------------------------------------

Show
	Class "Divination"
	BaseType "The Doctor" "The Fiend" "House of Mirrors" "Hunter's Reward" "Abandoned Wealth" "The Artist" "Bowyer's Dream" "The Brittle Emperor" "The Celestial Justicar" "The Dapper Prodigy" "The Dark Mage" "The Devastator" "The Dragon's Heart" "The Ethereal" "The Formless Sea" "Heterochromia" "The Hunger" "The Immortal" "The Last One Standing" "The Offering" "The Queen" "The Thaumaturgist" "Wealth and Power" "The Enlightened"
	SetFontSize 45
	SetTextColor 0 0 255 255             # TEXTCOLOR:	 Cosmetic: T1 Divination card
	SetBorderColor 0 0 255 255           # BORDERCOLOR:	 Cosmetic: T1 and T2 Divination
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T1 Global High Value Drop
	PlayAlertSound 6 300                 # DROPSOUND:	 T1 Drop

#------------------------------------
#   [1203] T2 - Great cards
#------------------------------------

Show
	Class "Divination"
	BaseType "The Cartographer" "The Chains that Bind" "Chaotic Disposition" "Emperor of Purity" "The Harvester" "The Hoarder" "The King's Heart" "Last Hope" "Mawr Blaidd" "The Penitent" "Pride Before the Fall" "The Scavenger" "The Sephirot" "The Valkyrie" "The Vast" "The Warlord" "The Wolf" "Stormcaller" "Earth Drinker" "The Surveyor" "The Void"
	SetFontSize 44
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 Cosmetic: Black Text
	SetBorderColor 255 255 0 255         # BORDERCOLOR:	 Crafting: T1
	SetBackgroundColor 100 250 250 245   # BACKGROUND:	 T2 Divination
	PlayAlertSound 2 300                 # DROPSOUND:	 Value Drop: Currency, fragments

#------------------------------------
#   [1204] T3 - Decent cards
#------------------------------------

Show
	Class "Divination"
	BaseType "The Aesthete" "The Arena Champion" "The Avenger" "Blind Venture" "The Body" "Boundless Realms" "The Calling" "Coveted Possession" "The Cursed King" "The Encroaching Darkness" "The Fletcher" "Gemcutter's Promise" "The Gladiator" "Glimmer of Hope" "Grave Knowledge" "Hope" "Humility" "The Inventor" "Jack in the Box" "The Jester" "Lost Worlds" "Lucky Connections" "Lysah's Respite" "Merciless Armament" "Rats" "The Risk" "The Road to Power" "Scholar of the Seas" "The Soul" "The Spoiled Prince" "The Survivalist" "Time-Lost Relic" "Tranquillity" "The Tyrant" "The Union" "The Wind" "The Wrath" "Lucky Deck" "Treasure Hunter" "Vinia's Token" "Trial" "Dialla's Subjugation"
	SetFontSize 40
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 Cosmetic: Black Text
	SetBorderColor 0 0 255 255           # BORDERCOLOR:	 Cosmetic: T1 and T2 Divination
	SetBackgroundColor 50 220 240 235    # BACKGROUND:	 T3 Divination
	PlayAlertSound 2 300                 # DROPSOUND:	 Value Drop: Currency, fragments

#------------------------------------
#   [1205] T5 - Format trash tier cards... before
#------------------------------------

Show #%H3
	Class "Divination"
	BaseType "Carrion Crow" "Other Cheek" "Hermit" "King's Blade" "Prosperity" "Metalsmith's Gift"
	SetFontSize 32
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 Cosmetic: Black Text
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Cosmetic: Neutral Highlight
	SetBackgroundColor 175 215 230 180   # BACKGROUND:	 T5 Divination

#------------------------------------
#   [1206] T4 - ...showing the remaining cards
#------------------------------------

Show
	Class "Divination"
	SetFontSize 38
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 Cosmetic: Black Text
	SetBorderColor 0 100 150 255         # BORDERCOLOR:	 Cosmetic: T4 Divination
	SetBackgroundColor 145 215 230 225   # BACKGROUND:	 T4 Divination
	PlayAlertSound 2 300                 # DROPSOUND:	 Value Drop: Currency, fragments
	
Show
    LinkedSockets = 6
    Rarity >= Normal
	SetFontSize 48
    SetTextColor 255 0 0
    SetBackgroundColor 255 255 255
    PlayAlertSound 6 300


Show
    BaseType "Titan Gauntlets" "Slink Boots" "Slink Gloves" "Titan Greaves" "Dragonscale Boots" "Dragonscale Gauntlets" "Royal Burgonet" "Lion Pelt" "Mind Cage"
    Rarity = Rare
    SetBorderColor 0 0 0 0
    SetFontSize 48
Show
    BaseType "Vaal Regalia" "Sorcerer Boots" "Sorcerer Gloves" "Hubris Circlet" "Titanium Spirit Shield" "Fingerless Silk Gloves" "Gripped Gloves" "Spiked Gloves" "Two-Toned Boots" "Bone Helmet" 
    Rarity = Rare
    SetBorderColor 0 0 0 0
	SetBackgroundColor 153 255 255
    SetFontSize 48
	

    
		
		
Show 
	BaseType "Sorcerer Boots"
	Rarity Normal
	SetTextColor 255 255 255 255         
	SetBorderColor 0 210 0 210           

	
Show
    BaseType "Orb of Alchemy" "Chaos Orb" "Orb of Scouring" "Orb of Fusing" "Orb of Regret" "Regal Orb" "Cartographer's Chisel" "Vaal Orb" "Gemcutter's Prism" "Blessed Orb" "Master Cartographer's Sextant" "Journeyman Cartographer's Sextant" "Apprentice Cartographer's Sextant" "Splinter of Chayula"
    Rarity >= Normal
    SetBorderColor 255 165 0
    SetFontSize 48
    PlayAlertSound 9 300

Show
    Class "Jewel"
    Rarity = Rare
    SetFontSize 48

Show
    BaseType "Talisman"
	SetFontSize 48

Show
    Rarity = Unique
    SetFontSize 48
    PlayAlertSound 3 300

Show
    BaseType "Fishing Rod" "Exalted Orb" "Divine Orb" "Mirror of Kalandra" "Eternal Orb"
    Rarity >= Normal
	SetFontSize 48
    SetTextColor 255 0 0
    SetBackgroundColor 255 255 255
    PlayAlertSound 6 300


 
 Show 
 Class "Maps"
 BaseType "Shaped Mesa" "Shaped Strand" "Shaped Atoll" "Shaped Courtyard" "Mesa" "Strand" "Shaped Beach" "Atoll" "Shaped Channel" "Shaped" "Tropical Island" "Dunes" "Canyon" "Acid Lakes"
 SetFontSize 48
    SetTextColor 0 0 255
    SetBackgroundColor 255 255 255  
	PlayAlertSound 3	300    
	
Show
    DropLevel >= 76
    Class "Maps"
	SetFontSize 48
    SetTextColor 0 0 255
    SetBackgroundColor 255 255 255  
	PlayAlertSound 8	300   
Hide
    Class "Maps"
	DropLevel < 76 
Show
	BaseType  "Glassblower's Bauble" "Orb of Alteration" "Jeweller's Orb" "Orb of Chance" "Chromatic Orb"   "Splinter of Uul-Netol" "Splinter of Xoph" "Splinter of Esh" "Splinter of Tul"
	SetFontSize 48
	
Hide
	 BaseType  "Breach Ring"  "Orb of Transmutation" "Orb of Augmentation" "Armourer's Scrap" "Blacksmith's Whetstone"
Hide
	BaseType "Occultist's Vestment"
	Rarity Normal
	SetTextColor 255 255 255 255        
	SetBorderColor 0 150 0 150        

Hide
    BaseType "Scroll of Wisdom"  "Portal Scroll"



Show
    BaseType "Empower" "Enlighten" "Portal" "Enhance" "Vaal Breach" "Item Quantity" "Detonate Mines"
    SetFontSize 48

Show
    Quality >= 15
    Class "Gem"
    SetFontSize 48

Show
    Class "Divination Card"
    SetTextColor 255 165 0
	SetFontSize 48
    PlayAlertSound 7 300

Show
    LinkedSockets >= 5
    SetTextColor 0 0 0
    SetBackgroundColor 255 153 153
    SetFontSize 48


Show
    Sockets = 6
    SetBorderColor 0 255 255
    SetFontSize 48
    PlayAlertSound 4 300


Show
    BaseType "Imperial Skean" "Imbued Wand" "Jewelled Foil" "Vaal Rapier"  "Sai" "Ambusher" "Platinum Kris" "Imperial Claw" "Gemini Claw"
    Rarity = Rare   
    SetBorderColor 38 209 22 200
    SetFontSize 48	
	
Hide
	BaseType "Infernal Axe" "Sambar Sceptre" "Coronal Maul" "Harbinger Bow" "Vaal Rapier"  "Dragoon Sword" "Eclipse Staff" "Astral Plate" "Glorious Plate" "Zodiac Leather" "Assassin's Garb" "Vaal Axe" 
    Rarity = Normal
    ItemLevel >= 84
    SetBorderColor 38 209 22 200
	

		
Show
    BaseType "Imperial Skean" "Sai" "Ambusher" "Platinum Kris" "Demon Dagger" "Jewelled Foil" "Imperial Claw" "Gemini Claw" "Imbued Wand"
    Rarity = Normal
    ItemLevel >= 84
	SetFontSize 48	
    SetBorderColor 38 209 22 200

Show
    BaseType "Astral Plate" "Titan Gauntlets" "Slink Boots" "Slink Gloves" "Titan Greaves" "Dragonscale Boots" "Dragonscale Gauntlets" "Royal Burgonet" "Lion Pelt" "Nightmare Bascinet" "Imperial Buckler"  "Mind Cage" 
    Rarity = Rare
	SetFontSize 48
    SetBorderColor 38 209 22 200
	
Hide
    BaseType "Harbinger Bow" "Exquisite Blade" "Fleshripper" "Vaal Axe" "Coronal Maul" "Opal Sceptre" "Colossal Tower Shield"
    Rarity = Rare
    SetBorderColor 38 209 22 200
	
	Show
        Class Gem
        BaseType "Vaal"
        SetTextColor 14 161 155
        SetBorderColor 220 30 30
        SetBackgroundColor 0 0 0
        SetFontSize 48
	
Hide
    BaseType "Astral Plate" "Titan Gauntlets" "Slink Boots" "Slink Gloves" "Titan Greaves" "Dragonscale Boots" "Dragonscale Gauntlets" "Royal Burgonet" "Lion Pelt" "Nightmare Bascinet" "Imperial Buckler" "Colossal Tower Shield"  "Mind Cage"
    Rarity = Normal
    ItemLevel >= 84
    SetBorderColor 38 209 22 200
	
Show
    BaseType  "Bone Helmet" "Two-Toned Boots" "Spiked Gloves" "Gripped Gloves" "Fingerless Silk Gloves"
	SetBorderColor 255 165 0
	SetBackgroundColor 153 255 255
    SetFontSize 48
    PlayAlertSound 9 300
	Rarity >= Normal
	
	

Show
    BaseType "Vaal Regalia" "Sorcerer Boots" "Sorcerer Gloves" "Hubris Circlet" "Titanium Spirit Shield"  "Crusader Gloves" "Crusader Boots" 
    Rarity = Rare
	SetBackgroundColor 30 90 45 225
    SetBorderColor 38 209 22 200
	SetFontSize 48

	
Show
    BaseType  "Hubris Circlet" "Vaal Regalia" "Titanium Spirit Shield" "Sorcerer Boots" "Sorcerer Gloves" 
    Rarity >= Normal
    ItemLevel >= 84
    SetBorderColor 38 209 22 200
Show
    BaseType "Crystal Belt" "Steel Ring" "Blue Pearl Amulet" "Marble Amulet" "Vanguard Belt" "Opal Ring"
    SetBorderColor 255 165 0
	SetBackgroundColor 153 255 255
    SetFontSize 48
    PlayAlertSound 9 300
	Rarity >= Normal

    SetFontSize 48

Show
    BaseType "Two-Stone Ring" "Topaz Ring" "Diamond Ring" "Ruby Ring" "Sapphire Ring" "Turquoise Amulet" "Citrine Amulet" "Lapis Amulet" "Amber Amulet" "Onyx Amulet" "Prismatic Ring" "Rustic Sash" "Leather Belt" "Agate Amulet" "Jade Amulet"
    Rarity = Rare
    SetFontSize 48
	SetTextColor 255 190 0               # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 25 235 25 255         # BORDERCOLOR:	 Rares - Size - Tiny, special base
	SetBackgroundColor 30 90 45 225      # BACKGROUND:	 Rares - Basetype - Great
	

	
Show #$great, tiny
	Class Rings Amulets Belts
	SetFontSize 48
	Rarity Rare

	
	
Hide
    BaseType "Two-Stone Ring" "Topaz Ring" "Diamond Ring" "Ruby Ring" "Sapphire Ring" "Turquoise Amulet" "Citrine Amulet" "Lapis Amulet" "Amber Amulet" "Onyx Amulet" "Prismatic Ring" "Rustic Sash" "Leather Belt" "Agate Amulet" "Jade Amulet"
    Rarity = Normal	
    ItemLevel >= 84
    SetFontSize 45
Show
    Identified True
	Rarity > Magic



Show
BaseType  "Sai" "Platinum Kris"  "Imbued Wand"  "Ambusher" "Imperial Skean" "Demon Dagger" "Vaal Rapier" "Jewelled Foil" "Astral Plate" "Glorious Plate" "Imperial Claw" "Gemini Claw"
Rarity = Rare

Show
BaseType "Titan Greaves" "Titan Gauntlets" "Royal Burgonet" "Vaal Regalia" "Saintly Chainmail" "Carnal Armour" "Sorcerer Gloves" "Sorcerer Boots" "Hubris Circlet" "Crusader Gloves" "Crusader Boots" "Murder Boots" "Murder Mitts" "Titanium Spirit Shield" "Archon Kite Shield" "Supreme Spiked Shield" "Profane Wand" 
Rarity = Rare

Hide #$rgb, small, lvl
	SocketGroup RGB
	Width <= 2
	Height <= 2
	Rarity < Rare
	SetBorderColor 0 0 0           # BORDERCOLOR:	 Rares - Size - Small (+Good basetype), Recipe: small/high qual
	SetBackgroundColor 0 0 0          # BACKGROUND:	 Recipes

Hide #$rgb, small, lvl
	SocketGroup RGB
	Width <= 1
	Height <= 3
	Rarity < Rare
	SetBorderColor 0 0 0           # BORDERCOLOR:	 Rares - Size - Small (+Good basetype), Recipe: small/high qual
	SetBackgroundColor 0 0 0         # BACKGROUND:	 Recipes
	
	Show
    Class "Map Fragments" "Quest Items" "Labyrinth Map Item"
	SetFontSize 48
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 Cosmetic: Black Text
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Cosmetic: Neutral Highlight
	SetBackgroundColor 180 0 0 255       # BACKGROUND:	 Fragments - valuable
	PlayAlertSound 4 300                 # DROPSOUND:	 T1 maps
	
	Show
    Class "Currency" "Maps"
	SetFontSize 48
	Show
    BaseType Flask
    BaseType "Diamond" "Granite" "Quicksilver" "Ruby" "Sapphire" "Topaz" "Quartz" "Stibnite" "Basalt" "Sulphur"
    SetBorderColor 200 200 0 180
    SetBackgroundColor 0 0 0
    SetFontSize 32
Show
	BaseType "Offering to the Goddess"
	SetFontSize 48
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 Cosmetic: Black Text
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Cosmetic: Neutral Highlight
	SetBackgroundColor 180 0 0 255       # BACKGROUND:	 Fragments - valuable
	PlayAlertSound 4 300                 # DROPSOUND:	 T1 maps
	Hide
    Class "Mana Flasks" "Hybrid Flasks" "Utility Flasks" "Life Flasks"
Hide
