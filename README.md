# Touhou Dialogue Generator

This is a repository for Touhou Dialogue Generator.

dataset.txt is what was created by using THWiki_parser.ipynb on https://github.com/DestructionCatalyst/TouhouWikiPages.
Then there were some manual changes made:
- Delete arrows and other ~~phallic~~ symbols that appear on rare occasions. The reason for this is that they are practically useless, but they affect the number of input dimensions, making the learning process slower. The tilda symbol is used quite often, so I left it, believing the model can pick up on using in. The same goes for note symbol
- Some standartization for chars like apostrophes or quotation marks
