# Europa Universalis: The price of Power fan-made rules wiki

From a suggestion in the Aegir Games Community discord channel, I thought that creating a wiki-like rules document would be a helpful resource for this game to more easily links rules related to specific concepts together. For example, every reference to "Change Religion" on a single page to save switching back and forth between pages.

I have decided on a Hugo static site as that is what I have some experience with, and the .md files that I will create should be able to be ported easily to another wiki platform if it needs to change.

I'm imagining starting by just getting all of the rulebook text into text files, then splitting then into logical pages/sections, then duplicating whatever text is needed for each term, then adding links.

To display the game symbols, I have overridden the font used for code blocks, but the rest of the code block format remains. If anyone has some experience with Hugo or CSS maybe you could give me some help. I'm not too fussed about the regular text font at this time.

If you see any errors, please click on "Issues" near the top of the Github page and create a new issue.

To-do:
- Copy rules text from official PDF, with one .md file (and thus one web page) for each section
	- How I define a "section" is still up in the air
- Replace links to other pages in the PDF with linkes to other pages in the wiki
- For each term in the index, create a page containing all of the rules references to that item
- List any other concepts that may need their own page and create them
- Try to fix the symbols so that they appear with no background or padding and have a larger font to be legibe
- The specific symbol for "Administrative Action Card" seems to not copy properly from the PDF, so fix that
- See if I can also find an easy way to format area names as small caps instead of LARGE CAPS