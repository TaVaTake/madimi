## FontBakery report

fontbakery version: 0.10.1

<details><summary><b>[25] Madimi-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | **Madimi Bold** | **Madimi** |
| Subfamily Name | **Regular** | **Bold** |
| Full Name | Madimi Bold | Madimi Bold |
| Postscript Name | Madimi-Bold | Madimi-Bold |
| Typographic Family Name | **Madimi** | **N/A** |
| Typographic Subfamily Name | **Bold** | **N/A** | [code: bad-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Madimi-Bold.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1000, but got 950 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 310, but got 250 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (750) and hhea ascent (950) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.1, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that legacy accents aren't used in composite glyphs. (derived from com.google.fonts/check/legacy_accents) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/legacy_accents">com.google.fonts/check/legacy_accents</a>)</summary><div>


* 🔥 **FAIL** Legacy accent "tilde" are too narrow. [code: legacy-accents-width]
</div></details><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 220 font units wide, non-breaking space named (uni00A0) is 224 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking head.macStyle value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/mac_style">com.google.fonts/check/mac_style</a>)</summary><div>


* 🔥 **FAIL** head macStyle BOLD bit should be set. [code: bad-BOLD]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsSelection value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/fsselection">com.google.fonts/check/fsselection</a>)</summary><div>


* 🔥 **FAIL** OS/2 fsSelection REGULAR bit should be unset. [code: bad-REGULAR]
* 🔥 **FAIL** OS/2 fsSelection BOLD bit should be set. [code: bad-BOLD]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value '    ' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: coptic, syriac, canadian-aboriginal, old-permic, math, malayalam, tai-le, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2205 EMPTY SET: try adding math
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 539 among a set of 7 math glyphs.
The following math glyphs have a different width, though:

Width = 454:
greaterequal, lessequal, greater, less

Width = 477:
multiply

Width = 595:
approxequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Check accent of Lcaron, dcaron, lcaron, tcaron (derived from com.google.fonts/check/alt_caron) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/alt_caron">com.google.fonts/check/alt_caron</a>)</summary><div>


* ⚠ **WARN** lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** tcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* ampersand (U+0026) contains a short segment B<<588.0,304.0>-<588.0,300.0>-<587.5,295.5>>

	* ampersand (U+0026) contains a short segment B<<587.5,295.5>-<587.0,291.0>-<586.0,287.0>>

	* slash (U+002F) contains a short segment B<<53.0,-19.0>-<53.0,-14.0>-<53.5,-9.5>>

	* slash (U+002F) contains a short segment B<<53.5,-9.5>-<54.0,-5.0>-<55.0,-1.0>>

	* slash (U+002F) contains a short segment B<<375.0,726.0>-<375.0,722.0>-<375.0,716.5>>

	* slash (U+002F) contains a short segment B<<375.0,716.5>-<375.0,711.0>-<373.0,706.0>>

	* four (U+0034) contains a short segment L<<104.0,180.0>--<101.0,180.0>>

	* four (U+0034) contains a short segment L<<101.0,180.0>--<98.0,180.0>>

	* five (U+0035) contains a short segment B<<205.0,591.0>-<205.0,592.0>-<203.0,575.5>>

	* five (U+0035) contains a short segment B<<187.0,443.5>-<185.0,427.0>-<185.0,427.0>>

	* less (U+003C) contains a short segment L<<53.0,194.0>--<51.0,195.0>>

	* greater (U+003E) contains a short segment L<<401.0,314.0>--<403.0,313.0>>

	* at (U+0040) contains a short segment B<<597.5,-90.0>-<610.0,-104.0>-<610.0,-118.0>>

	* Z (U+005A) contains a short segment B<<60.0,49.0>-<60.0,56.0>-<61.5,62.5>>

	* Z (U+005A) contains a short segment B<<368.5,565.5>-<375.0,568.0>-<366.0,568.0>>

	* Z (U+005A) contains a short segment B<<543.0,640.0>-<543.0,632.0>-<540.0,622.5>>

	* Z (U+005A) contains a short segment B<<235.5,144.5>-<226.0,139.0>-<233.0,139.0>>

	* backslash (U+005C) contains a short segment B<<373.0,-1.0>-<375.0,-5.0>-<375.0,-9.5>>

	* backslash (U+005C) contains a short segment B<<375.0,-9.5>-<375.0,-14.0>-<375.0,-19.0>>

	* backslash (U+005C) contains a short segment B<<55.0,706.0>-<54.0,711.0>-<53.5,716.5>>

	* backslash (U+005C) contains a short segment B<<53.5,716.5>-<53.0,722.0>-<53.0,726.0>>

	* asciicircum (U+005E) contains a short segment L<<167.0,428.0>--<168.0,430.0>>

	* f (U+0066) contains a short segment L<<98.0,500.0>--<98.0,504.0>>

	* z (U+007A) contains a short segment B<<34.0,43.0>-<34.0,48.0>-<36.0,56.0>>

	* z (U+007A) contains a short segment B<<238.0,374.0>-<247.0,378.0>-<245.0,378.0>>

	* z (U+007A) contains a short segment B<<204.0,122.5>-<199.0,122.0>-<206.0,122.0>>

	* Zacute (U+0179) contains a short segment B<<60.0,49.0>-<60.0,56.0>-<61.5,62.5>>

	* Zacute (U+0179) contains a short segment B<<368.5,565.5>-<375.0,568.0>-<366.0,568.0>>

	* Zacute (U+0179) contains a short segment B<<543.0,640.0>-<543.0,632.0>-<540.0,622.5>>

	* Zacute (U+0179) contains a short segment B<<235.5,144.5>-<226.0,139.0>-<233.0,139.0>>

	* zacute (U+017A) contains a short segment B<<34.0,43.0>-<34.0,48.0>-<36.0,56.0>>

	* zacute (U+017A) contains a short segment B<<238.0,374.0>-<247.0,378.0>-<245.0,378.0>>

	* zacute (U+017A) contains a short segment B<<204.0,122.5>-<199.0,122.0>-<206.0,122.0>>

	* Zdotaccent (U+017B) contains a short segment B<<60.0,49.0>-<60.0,56.0>-<61.5,62.5>>

	* Zdotaccent (U+017B) contains a short segment B<<368.5,565.5>-<375.0,568.0>-<366.0,568.0>>

	* Zdotaccent (U+017B) contains a short segment B<<543.0,640.0>-<543.0,632.0>-<540.0,622.5>>

	* Zdotaccent (U+017B) contains a short segment B<<235.5,144.5>-<226.0,139.0>-<233.0,139.0>>

	* zdotaccent (U+017C) contains a short segment B<<34.0,43.0>-<34.0,48.0>-<36.0,56.0>>

	* zdotaccent (U+017C) contains a short segment B<<238.0,374.0>-<247.0,378.0>-<245.0,378.0>>

	* zdotaccent (U+017C) contains a short segment B<<204.0,122.5>-<199.0,122.0>-<206.0,122.0>>

	* Zcaron (U+017D) contains a short segment B<<60.0,49.0>-<60.0,56.0>-<61.5,62.5>>

	* Zcaron (U+017D) contains a short segment B<<368.5,565.5>-<375.0,568.0>-<366.0,568.0>>

	* Zcaron (U+017D) contains a short segment B<<543.0,640.0>-<543.0,632.0>-<540.0,622.5>>

	* Zcaron (U+017D) contains a short segment B<<235.5,144.5>-<226.0,139.0>-<233.0,139.0>>

	* zcaron (U+017E) contains a short segment B<<34.0,43.0>-<34.0,48.0>-<36.0,56.0>>

	* zcaron (U+017E) contains a short segment B<<238.0,374.0>-<247.0,378.0>-<245.0,378.0>>

	* zcaron (U+017E) contains a short segment B<<204.0,122.5>-<199.0,122.0>-<206.0,122.0>>

	* florin (U+0192) contains a short segment L<<193.0,379.0>--<179.0,379.0>>

	* florin (U+0192) contains a short segment L<<193.0,500.0>--<193.0,504.0>>

	* Euro (U+20AC) contains a short segment B<<48.0,365.0>-<48.0,374.0>-<48.0,382.0>>

	* Euro (U+20AC) contains a short segment L<<198.0,382.0>--<198.0,378.0>>

	* infinity (U+221E) contains a short segment B<<431.0,220.0>-<429.0,218.0>-<427.0,216.0>>

	* notequal (U+2260) contains a short segment L<<454.0,438.0>--<461.0,438.0>>

	* lessequal (U+2264) contains a short segment L<<53.0,300.0>--<51.0,301.0>>

	* greaterequal (U+2265) contains a short segment L<<401.0,420.0>--<403.0,419.0>>

	* fi (U+FB01) contains a short segment L<<98.0,379.0>--<84.0,379.0>>

	* fi (U+FB01) contains a short segment L<<98.0,500.0>--<98.0,504.0>>

	* fl (U+FB02) contains a short segment L<<98.0,500.0>--<98.0,504.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* asciicircum (U+005E): L<<19.0,132.0>--<167.0,428.0>> -> L<<167.0,428.0>--<168.0,430.0>>

	* asciicircum (U+005E): L<<286.0,430.0>--<287.0,428.0>> -> L<<287.0,428.0>--<435.0,132.0>>

	* four (U+0034): L<<104.0,180.0>--<101.0,180.0>> -> L<<101.0,180.0>--<98.0,180.0>>

	* four (U+0034): L<<330.0,180.0>--<104.0,180.0>> -> L<<104.0,180.0>--<101.0,180.0>>

	* greater (U+003E): L<<105.0,462.0>--<401.0,314.0>> -> L<<401.0,314.0>--<403.0,313.0>>

	* greater (U+003E): L<<403.0,195.0>--<401.0,194.0>> -> L<<401.0,194.0>--<105.0,46.0>>

	* greaterequal (U+2265): L<<105.0,568.0>--<401.0,420.0>> -> L<<401.0,420.0>--<403.0,419.0>>

	* greaterequal (U+2265): L<<403.0,301.0>--<401.0,300.0>> -> L<<401.0,300.0>--<105.0,152.0>>

	* less (U+003C): L<<349.0,46.0>--<53.0,194.0>> -> L<<53.0,194.0>--<51.0,195.0>>

	* less (U+003C): L<<51.0,313.0>--<53.0,314.0>> -> L<<53.0,314.0>--<349.0,462.0>>

	* lessequal (U+2264): L<<349.0,152.0>--<53.0,300.0>> -> L<<53.0,300.0>--<51.0,301.0>>

	* lessequal (U+2264): L<<51.0,419.0>--<53.0,420.0>> -> L<<53.0,420.0>--<349.0,568.0>>

	* notequal (U+2260): L<<217.0,84.0>--<206.0,68.0>> -> L<<206.0,68.0>--<166.0,9.0>>

	* oslash (U+00F8): L<<169.0,190.0>--<171.0,193.0>> -> L<<171.0,193.0>--<312.0,401.0>>

	* two (U+0032): L<<210.0,150.0>--<210.0,148.0>> -> L<<210.0,148.0>--<209.0,119.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* b (U+0062): B<<198.5,490.5>-<195.0,472.0>-<188.0,451.0>>/B<<188.0,451.0>-<207.0,482.0>-<240.5,495.0>> = 13.069317896282163

	* d (U+0064): B<<325.0,495.0>-<358.0,482.0>-<377.0,451.0>>/B<<377.0,451.0>-<370.0,472.0>-<366.5,490.5>> = 13.069317896282163

	* dcaron (U+010F): B<<325.0,495.0>-<358.0,482.0>-<377.0,451.0>>/B<<377.0,451.0>-<370.0,472.0>-<366.5,490.5>> = 13.069317896282163

	* dcroat (U+0111): B<<325.0,495.0>-<358.0,482.0>-<377.0,451.0>>/B<<377.0,451.0>-<370.0,472.0>-<366.5,490.5>> = 13.069317896282163

	* h (U+0068): B<<199.0,523.0>-<193.0,497.0>-<179.0,469.0>>/B<<179.0,469.0>-<196.0,490.0>-<224.0,499.0>> = 12.425942865427455

	* hbar (U+0127): B<<199.0,523.0>-<193.0,497.0>-<179.0,469.0>>/B<<179.0,469.0>-<196.0,490.0>-<224.0,499.0>> = 12.425942865427455

	* p (U+0070): B<<237.5,7.0>-<204.0,22.0>-<185.0,53.0>>/B<<185.0,53.0>-<192.0,33.0>-<195.5,14.0>> = 12.21422050001543

	* q (U+0071): B<<366.5,14.0>-<370.0,33.0>-<377.0,53.0>>/B<<377.0,53.0>-<358.0,22.0>-<325.0,7.0>> = 12.21422050001543

	* thorn (U+00FE): B<<240.5,7.0>-<207.0,22.0>-<188.0,53.0>>/B<<188.0,53.0>-<195.0,33.0>-<198.5,14.0>> = 12.21422050001543

	* z (U+007A): B<<371.0,345.0>-<360.0,330.0>-<361.0,331.0>>/L<<361.0,331.0>--<243.0,154.0>> = 11.309932474020227

	* zacute (U+017A): B<<371.0,345.0>-<360.0,330.0>-<361.0,331.0>>/L<<361.0,331.0>--<243.0,154.0>> = 11.309932474020227

	* zcaron (U+017E): B<<371.0,345.0>-<360.0,330.0>-<361.0,331.0>>/L<<361.0,331.0>--<243.0,154.0>> = 11.309932474020227

	* zdotaccent (U+017C): B<<371.0,345.0>-<360.0,330.0>-<361.0,331.0>>/L<<361.0,331.0>--<243.0,154.0>> = 11.309932474020227 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* T (U+0054): L<<202.0,41.0>--<201.0,509.0>>

	* Tcaron (U+0164): L<<202.0,41.0>--<201.0,509.0>>

	* uni021A (U+021A): L<<202.0,41.0>--<201.0,509.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̣̀ į̣́ į̣̂ į̣̃ į̣̄ į̣̆ į̣̇ į̣̈ į̣̊ į̣̋ į̣̌ į̣̒ į̦̀ į̦́

Your font fully covers the following languages that require the soft-dotted feature: Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers), Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Navajo (Latn, 166,319 speakers), Basaa (Latn, 332,940 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Aghem (Latn, 38,843 speakers), Kom (Latn, 360,685 speakers), Ma’di (Latn, 584,000 speakers), Lugbara (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Ejagham (Latn, 120,000 speakers), Nateni (Latn, 100,000 speakers), Avokaya (Latn, 100,000 speakers), Dan (Latn, 1,099,244 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 11 | 14 | 123 | 7 | 97 | 0 |
| 0% | 4% | 6% | 49% | 3% | 38% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
