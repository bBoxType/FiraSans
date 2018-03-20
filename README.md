# Fira Sans 4.3 * NEW *
# Fira Code 3.2
# Fira Mono 3.2

## Fira is a trademark of The Mozilla Corporation.

## Digitized data copyright 2012-2018, The Mozilla Foundation and Telefonica S.A., bBox Type GmbH and Carrois Corporate GbR, with Reserved Font Name "Fira" 

### Design 2012-2015: Carrois Corporate GbR & Edenspiekermann AG
### Design 2016 and later: bBox Type GmbH

_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _


### FIRA SANS font weights:

- Two 			(2 units / CSS 100)
- Four 			(4 units / CSS 100)
- Six  			(6 units / CSS 100)
- Eight			(8 units / CSS 100)
- Hair 			(14 units / CSS 100)
- Thin 			(22 units / CSS 100)
- UltraLight 	(34 units / CSS 200)
- ExtraLight 	(46 units / CSS 250)
- Light 		(58 units / CSS 300)
- Book 			(84 units / CSS 350)
- Regular 		(92 units / CSS 400)
- Medium 		(128 units / CSS 500)
- SemiBold 		(142 units / CSS 600)
- Bold 			(158 units / CSS 700)
- ExtraBold 	(178 units / CSS 800)
- Heavy 		(198 units / CSS 900)

__* Note on thin weight fractional coordinates__

All weights below “Thin” use fractional coordinates which is an optical decision. Rendering engines might not be able to deal with that correctly. As for that, these weights should be seen as an experiment by now. If you notice any problems in smaller sizes please consider to use weights from Thin.

### FIRA MONO font weights:

* Regular 		(84em / CSS 400)
* Medium 		(112em / CSS 500)
* Bold  		(158em / CSS 700)


!!! THANK YOU !!! MERCI !!! DANKE !!! Dziękuję !!!  Gracias !!! Kiitos !!! Obrigado !!! Спасибо !!!

_ Patryk Adamczyk and his colleagues at Mozilla Foundation and Mozilla Corporation for trust and huge support over the last years
_ Christine Sunkel at EdenSpiekermann for project management, organization and her patience.

_ Denis Jacquerye for stunning support concerning IPA and PAN African
_ Prof. Dr. Sebastian Kempgen at Uni Bamberg for offering his expertise on Slavistic matters
_ Georg Seifert, Andreas Eigendorf and Adam Twardoch for all-time technical support and advice
_ Finally: the whole community who helped improving Fira via Mail, GitHub and FireBug!

_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _

### Future prospect

_ This will be the last version of Fira Sans. Development will continue with FiraGO. See FiraGO for plenty of new scripts (Arabic, Hebrew, Devanagari, Thai, Georgian) and manual TT hinting.

_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _



## CHANGE LOG Fira Sans

_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _


### version/build 4.301 (Sans only), 19.03.2018

_ issue #25: change be.loclBGR to ve.loclBGR, thanks StefanPeev 
_ introduce clear names for stylistic sets
_ separate stylistic variant a and g (a=ss04, g=ss05), for R.Trinler
_ issue #12: change shape of /longs according to /f and /germandbls, thanks thlinard 
_ optimize anchor position of /zeta
_ add rfn-notice to copyright: with Reserved Font Name "Fira“
_ issue #26: Moved ligatures f_f, f_f_i, f_f_j, f_j, f_f_l to liga-feature. Thanks Ray.

_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _


### version/build 4.300 (Sans only)

LOCL FEATURES

_ loclHUN / hungarianumlaut (thanks, Thorsten)
_ loclBGR (also available via stylistic set 01) for Cy-EXT range in cooperation with Bulgarian Type Designers Botio Nikoltchev and Vassil Kateliev
_ ДЛФЉҔҦԪԬԮӅӺӼԈԒԔԠбгѓджийҋѝкќлптцшщџљюғҕҗқҝҥҧԥҭҵԫԭԯӂӄӆӣӥӷӻӽԉԏԓԕԡ + their .sc
_ loclSRB, loclMKD

ISSUES/FIXES

