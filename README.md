# IT-140-Project-One

GameConcept: Eldritch Castle
 Set in a decaying, cursed castle, the player must explore to find six magical artifacts and defeat
 the evil sorcerer who controls the castle. The game combines exploration and item collection,
 with the player needing to avoid the sorcerer until all artifacts are gathered. The sorcerer will
 defeat the player instantly if encountered before collecting the items.
 Storyline
 The player is transported to Eldritch Castle, where the sorcerer’s dark magic has warped reality.
 Six artifacts—Spellbook, Elixir, Key, Shield, Rare Flower, and Magical Dagger—are scattered
 across the castle. The player must collect all the artifacts while avoiding the sorcerer, who is
 hidden in his lair. Only after gathering the items can the player challenge the sorcerer.
 Rooms and Items
 1. Start Room: The castle’s entryway.
 2. Library: Contains the Spellbook.
 3. Alchemy Lab: Holds the Elixir.
 4. Banquet Hall: The Key is found here.
 5. Courtyard: The Shield is located here.
 6. Garden: The Rare Flower grows here.
 7. Tower: The Magical Dagger is hidden here.
 8. Sorcerer’s Lair: The final room, where the sorcerer waits.
 Villain: The Sorcerer
 The sorcerer controls the castle and resides in the Sorcerer’s Lair. The player must avoid this
 room until all six artifacts are collected, as entering prematurely results in instant defeat. Only
 after gathering all the items can the player confront and defeat the sorcerer in a final battle.
 Pseudocode for Room Movement:
 While True:
 Prompt: "Which direction do you want to go?"
 Get input: direction
 IF direction is valid:
 Move player to new room
Output: "You move [direction]."
 Break loop
 ELSE:
 Output: "Invalid direction."
 Pseudocode for Item Collection:
 While True:
 Prompt: "Which item would you like to take?"
 Get input: item
 IF item is in room:
 Add item to inventory
 Output: "You take the [item]."
 Break loop
 ELSE:
 Output: "Item not here.
