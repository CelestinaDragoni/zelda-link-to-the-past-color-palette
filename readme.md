# A Link to the Past  (Kamigami no Triforce) Color Palette
A relatively accurate generation of all of the colors used in The Legend of Zelda - A Link to the Past (Kamigami no Triforce)

## Why Would You Do This?
I went diving into the internet and I wanted to find a good color sheet of Link to the Past for my own purposes. However, I came up empty despite the various requests around this very thing.

## The Process

This is all likely extremely convoluted because I could have just dumped the assets and generated the palette, but it was fun, so whatever.

- I built **Mondo Color Generator** so I had a toolkit to use, you can check it out here for your own purposes: https://github.com/KernelZechs/mondo-palette-generator
- I decided on using emulation for this since it would be pixel clean. Despite my SNES Jr. being RGB modded and hooked up to HDMI it's still not as crisp as say, a direct framebuffer. Now you may be concerned with the accuracy of the colors, but considering the SNES used RGB data for their assets (unlike like the NES) , it's safe to assume the colors are fairly accurate emulation side. (Note: I used SNES9x v1.60 for this)
- I played the game from start to finish. Nearly 100% (all heart containers or bottles weren't important but getting every item and upgrade was for color count).
- I made sure to engage visibly all NPCs that weren't duplicates and areas that weren't duplicates to get into keyframes.
- I recorded everything at 1fps into PNG images and then manually picked good keyframes to throw in as samples.
- Then used my tools to generate the palette files.

## Which Version?

 - Japanese 1.0 (Kamigami no Triforce) dumped from my own personal cart for this project.

## How Accurate Do You Think It Is?
I'm going to guess around 95% accurate and here is why:

 - Compositing effects are still around despite not adding any dark room, lost woods, or other weird areas. Dark woods is in here because it truly is unique in color, but it still has some effects and layer removal is tricky to get clean.
 - There are places I may have missed that had small color variances. You'll see Nintendo wasn't exactly consistent with its color indexing and it's sort of all over the place. And even though I went into areas I haven't been in years, likely something was missed.

## What Should I Do With This?
Well, you could use the raw palette and just get to work. However (likely what I'm going to do) is index reduce this down to less colors. There is too much to digest here and if you're working on a 2D game project this would be nightmarish to start with as is. However, if you like that sort of thing, more power to you.

## Palette Files Included (Output Folder)

- Adobe Color Palette (ACO)
- CSS
- SASS/SCSS
- LESS
- Text
- JSON
- HTML
- PNG

## Source Images (Images Folder)
These are the keyframes from my gameplay. If you want to regen the palette yourself download the toolkit mentioned above and follow the instructions in the readme.

## License
No license, this is free for all who want to use it. Get creative and have fun with it.

## Palette Preview
