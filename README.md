Recommended to use on any of the following [Ez-Vencord-Install for dev edition with third party plugins pre-installed](https://github.com/VTArcelia/ez-vencord-install), [SheltUpdate for multi client loading](https://shelter.uwu.network/install), or [Vanilla Vencord](https://vencord.dev/)

------------------------

[Use syndishare's theme fixer if you want old icons on MrDiamondDog's css](https://github.com/MrDiamondDog/noUglyIconsTheme)

-------------------------

To use put in your quickcss editor of choice,
```
@import (https://vtarcelia.github.io/Discord-QuickCSS/theme-of-choice.css);
```
or if you are using an online theme importer such as vencord's specific tab
```
https://vtarcelia.github.io/Discord-QuickCSS/theme-of-choice.css
https://vtarcelia.github.io/Discord-QuickCSS/theme-of-choice2.css
```


-------------------------

You can also change parts of imported themes via quick css

example we will look at fontreplacer.css

```
@import url('https://fonts.bunny.net/css?family=atkinson-hyperlegible:400,400i,700,700i');
:root
 { --font-primary: "Atkinson Hyperlegible";
   --font-display: "Atkinson Hyperlegible";
   --font-headline: "Atkinson Hyperlegible";
   --font-code: "Atkinson Hyperlegible"; 
   --nvfontsize: 13px; }

html,
[class*=heading-md],
[class*=text],
[class*=input_],
[class^=topic_],
[class^=name_],
[class*=item_],
[class*=description_],
[class*=tooltip_]
 { font-size: var(--nvfontsize) !important; }
```

Anything in the :root section can be changed you would do the following. say we want to change just the font size
```
:root {
  --mvfontsize: 16px;
}
```

This increases the font size from 13px to 16px, my preference is completely different from yours, so obviously you will want to change stuff.

if the theme has an import in it already for example font replacer has the atkinson hyperlegible font, you cant remove it, but you can also just @import whatever font you want, and then change all of the font settings inside of the root to use your own font.

I suggest using fonts.bunny.net over google fonts, but you are free to use anything you want. 
