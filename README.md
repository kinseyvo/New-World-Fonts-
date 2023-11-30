# New-World-Fonts

Create a Font Browser using Google Fonts API.

- User can select a font from a list of Google Fonts
- Allow selection of Style (bold, ital, or combo at least)
- User can switch between entering a phrase and browsing the font. Both update if the font is changed
  - Entering a phrase 
  - User can enter a text/phrase/line
  - On text edit, render the text in that font
  - Allow size selection
- Browsing the font:
  - Draw a grid of letters (visible chars between 0x20 and 0x7F)
  - with borders of grid, and between letters; render using font
  - Include a larger space (bordered)
  - When user touches a letter, render the letter in the larger space
  - must allow style, choose the Sizes to fit the grid/larger (user cannot select size on browse screen)
- Add a personally-chosen feature
- About Page
