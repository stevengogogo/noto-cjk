# Noto CJK
Noto CJK is available in multiple formats which have different uses. Each of
these font formats used below has the capability to display both horizontal
and vertical forms where appropriate. Any of the fonts that support
Japanese will also be able to support proportional kana.

Note: New in release 1.002 were 'Monospace' versions. These provide half-width
instead of proportional widths for ASCII (U+0020 to U+007E) and the following
characters: U+00A0, U+00A5, U+2011, and U+20A9. These come in two weights
(Regular and Bold) for each of the five languages. These fonts have 'Mono' in
the family name, e.g. 'Noto Sans Mono CJK {HK, JP, KR, SC, TC}'.


### Super OTC
This packaging form carries the fonts for each of Simplified Chinese,
Traditional Chinese, Traditional Chinese HK, Japanese, and Korean multiplied
by all 7 weights for each in one single font file. In addition, each language
provides monospace versions in Regular and Bold weights. Once installed it
will appear in font menus as 45 separate fonts. This format is the easiest to
install of all the formats and takes the least space due to sharing between the
45 pieces.

**Special Note**: This deployment format requires macOS (OS X) Version 10.8 (aka *Mountain Lion*) or later, iOS 7 or later, Windows 10 Version 1703 (aka *Creators Update*) or later, a flavor of Linux that uses *fontconfig* and FreeType Version 2.5.0.1 or greater, or Adobe CS6 apps or later.


### OTC
This packaging form carries the fonts for each of Simplified Chinese,
Traditional Chinese, Traditional Chinese HK, Japanese, and Korean in a single font file. Once
installed it will appear in font menus as four or eight separate fonts. This
format is the easiest to install and compared to installing separate fonts
takes less space. There are 7 of these OTC font files with one for each weight
from Thin to Black.

Two of these files (Regular and Bold) also contain new 'Monospace' versions for
each language. These files appear in font menus as eight separate fonts.

**Special Note**: This deployment format requires macOS (OS X) Version 10.8 (aka *Mountain Lion*) or later, iOS 7 or later, Windows 10 Version 1607 (aka *Anniversary Update*) or later, a flavor of Linux that uses *fontconfig* and FreeType Version 2.5.0.1 or greater, or Adobe CS6 apps or later.

### Multilingual OTF
This packaging form has 5 language specific variants that have all the same
glyph coverage as the OTC format but provide language coverage through the
use of the OpenType 'locl' feature. In each of these font files there is a
single default language which is used when the 'locl' feature isn't
specified. There are 35 of these files (5 language default variants * 7
weights).

Each language also provides Monospace variants in Regular and Bold. There are 10
of these files (5 language default variants * 2 weights).

### Region-specific OTF
This packaging form provides monolingual subset versions of the fonts. There is
a separate font file for each of Simplified Chinese, Traditional Chinese, Traditional Chinese HK,
Japanese, and Korean. If you want to install one language only then this
would be the option to consider. It will have the smallest space requirement.
It would also be the choice if you want to use the font on a system
(such as Windows) that doesn't support the OTC format and can’t use the OpenType
‘locl’ feature to select language.

The region-specific OTFs do not include the Monospace versions.