_ Optimize position or insert anchors for greek polytonic > ζ, ξ, ς, ψ (thanks, disk0x)
_ Italic: /pe-cy now has a real Italic shape
_ Italic: moved descender of /gedescender-cy (uni04F7) to the right
_ fixed an anchor issue with ɨ́  (thanks, Denis)
_ fixed an anchor issue with 031A COMBINING LEFT ANGLE ABOVE (thanks, Denis)
_ Removed f_t ligature (see next point)
_ introduced stylistic alternative short_f in combination with ascender letters (like h, t, k, …). Replacement via calt-feature
_ few optimized kerning pairs (thanks, Thorsten)
_ added uni1D7B /idotlessstroke (thanks, Ray)
added uni0305 /overlinecomb (thanks, Ray)
_ added uni25BA and uni25C4
_ changed descender of zedescender-cy.sc to match the according uppercase and lowercase letters
_ re-structured calt-feature for Greek (disappearing accents in all cap use)
_ deleted acute in /UpsilonacutehookSymbol.sc (disappearing accents in all cap use)
_ little changes of overall Metrics of Regular Master (text might wrap differently)
_ added some glyphs for Mac OSX system requirements (thanks, Jens)
_ plenty of smaller fixes

_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _


### version/build 4.203 (Sans only)

_ fixed #2 (LineHeight, Hinting) – thanks Ray
_ fixed #3 (Ligatures in Roman files) – thanks BonnEconLab
_ few optimized kerning pairs

_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _

### Fira Code 3.206

_ Fira Mono 3.206 with less Line Space (1.0)
_ fixed bug #156 (swapped /BoxLightDown /BoxLightUp)

_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _


### version/build 4.202 (Sans only)

