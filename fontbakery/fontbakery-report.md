## FontBakery report

fontbakery version: 0.10.1

<details><summary><b>[26] Madimi-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Familyname must be unique according to namecheck.fontdata.com (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fontdata_namecheck">com.google.fonts/check/fontdata_namecheck</a>)</summary><div>


* 💔 **ERROR** Failed to access: http://namecheck.fontdata.com.
		This check relies on the external service http://namecheck.fontdata.com via the internet. While the service cannot be reached or does not respond this check is broken.

		You can exclude this check with the command line option:
		-x com.google.fonts/check/fontdata_namecheck

		Or you can wait until the service is available again.
		If the problem persists please report this issue at: https://github.com/fonttools/fontbakery/issues

		Original error message:
		<class 'requests.exceptions.ConnectionError'> [code: namecheck-service]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://openfontlicense.org" Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
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


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1010, but got 950 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 310, but got 250 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (750) and hhea ascent (950) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.1, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that legacy accents aren't used in composite glyphs. (derived from com.google.fonts/check/legacy_accents) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/legacy_accents">com.google.fonts/check/legacy_accents</a>)</summary><div>


* 🔥 **FAIL** Legacy accent "dieresis" are too narrow. [code: legacy-accents-width]
* 🔥 **FAIL** Legacy accent "dotaccent" are too narrow. [code: legacy-accents-width]
* 🔥 **FAIL** Legacy accent "cedilla" are too narrow. [code: legacy-accents-width]
* 🔥 **FAIL** Legacy accent "ogonek" are too narrow. [code: legacy-accents-width]
</div></details><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 218 font units wide, non-breaking space named (uni00A0) is 222 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
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

 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: coptic, syriac, malayalam, tifinagh, canadian-aboriginal, math, old-permic, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
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

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Racute	Contours detected: 2	Expected: 3

	- Glyph name: uni0156	Contours detected: 2	Expected: 3

	- Glyph name: Rcaron	Contours detected: 2	Expected: 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Racute	Contours detected: 2	Expected: 3

	- Glyph name: Rcaron	Contours detected: 2	Expected: 3

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uni0156	Contours detected: 2	Expected: 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 7 math glyphs.
The following math glyphs have a different width, though:

Width = 474:
less, greater

Width = 517:
multiply

Width = 571:
approxequal

Width = 484:
greaterequal, lessequal
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

	* percent (U+0025) contains a short segment B<<509.0,663.0>-<513.0,669.0>-<515.0,671.0>>

	* ampersand (U+0026) contains a short segment B<<588.0,304.0>-<588.0,300.0>-<587.5,295.5>>

	* ampersand (U+0026) contains a short segment B<<587.5,295.5>-<587.0,291.0>-<586.0,287.0>>

	* slash (U+002F) contains a short segment B<<53.0,-19.0>-<53.0,-14.0>-<53.5,-9.5>>

	* slash (U+002F) contains a short segment B<<53.5,-9.5>-<54.0,-5.0>-<55.0,-1.0>>

	* slash (U+002F) contains a short segment B<<375.0,726.0>-<375.0,722.0>-<375.0,716.5>>

	* slash (U+002F) contains a short segment B<<375.0,716.5>-<375.0,711.0>-<373.0,706.0>>

	* five (U+0035) contains a short segment B<<205.0,591.0>-<205.0,592.0>-<203.0,575.5>>

	* five (U+0035) contains a short segment B<<187.0,443.5>-<185.0,427.0>-<185.0,427.0>>

	* less (U+003C) contains a short segment L<<63.0,257.0>--<61.0,258.0>>

	* greater (U+003E) contains a short segment L<<411.0,377.0>--<413.0,376.0>>

	* at (U+0040) contains a short segment B<<607.5,-90.0>-<620.0,-104.0>-<620.0,-118.0>>

	* K (U+004B) contains a short segment B<<404.0,27.0>-<397.0,38.0>-<397.0,38.0>>

	* Z (U+005A) contains a short segment B<<355.0,561.0>-<368.0,568.0>-<366.0,568.0>>

	* Z (U+005A) contains a short segment B<<241.0,144.5>-<232.0,139.0>-<233.0,139.0>>

	* backslash (U+005C) contains a short segment B<<373.0,-1.0>-<375.0,-5.0>-<375.0,-9.5>>

	* backslash (U+005C) contains a short segment B<<375.0,-9.5>-<375.0,-14.0>-<375.0,-19.0>>

	* backslash (U+005C) contains a short segment B<<55.0,706.0>-<54.0,711.0>-<53.5,716.5>>

	* backslash (U+005C) contains a short segment B<<53.5,716.5>-<53.0,722.0>-<53.0,726.0>>

	* asciicircum (U+005E) contains a short segment L<<178.0,428.0>--<179.0,430.0>>

	* f (U+0066) contains a short segment L<<98.0,379.0>--<84.0,379.0>>

	* f (U+0066) contains a short segment L<<98.0,500.0>--<98.0,504.0>>

	* f (U+0066) contains a short segment L<<301.0,762.0>--<301.0,762.0>>

	* f (U+0066) contains a short segment B<<301.0,762.0>-<302.0,762.0>-<303.0,762.0>>

	* f (U+0066) contains a short segment B<<304.0,762.0>-<307.0,762.0>-<310.0,762.0>>

	* z (U+007A) contains a short segment B<<238.0,374.0>-<247.0,378.0>-<245.0,378.0>>

	* z (U+007A) contains a short segment B<<204.0,122.5>-<199.0,122.0>-<206.0,122.0>>

	* section (U+00A7) contains a short segment B<<428.0,171.0>-<429.0,169.0>-<429.0,168.0>>

	* section (U+00A7) contains a short segment B<<429.0,168.0>-<429.0,167.0>-<429.0,166.0>>

	* section (U+00A7) contains a short segment B<<429.0,166.0>-<429.0,163.0>-<429.0,161.0>>

	* section (U+00A7) contains a short segment B<<429.0,161.0>-<429.0,160.0>-<429.0,159.0>>

	* section (U+00A7) contains a short segment B<<429.0,159.0>-<429.0,158.0>-<429.0,160.0>>

	* section (U+00A7) contains a short segment B<<429.0,160.0>-<429.0,158.0>-<429.0,155.0>>

	* Ccedilla (U+00C7) contains a short segment B<<370.0,-8.0>-<367.0,-8.0>-<365.0,-8.0>>

	* Aogonek (U+0104) contains a short segment B<<514.0,5.0>-<509.0,-1.0>-<504.0,-6.5>>

	* Aogonek (U+0104) contains a short segment B<<504.0,-6.5>-<499.0,-12.0>-<496.0,-15.0>>

	* Aogonek (U+0104) contains a short segment B<<417.0,-24.0>-<420.0,-21.0>-<425.5,-15.5>>

	* Aogonek (U+0104) contains a short segment B<<425.5,-15.5>-<431.0,-10.0>-<438.0,-5.0>>

	* aogonek (U+0105) contains a short segment B<<257.0,-24.0>-<260.0,-21.0>-<265.0,-16.0>>

	* aogonek (U+0105) contains a short segment B<<265.0,-16.0>-<270.0,-11.0>-<276.0,-6.0>>

	* Eogonek (U+0118) contains a short segment B<<494.0,13.0>-<489.0,8.0>-<480.5,-1.5>>

	* Eogonek (U+0118) contains a short segment B<<480.5,-1.5>-<472.0,-11.0>-<468.0,-15.0>>

	* Eogonek (U+0118) contains a short segment B<<389.0,-24.0>-<393.0,-20.0>-<400.5,-13.0>>

	* Eogonek (U+0118) contains a short segment B<<400.5,-13.0>-<408.0,-6.0>-<417.0,0.0>>

	* eogonek (U+0119) contains a short segment B<<307.0,-24.0>-<310.0,-21.0>-<314.5,-16.5>>

	* eogonek (U+0119) contains a short segment B<<314.5,-16.5>-<319.0,-12.0>-<325.0,-7.0>>

	* Iogonek (U+012E) contains a short segment B<<98.0,-24.0>-<101.0,-21.0>-<106.5,-15.5>>

	* Iogonek (U+012E) contains a short segment B<<185.5,-6.0>-<180.0,-12.0>-<177.0,-15.0>>

	* iogonek (U+012F) contains a short segment L<<194.0,14.0>--<194.0,14.0>>

	* iogonek (U+012F) contains a short segment B<<194.0,14.0>-<193.0,13.0>-<192.0,12.0>>

	* iogonek (U+012F) contains a short segment B<<192.0,12.0>-<191.0,11.0>-<190.0,10.0>>

	* uni0136 (U+0136) contains a short segment B<<404.0,27.0>-<397.0,38.0>-<397.0,38.0>>

	* Uogonek (U+0172) contains a short segment B<<385.0,-24.0>-<388.0,-21.0>-<394.5,-14.0>>

	* Uogonek (U+0172) contains a short segment B<<394.5,-14.0>-<401.0,-7.0>-<410.0,2.0>>

	* uogonek (U+0173) contains a short segment B<<488.0,121.0>-<488.0,121.0>-<487.0,120.0>>

	* uogonek (U+0173) contains a short segment B<<487.0,120.0>-<486.0,116.0>-<484.0,113.0>>

	* uogonek (U+0173) contains a short segment B<<320.0,-24.0>-<324.0,-20.0>-<331.0,-13.0>>

	* Zacute (U+0179) contains a short segment B<<355.0,561.0>-<368.0,568.0>-<366.0,568.0>>

	* Zacute (U+0179) contains a short segment B<<241.0,144.5>-<232.0,139.0>-<233.0,139.0>>

	* zacute (U+017A) contains a short segment B<<238.0,374.0>-<247.0,378.0>-<245.0,378.0>>

	* zacute (U+017A) contains a short segment B<<204.0,122.5>-<199.0,122.0>-<206.0,122.0>>

	* Zdotaccent (U+017B) contains a short segment B<<355.0,561.0>-<368.0,568.0>-<366.0,568.0>>

	* Zdotaccent (U+017B) contains a short segment B<<241.0,144.5>-<232.0,139.0>-<233.0,139.0>>

	* zdotaccent (U+017C) contains a short segment B<<238.0,374.0>-<247.0,378.0>-<245.0,378.0>>

	* zdotaccent (U+017C) contains a short segment B<<204.0,122.5>-<199.0,122.0>-<206.0,122.0>>

	* Zcaron (U+017D) contains a short segment B<<355.0,561.0>-<368.0,568.0>-<366.0,568.0>>

	* Zcaron (U+017D) contains a short segment B<<241.0,144.5>-<232.0,139.0>-<233.0,139.0>>

	* zcaron (U+017E) contains a short segment B<<238.0,374.0>-<247.0,378.0>-<245.0,378.0>>

	* zcaron (U+017E) contains a short segment B<<204.0,122.5>-<199.0,122.0>-<206.0,122.0>>

	* florin (U+0192) contains a short segment L<<193.0,379.0>--<179.0,379.0>>

	* florin (U+0192) contains a short segment L<<193.0,500.0>--<193.0,504.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<259.0,372.0>-<259.0,381.0>-<263.0,391.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<364.0,543.0>-<371.0,554.0>-<368.0,561.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<368.0,561.0>-<365.0,568.0>-<354.0,568.0>>

	* Euro (U+20AC) contains a short segment B<<48.0,365.0>-<48.0,372.0>-<48.0,378.0>>

	* emptyset (U+2205) contains a short segment L<<397.0,599.0>--<392.0,599.0>>

	* notequal (U+2260) contains a short segment L<<464.0,496.0>--<471.0,496.0>>

	* lessequal (U+2264) contains a short segment L<<63.0,386.0>--<61.0,387.0>>

	* greaterequal (U+2265) contains a short segment L<<421.0,506.0>--<423.0,505.0>>

	* fi (U+FB01) contains a short segment L<<98.0,379.0>--<84.0,379.0>>

	* fi (U+FB01) contains a short segment L<<98.0,500.0>--<98.0,504.0>>

	* fl (U+FB02) contains a short segment L<<98.0,379.0>--<84.0,379.0>>

	* fl (U+FB02) contains a short segment L<<98.0,500.0>--<98.0,504.0>>

	* fl (U+FB02) contains a short segment L<<301.0,762.0>--<301.0,762.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* asciicircum (U+005E): L<<297.0,430.0>--<298.0,428.0>> -> L<<298.0,428.0>--<446.0,132.0>>

	* asciicircum (U+005E): L<<30.0,132.0>--<178.0,428.0>> -> L<<178.0,428.0>--<179.0,430.0>>

	* fl (U+FB02): L<<301.0,762.0>--<301.0,762.0>> -> L<<301.0,762.0>--<510.0,762.0>>

	* greater (U+003E): L<<115.0,525.0>--<411.0,377.0>> -> L<<411.0,377.0>--<413.0,376.0>>

	* greater (U+003E): L<<413.0,258.0>--<411.0,257.0>> -> L<<411.0,257.0>--<115.0,109.0>>

	* greaterequal (U+2265): L<<125.0,654.0>--<421.0,506.0>> -> L<<421.0,506.0>--<423.0,505.0>>

	* greaterequal (U+2265): L<<423.0,387.0>--<421.0,386.0>> -> L<<421.0,386.0>--<125.0,238.0>>

	* less (U+003C): L<<359.0,109.0>--<63.0,257.0>> -> L<<63.0,257.0>--<61.0,258.0>>

	* less (U+003C): L<<61.0,376.0>--<63.0,377.0>> -> L<<63.0,377.0>--<359.0,525.0>>

	* lessequal (U+2264): L<<359.0,238.0>--<63.0,386.0>> -> L<<63.0,386.0>--<61.0,387.0>>

	* lessequal (U+2264): L<<61.0,505.0>--<63.0,506.0>> -> L<<63.0,506.0>--<359.0,654.0>>

	* notequal (U+2260): L<<227.0,142.0>--<216.0,126.0>> -> L<<216.0,126.0>--<176.0,67.0>>

	* two (U+0032): L<<210.0,150.0>--<210.0,148.0>> -> L<<210.0,148.0>--<209.0,119.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Lcaron (U+013D): B<<377.5,549.0>-<375.0,556.0>-<376.0,572.0>>/B<<376.0,572.0>-<376.0,569.0>-<383.5,611.5>> = 3.576334374997269

	* b (U+0062): B<<198.5,490.5>-<195.0,472.0>-<188.0,451.0>>/B<<188.0,451.0>-<207.0,482.0>-<240.5,495.0>> = 13.069317896282163

	* d (U+0064): B<<325.0,495.0>-<358.0,482.0>-<377.0,451.0>>/B<<377.0,451.0>-<370.0,472.0>-<366.5,490.5>> = 13.069317896282163

	* dcaron (U+010F): B<<325.0,495.0>-<358.0,482.0>-<377.0,451.0>>/B<<377.0,451.0>-<370.0,472.0>-<366.5,490.5>> = 13.069317896282163

	* dcaron (U+010F): B<<536.5,549.0>-<534.0,556.0>-<535.0,572.0>>/B<<535.0,572.0>-<535.0,569.0>-<542.5,611.5>> = 3.576334374997269

	* dcroat (U+0111): B<<325.0,495.0>-<358.0,482.0>-<377.0,451.0>>/B<<377.0,451.0>-<370.0,472.0>-<366.5,490.5>> = 13.069317896282163

	* h (U+0068): B<<199.0,523.0>-<193.0,497.0>-<179.0,469.0>>/B<<179.0,469.0>-<196.0,490.0>-<224.0,499.0>> = 12.425942865427455

	* hbar (U+0127): B<<199.0,523.0>-<193.0,497.0>-<179.0,469.0>>/B<<179.0,469.0>-<196.0,490.0>-<224.0,499.0>> = 12.425942865427455

	* p (U+0070): B<<237.5,7.0>-<204.0,22.0>-<185.0,53.0>>/B<<185.0,53.0>-<192.0,33.0>-<195.5,14.0>> = 12.21422050001543

	* q (U+0071): B<<366.5,14.0>-<370.0,33.0>-<377.0,53.0>>/B<<377.0,53.0>-<358.0,22.0>-<325.0,7.0>> = 12.21422050001543

	* thorn (U+00FE): B<<240.5,7.0>-<207.0,22.0>-<188.0,53.0>>/B<<188.0,53.0>-<195.0,33.0>-<198.5,14.0>> = 12.21422050001543

	* trademark (U+2122): B<<159.0,617.0>-<164.0,621.0>-<177.0,623.0>>/L<<177.0,623.0>--<80.0,623.0>> = 8.746162262555211 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* T (U+0054): L<<202.0,41.0>--<201.0,509.0>>

	* Tcaron (U+0164): L<<202.0,41.0>--<201.0,509.0>>

	* trademark (U+2122): L<<679.0,551.0>--<678.0,365.0>>

	* uni021A (U+021A): L<<202.0,41.0>--<201.0,509.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̣̀ į̣́ į̣̂ į̣̃ į̣̄ į̣̆ į̣̇ į̣̈ į̣̊ į̣̋ į̣̌ į̣̒ į̦̀ į̦́

Your font fully covers the following languages that require the soft-dotted feature: Ebira (Latn, 2,200,000 speakers), Igbo (Latn, 27,823,640 speakers), Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Kom (Latn, 360,685 speakers), Lugbara (Latn, 2,200,000 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Ejagham (Latn, 120,000 speakers), Navajo (Latn, 166,319 speakers), Koonzime (Latn, 40,000 speakers), Dan (Latn, 1,099,244 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Avokaya (Latn, 100,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Nateni (Latn, 100,000 speakers), Basaa (Latn, 332,940 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 1 | 11 | 14 | 123 | 7 | 96 | 0 |
| 0% | 4% | 6% | 49% | 3% | 38% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
