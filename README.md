# pokemon-db
A database of all 807 Pokémons along with their sprites

The database in available only in JSON format, and the Schema looks like: 

    [
    	{
        	id: Integer,
            name: String,
            types: [ String... ],
            species: String,
			places: [
            	{
                	gen: [ String... ],
                    details: String
                }
            ]
        }, ....    
    ]

For example, Mew is represented by :

	{
      "id": 151,
      "name": "Mew",
      "types": [
        "Psychic"
      ],
      "species": "New Species Pokémon",
      "places": [
        {
          "gen": [
            "Red",
            "Blue",
            "Yellow"
          ],
          "details": "Trade/migrate from another game"
        },
        {
          "gen": [
            "Gold",
            "Silver",
            "Crystal"
          ],
          "details": "Trade/migrate from another game"
        },
        {
          "gen": [
            "Ruby",
            "Sapphire",
            "FireRed",
            "LeafGreen"
          ],
          "details": "Trade/migrate from another game"
        },
        {
          "gen": [
            "Emerald"
          ],
          "details": "Faraway Island"
        },
        {
          "gen": [
            "Diamond",
            "Pearl",
            "Platinum",
            "HeartGold",
            "SoulSilver"
          ],
          "details": "Trade/migrate from another game"
        },
        {
          "gen": [
            "Black",
            "White",
            "Black 2",
            "White 2"
          ],
          "details": "Trade/migrate from another game"
        },
        {
          "gen": [
            "X",
            "Y",
            "Omega Ruby",
            "Alpha Sapphire"
          ],
          "details": "Trade/migrate from another game"
        },
        {
          "gen": [
            "Sun",
            "Moon",
            "Ultra Sun",
            "Ultra Moon"
          ],
          "details": "Trade/migrate from another game"
        }
      ]
    }
    
Of course, all of this data is the property of Game Freaks / Nintendo / Whatever / Please don't sue me I don't have money / bla bla bla.
