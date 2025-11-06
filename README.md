Recommended to use on any of the following [SheltUpdate for multi client loading (the preferred way in my opinion)](https://shelter.uwu.network/install), [Ez-Vencord-Install for dev edition vencord making it easy to install/add third party plugins](https://github.com/VTArcelia/ez-vencord-install) or [Vanilla Vencord](https://vencord.dev/)

------------------------

[Use syndishanx's theme fixer if you want to fix broken classes](https://syndishanx.github.io/Website/Update_Classes.html)

this changes the classes of things that are broken to their latest if it exists, example if something was like `icon__23ae83` it would update that to `icon__47e34a` if it was the latest. it doesn't work unless it is stuff like that where you can actually see the class, aka the original css before it was made into something user friendly. Typically used on quickcss but you can use on actual themes if you get the original file to update them. 

-------------------------

To use put the following in your quickcss editor of choice,
```
@import (https://vtarcelia.github.io/Discord-QuickCSS/OpenAsar.css);
@import (https://vtarcelia.github.io/Discord-QuickCSS/fontreplacer.css);
```

or if you are using an online theme importer such as vencord's online theme tab

```
https://vtarcelia.github.io/Discord-QuickCSS/OpenAsar.css
https://vtarcelia.github.io/Discord-QuickCSS/fontreplacer.css
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







# Setup
Using SheltUpdate for Shelter with the following Plugins

- anonymize file names by Amy
- Better Screenshare Quality Fix by Xirreal
- Antitrack by Yellowsink
- No Dev Tools Detection by Yellowsink
- QuickReply by Yellowsink
- Text Replacements by Yellowsink (x.com link to stupidpenisx and youtube.com/watch?v= to youtu.be/)
- No F1 by ErogeMaster225
- Notification Volume by ioj4 (20% volume)
- Open Profile Images by ioj4
- Orbolay Bridge by SpikeHD (with orbolay obviously)
- Invisible Typing by SpikeHD (my version without the toggle so it's just forced on)

The following theme + my Openasar.css

https://refact0r.github.io/system24/build/system24.css

You can find everything needed for my setup at https://shelter.uwu.network/ & theme's at whatever the fuck betterdiscord's site is

