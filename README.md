# ARR_TeamBuilder
A calculator that automatically builds teams for birthday events.

## How to use
Fill out the character’s card info in the JSON file included in the folder, cards.json, on any text editor program (Notepad on Windows or TextEdit on Mac for example). Ideally, use only the birthday character’s cards.

Within the “cards”: [] list, each card’s data’s stored within {}
```{
“cardName” : “Name of the card”,
“character” : “Name of the character”,
“affinity” : “TECH, PWR, or SPD”,
“rarity” : “N, R, SR, or SSR”,
“awakenings” : 0, 1, 2, 3, or 4,
“leaderSkill” : number without the percentage mark,
“PWR” : base value,
“TECH” : base value,
“SPD” : base value,
“is_current_birthday_card”: true if it’s the birthday card for the 
current year, false if it’s not
}
```

and separated with commas. The card name doesn’t have to be the same as its name in the game, but if you are including duplicates, make sure that they will allhave the same name. The program will take care of duplicates. Also make sure that the character name spelling is consistent.

Once you are done filling out your cards in the JSON file and saved it, open `ARR_Calculator.exe.`

You’ll first be prompted to enter the character you’re building a deck for. Make sure the 
spelling’s the same as it is in the JSON file. If you do make a typo, you can fix it with 
Option 6.

Next, you will be given 7 options. First, load in your cards with the JSON file. You can also reload your cards with option ‘1’ should you change something in your file. Make sure the file is in the same folder as the `ARR_Calculator.exe`.

Option 2 lets you view the cards that you loaded into the program. Options 3-5 will auto generate decks depending on the number of SP you want to use. It will give you the cards names, and if there aren’t enough cards to make a full deck, it will either provide characters you can add for link skills or tell you to use any 2/3/4-person link skills. It will also tell you how many stages you can clear per SP with the decks built a how many points you get per SP when clearing the highest possible stage. 