_ Fira Condensed & Fira Condensed Italic now covering complete Glyph range of Fira 4.1 (see below)
_ New: Fira Compressed & Fira Compressed Italic
_ Fira Sans Condensed slightly wider to locate in the middle of Normal and Condensed
_ Glyphs source files of Fira Sans and Sans Italic now with 8 masters each, interpolation of width and weight possible
_ Completely reworked kerning (including #154)

_ Single-storey alternates for a and g accessible via .ss04 (#127)
_ Addition of currency symbols (#55 – 101)
_ Addition of ligatures ff, fj, ft, ffj, fft (#53 #180) [switch on dlig feature]

_ fixed bugs/requests mentioned on GitHub
_#130 (/longs missing in Upright)
_#121 (wrong letter – interpolation glitch)
_#147 (Greek polytonic accents)
_#171 (Style names)
_#149 (Copyright string)

_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _

## previous changes
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _

version/build 4.106 (Mono 3.206)

_ exported fonts via Glyphs 2.1.1 build 799 to fix UFO problems
_ added top and bottom anchors to all base glyphs (GitHub # 107)


### version/build 4.105 (Mono 3.205)

exported fonts via Glyphs 2.1 build 780 to fix technical problems: 
_ zero-width glyphs in TTF-files
_ truncation of glyph names
_ fix differences in GPOS-tables between OTF and TTF (affects diacritic positioning)

for Fira & Fira Italic:
_ fix greek small caps issue


### version/build 4.104 (Mono 3.204)

_ exported fonts via Glyphs 2.1 build 767 to erase remaining technical bugs from last version


### version/build 4.103 (Mono 3.203)

_ exported fonts via Glyphs build 750 to fix bug #81 — github
_ exported fonts via Glyphs build 750 — bugzilla 1167071
_ fixed — bugzilla 1167076


### version/build 4.102 (Mono 3.202)

Exported fonts via Glyphs build 749 to fix bug #81 — please check and report if fixed. THANKS.

Sans:
_ fixed /uni02AD — was upside down
_ fixed some interpolation glitches 


### version/build 4.101 (Mono 3.201)

Mono: 
_ correct width of /fraction (uni2044) and /divisionslash (uni2215) to 600 in bold master (#56 GitHub)

All Fira fonts: 
_ add /tironiansignet (uni204A) – Gaelic ampersand
_ #81 GitHub: should be solved by new export behavior of current Glyphs version (this version of Fira generated by Glyphs2-740)


### version/build 4.100

_ expand Fira to comprise the following unicode blocs (added appr. 500 glyphs since 4.004)

Cyrillic (uni0400 – 04FF)
Cyrillic Supplement (uni0500 – 052F)
Greek & Coptic (uni0370 – 03FF) [except from 12 coptic characters (uni03E2 – 03EF)]
Greek Supplement (uni1F00 – 1FFF) 

Each font of Fira Sans contains ~2600 glyphs now!

_ re-introduce curly ampersand in Italic; also added it in Roman. 
Accessible via .ss03 OR type ‚ #& ’ (replacement via calt feature)

_ eliminate interpolation glitch in Italic [light master of /exclam (uni0021)]
Thanks, Ralf Trinler

_ edit /Yat-cy (uni0462) and Izhitsa-cy (uni0474 / uni0475) 
Thanks, Prof. Dr. Sebastian Kempgen

_ place varia and oxia before uc letters just as other Greek uc diacritics (e.g. uni1FBA / uni1FBB)
Thanks, Prof. Dr. Sebastian Kempgen

!!! Set new line height value for both Fira Sans and Fira Mono to 1.2 (was: 1.4) !!!

typoAscender: 935
typoDescender: -265
typoLineGap: 0
winAscent: 935
winDescent: 265

(Please note that this was done due to explicit demand of Mozilla and some users.
This change affects existing layouts if default line height is selected.)

Solved Issues tagged „BUG“ on GitHub 

_#65
CSS, Greek & Safari 
Secure correct replacement of accented Greek uppercase/sc letters by unaccented letters via calt feature
Thanks, wfdd

_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _

### version/build MONO 3.200

_ expand Fira Mono to comprise the following unicode blocs (added appr. 500 glyphs since 3.111)

Cyrillic (uni0400 – 04FF)
Cyrillic Supplement (uni0500 – 052F)
Greek & Coptic (uni0370 – 03FF) [except from 12 coptic characters (uni03E2 – 03EF)]
Greek Supplement (uni1F00 – 1FFF) 

Each font of Fira Mono contains ~1500 glyphs now!

_ increase SB of /underscore (uni005F) and /underscoredbl (uni2017)
Thanks, Fred Mora

_ introduce new /r (uni0072) > see # 49 GitHub

_ add currency symbols (default, tosf)
/Liraturkish (uni20BA) 
/Ruble (uni20BD)
/RupeeIndian (uni20B9)

_ edit /Yat-cy (uni0462) and Izhitsa-cy (uni0474 / uni0475) 
Thanks, Prof. Dr. Sebastian Kempgen

_ place varia and oxia before uc letters (e.g. uni1FBA / uni1FBB)
Thanks, Prof. Dr. Sebastian Kempgen

_ new line height value see above 4.001


Solved Issues tagged „BUG“ on GitHub 

_#49
Mono r looks like dotlessi at small sizes 
Thanks, rudd-v-a.

#56
Cannot select Fira Mono as monospaced font under KDE 
Note: 
We exported nonspacing accents again. Recognition as „monospaced“ should work anyway due to a change in export routine in Glyphs. Please report if not!
Thanks, houserockr and Georg.

_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _


### version/build 4.004

_ add some Celtic characters, now providing full support for ISO-Latin 1–10 
_ add /literSign (uni2113) 

_ increase lSB of /napostrophe (uni0149); introduce positive kerning between upper quotes and /napostrophe
Thanks Friedel, Jonathan & Dwayne!

Solved Issues tagged „BUG“ on GitHub 

_#64
Delete positive kerning between f and u 
… Finally ;) 
Thank you charakterziffer.

_#74 
Shifted double quotes using WOFF file 
Thank you mdesantis and Georg.


### version/build 4.003

_ increase space between apostrophe and n in /napostrophe (uni0149) 
Thanks, Friedel!

_ fix few interpolation glitches


### version/build 4.002

_ expand Fira to comprise the following unicode blocs (added another 200 glyphs since 4.001)

Latin Extensions A (uni0100 – 017F)
Latin Extensions B (uni0180 – 024F)
IPA Extensions (uni0250 – 02AF)

Each font of Fira contains ~2100 glyphs now!

_ add anchors for combining accent support for IPA and Pan African
Beta status!! 
Please report if several combinations might not work due to missing anchors. We’ll fix it. Thanks!

_ set CSS weight class to 100 for weights thin and below
_ multiple minor improvements


### version/build 4.001

_ expand Fira according to Glyphs categories
Latin > Vietnamese, Piyin, IPA & Pan African Latin including small caps
(add approx. 460 glyphs including regional stylistic alternates for Pan African accessible via .ss01)

_ add currency symbols (default, osf, tf, tosf)
/Liraturkish (uni20BA) 
/Ruble (uni20BD)
/RupeeIndian (uni20B9)

_ add /Germandbls (uni1E9E) + sc
_ multiple minor improvements

_ Mono Update will follow after extension of Romans and Italics to Cyr and Greek Extended.

Issues tagged „BUG“ on GitHub 

_#57
line positioning in ie
Vertical metrics of official version remains unchanged until the test version is confirmed by so0ft on GitHub.
Setting typoLineGap to zero might lead to vertical metrics conflicts in other layouts/circumstances.

_#59
FsType indicating restricted embedding and subsetting 
fsType was „editable“, now set to „not set“ (installable). Should solve the problem.
Thank you n7s.

_#64
Delete positive kerning between f and u caused by a transfer glitch from FL to Glyphs
Thank you charakterziffer.

_#66
Greek tonos capitals with negative SB
Added some SB in the Black master of the following glyphs to ensure they don’t overlay the space in the bold weights. 
Thank you wfdd.

/Epsilontonos (uni0388)
/Etatonos (uni0389)
/Iotatonos (uni038A)
/Omicrontonos (uni038C)
/Upsilontonos (uni038E)


_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _


### version/build 3.111

_ TTFautohint via Glyphs 2 developer Beta GUI for TTF export
_ fixed zero width glyphs with no zero value in Italic
* PDFs stay version 3110, just renamed the zip-folder


### version/build 3.110

_ fixed TTF/WOFF/EOT in Mono export error caused by database divergence Glyphs2 Beta
_ fixed interpolation glitches coming with new behavior of anchors in Glyphs2 Beta
_ fixed zero width glyphs with no zero value in Mono
_ legibility improvement for code applications: braces, brackets and parens in Mono


### version/build 3.109

_ https://github.com/mozilla/Fira/issues/43
* impossible to get equal values for all OS issues with common methods.
= catch:
> set typoLineGap to 400 (was 200)
> set winDescender to -350 (was -500)
! known bug: cuts of lowest glyphs (-353 Ultra)
? Arabic (should not become lower)
? Vietnamese (should not become higher)


_ fixed zero width glyphs with no zero value
_ fixed PS hinting issues coming up changing grid in the very thin weights


### version/build 3.108

_ NEW Mono Medium weight
_ added style linking for all weights and styles
_ panose information for single weights
_ Italic: uni0414 De-cyr in upright shape – commissioned by mozilla, but handwritten shape will come back with Bulgarian and Serbian localized feature in 3.2 ;) –
_ zip-archives without Mac-Resources


### version/build 3.107

! line spacing !
_ added “Use Typo Metrics” to sfSelection in OS/2 table
{ OS/2 table and bbox size are equal to Fira 1.4 and 2.1
If you have any issues with increased linespacing, make sure your render engine and/or software application DOES read the OS/2 table based information and/or the bbox size }
_ panose information added to OS/2 table
_ uni0400 & uni0450 (small & capital/sc cyrillic i with grave – Bulgarian/Macedonian)
_ uni040D & uni045D (small & capital/sc cyrillic i with grave – Bulgarian/Macedonian)
_ Mono: now set as isFixedPitch
_ Mono: asterisk * uni002A now on x-height and a little bit larger
_ fixed interpolation glitches
_ New grid export parameters for Two, Four, Eight and Hair
_ UFO source files instead of Glyphs-files


### version/build 3.106

_ aogonec uni0105 > nicer connection
_ outline corrections concerning some interpolation glitches
_ web font formats added (beta version only)


### version/build 3.105

_ smaller kerning issues
_ minor outline corrections concerning interpolation issues
_ T cedilla centered in Mono


### version/build 3.104

_ bbox resized to value of version 2.1
_ smaller kerning issues
_ all Bold weights from 160 to 158 (better results with hinting)
_ j Mono: wider shape
_ g Mono: equal style to Sans now (lower terminal)


### version/build 3.103

_ auto linespacing fixed (equal to Fira2.x)
_ ligature feature set to ‚dliv’ in Mono faces
_ new shape for J in Mono faces
_ fixed hinting bug in heavy weights
_ fixed /hcircumflex accent position in lighter weights
_ adding SmallCaps for free valuation service: adding as much composites as possible via Glyph 1.4.4 database from 3.001


### version/build 3.102

_ improved for el-cyrillic / all cases л Л л.sc
_ improved shape for alpha α, pi π, tau τ
_ minor kerning issues for punctuation
_ minor spacing issues


### version/build 3.101

_ no more empty glyphs in CYR


### version/build 3.100

! all new Italic !
! all new SmallCaps !

_ mark feature for combining accents
_ new bbox
_ new family zones
_ UC 0313 and 0314 added
_ UC 2205 added
_ similar shape for ampersand Italic and Upright
_ more common greek as mentioned in Deu. 2013
_ new shape cyrillic я (ia) lowercase
_ possibility of a stylistic set for /beta /zeta /sigma (ss10)
_ restored combing accents
_ no more hard ink-traps in M N 3 and relatives
_ fixed interpolation difficulties Cyrillic
_ added lost mu to Greek 
_ improved kerning
_ new shape for ogonek
_ improved connection of ogonek to e and U
_ fixed witdth .tf .tosf
_ removed figurespace form .tf and .tosf


### version/build 3.002

_ improved kerning
_ overlap crash fi lig fixed
_ Unicode Ranges rebuilt by Glyphs2Beta via makeOTF
_ removed helping glyphs from cyrillic part

### version/build 3.001
_ first Beta
