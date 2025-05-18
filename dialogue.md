# pilot & copilot dialogue

**pilot:** I want to use Geist fonts with MapLibre GL JS. I would like to generate SDF fonts and place them in the docs folder.

**copilot:** Understood. I will convert the Geist fonts (licensed under OFL) to SDF using FontMaker and copy them to the docs folder.

**pilot:** Geist fonts are available in both otf and ttf. Which should I use?

**copilot:** TTF is recommended for FontMaker. Please use the TTF files.

**pilot:** Can I use the variable font (Geist[wght].ttf)?

**copilot:** Yes, variable fonts are supported by FontMaker. You can generate SDFs for each weight as needed.

**pilot:** I tried the variable font, but only the Regular weight was generated. I will convert each ttf font instead.

**copilot:** Understood. Let's generate SDFs for each weight using the ttf fonts.

**pilot:** I have copied the SDF fonts to the docs folder. Please add the list of available fonts to the README.

**copilot:** I have inserted the list of 18 font names into the README.md.

**pilot:** I have checked the contents. Is it okay to push?

**copilot:** There are no issues. You can push as is.

**pilot:** Please update the usage instructions in simple, constructive, and polite English, describing how to set the `glyphs` property and specify the font name in `text-font`.

**copilot:** I have rewritten the usage instructions in clear English, including examples for both the `glyphs` property and the `text-font` property, so users can easily configure MapLibre GL JS to use Geist fonts.
