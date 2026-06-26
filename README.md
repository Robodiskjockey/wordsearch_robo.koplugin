# Word Search Puzzle Plugin 2 for KOReader!!!

This KOReader plugin generates classic word search puzzles directly on your device. Each puzzle mixes horizontal, vertical, and diagonal words while heuristics spread words across directions and starting points to avoid clustering.

I added some new word lists and stuff to it. Have fun -Robo

Originally came from wordsearch.koplugin by Omer-faruq.

## How to download
[wordsearch_robo.koplugin.zip](https://github.com/user-attachments/files/29361494/wordsearch_robo.koplugin.zip)
1. Download the .zip
2. Extract the .zip, it should come out as a folder
3. Move the entire newly-extracted folder into '.adds/plugins'.
4. Restart the koreader, and if everything goes right you should be able to play the game.

## Gameplay overview
1. Launch **Tools → Word Search**.
2. Tap the first and last letters of a word to select it. A line is drawn behind the grid letters and highlighted when the match is correct.
3. Tap **Words** to view the current list (found words are struck through).
4. Use **Show solution / Hide solution** to toggle helper lines for every hidden word.
5. A congratulatory overlay appears once every word is found.

## Adjustable settings
All settings persist between sessions.

- **Word count**: Choose 6–24 words per puzzle. Changing the count regenerates the grid.
- **Grid size**: Pick an 8×8 up to 16×16 board. The plugin automatically validates sizes and regenerates the puzzle.
- **Grid zoom**: Switch between predefined zoom levels that control the rendered cell size.
- **Word lists**: Select from bundled lists or any compatible `.txt` file to refresh the board with new vocabulary. I added a whole bunch of new files so it's not just 5k and 1k
- **New puzzle**: Forces a new puzzle regeneration with the current settings.

## Word lists
1. Here's how to make your own files:
2. Make a new .txt file at 'wordsearch.koplugin/word_lists'. You really don't need to give it a good name but it's best to give it a good name.
3. You'll want to add 'lang=en letters=ABCDEFGHIJKLMNOPQRSTUVWXYZ title=English_Basics_2k' to the beginning. Change the letters string if you want to add numbers, like '...letters=ABCDEFGHIJKLMNOPQRSTUVWXYZ-1234567890'. You can add numbers, dashes (-), but it's best not to add anything else or that will wonk up the other words and stuff.
4. Change the title (the title is what appears ingame, so for example you could do 'user_words'. You can use caps but don't add spaces into the title.
5. Add whatever you want underneath with new lines each word, for example I could add 'among' and 'us'. Any unsupported symbols or symbols you didn't add into the letters will be removed.
6. Restart your koreader, then open up word search, click 'word lists' and then your new '.txt' file, for example if you called it 'my_words' then look for 'my_words'.
That's all I did to make word lists.

## Saving & continuity
The plugin saves the active board, chosen list, grid size, max word count, and zoom level to KOReader's settings directory. Closing and reopening KOReader resumes exactly where you left off unless you generate a new puzzle.

## Credits
Created with the help of Windsurf (AI).
Again, this was made using Wordsearch.koplugin by Omer-faruq, so go check his out after mine.
