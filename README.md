# design-system
sources:
- Refactoring UI

### Font
- Use system fonts
- Ignore typefaces with less than five weights
- Optimize for legibility: for main texts (h1,h2,h3, etc) use "headlines" fonts (fonts designed specifically for headings). 
-- Headlines: Shorter x-height, tighter letter-spacing
-- Body: Larger x-height, wider letter-spacing
- If a font is popular, it’s probably a good font.
- Inspect some of your favorite sites and see what typefaces they are using.
- 45 and 75 characters per line.
- Align mixed font sizes by their baseline.
- Line-height and paragraph width should be proportional. Narrow content: shorter line-height (1.5), wide content: greater line-height (2). The purpose of increasing the line-height is to avoid reading two times the same line (easier to find the next line).
- Line-height and font size are inversely proportional. Small texts: taller line-height, large texts (headings): shorter line-height.
- when justifying text, also enable hyphenation
- It often makes sense to increase the letter-spacing of all-caps text to improve readability.

### Font size:
#### By ratio (2:3, 1:1.618)

- /1.618: 9.8888 (10)
- **base: 16px**
- x1.618: 25.888 (26)
- x1.618: 41.886784 (42)
- x1.618: 67.772816512 (68)
- ...

#### By eye
- 12, 14, 16, 18, 20, 24, 30, 36, 48, 60, 72

**Important:** Use only px or rem units. Ems are relative to the parent element.

• Font weight
• Line height


• Color
- **Greys:** 8-10 shades.
- **Primary colours:** 5-10; Colours that determine the overall look of a site.
- **Accent colours:** 5-10; emphasize, contrast, eye-grabbing, highlight, **different semantic states** (desctructive, warning, positive, etc).

For primary and accent colors, a good rule of thumb is to pick a shade that would work well as a button background.
Pick your darkest shade and your lightest shade.
The darkest shade of a color is usually reserved for text, while the lightest shade might be used to tint the background of an element. An alert use both colours.
Once you’ve got your base, darkest, and lightest shades, you just need to fill in the gaps in between them (until you make 9 shades).
**Trust your eyes, not the numbers.** Just try to avoid adding new shades too often if you can avoid it.

- Perceived brightness: every hue has an inherent perceived brightness due to how the human eye perceives color (between a yellow and a blue with same brightness, yellow seems to be brighter).
- Local minimums: red, green, and blue.
- Three local maximums: yellow, cyan, and magenta.

To make a color lighter/darker (without losing colour intensity = changing "l: lightness"):
- Lighter: rotate the hue towards the nearest bright hue — 60°, 180°, or 300°.
- Darker: to make a color darker, rotate the hue towards the nearest dark hue — 0°, 120°, or 240°.

You can of course combine these approaches too, getting some of the brightness by adjusting the hue and some from adjusting the lightness. Don't change the hue more than 20%-30%, or it will look like a totally different color instead of just lighter or darker.

• Margin
• Padding
• Width
• Height
• Box shadows
• Border radius
• Border width
• Opacity
• Z-Index
