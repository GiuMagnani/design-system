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
• Margin
• Padding
• Width
• Height
• Box shadows
• Border radius
• Border width
• Opacity
• Z-Index
