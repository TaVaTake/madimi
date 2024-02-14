## FontBakery report

fontbakery version: 0.11.1

<h2>Check results</h2><details><summary><b>[14] MadimiOne-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with ImportError: cannot import name 'unicodes_per_glyphset' from 'glyphsets.definitions' (/home/runner/work/madimi/madimi/venv-test/lib/python3.10/site-packages/glyphsets/definitions/__init__.py)
```
  File "/home/runner/work/madimi/madimi/venv-test/lib/python3.10/site-packages/fontbakery/checkrunner.py", line 170, in _exec_check
    results.extend(list(result))
  File "/home/runner/work/madimi/madimi/venv-test/lib/python3.10/site-packages/fontbakery/profiles/googlefonts.py", line 1076, in com_google_fonts_check_glyph_coverage
    glyphsets_fulfilled = get_glyphsets_fulfilled(ttFont)
  File "/home/runner/work/madimi/madimi/venv-test/lib/python3.10/site-packages/fontbakery/profiles/googlefonts_conditions.py", line 748, in get_glyphsets_fulfilled
    from glyphsets.definitions import unicodes_per_glyphset, glyphset_definitions

``` [code: failed-check]
</div></details><details><summary>💔 <b>ERROR:</b> Shapes languages in all GF glyphsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyphsets/shape_languages">com.google.fonts/check/glyphsets/shape_languages</a>)</summary><div>


* 💔 **ERROR** Failed with ImportError: cannot import name 'unicodes_per_glyphset' from 'glyphsets.definitions' (/home/runner/work/madimi/madimi/venv-test/lib/python3.10/site-packages/glyphsets/definitions/__init__.py)
```
  File "/home/runner/work/madimi/madimi/venv-test/lib/python3.10/site-packages/fontbakery/checkrunner.py", line 170, in _exec_check
    results.extend(list(result))
  File "/home/runner/work/madimi/madimi/venv-test/lib/python3.10/site-packages/fontbakery/profiles/googlefonts.py", line 3543, in com_google_fonts_check_glyphsets_shape_languages
    glyphsets_fulfilled = get_glyphsets_fulfilled(ttFont)
  File "/home/runner/work/madimi/madimi/venv-test/lib/python3.10/site-packages/fontbakery/profiles/googlefonts_conditions.py", line 748, in get_glyphsets_fulfilled
    from glyphsets.definitions import unicodes_per_glyphset, glyphset_definitions

``` [code: failed-check]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value '    ' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, cherokee, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, malayalam, coptic, syriac, canadian-aboriginal, math, tifinagh, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
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

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `greek-ext`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
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

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 7 math glyphs.
The following math glyphs have a different width, though:

Width = 474:
greater, less

Width = 517:
multiply

Width = 571:
approxequal

Width = 484:
greaterequal, lessequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check accent of Lcaron, dcaron, lcaron, tcaron (derived from com.google.fonts/check/alt_caron) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/alt_caron">com.google.fonts/check/alt_caron</a>)</summary><div>


* ⚠ **WARN** lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** tcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Outline Correctness Checks.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* quotedbl (U+0022): X=356.0,Y=702.0 (should be at cap-height 700?)

	* quotedbl (U+0022): X=122.0,Y=702.0 (should be at cap-height 700?)

	* numbersign (U+0023): X=80.0,Y=0.5 (should be at baseline 0?)

	* numbersign (U+0023): X=372.0,Y=0.5 (should be at baseline 0?)

	* dollar (U+0024): X=153.5,Y=-1.5 (should be at baseline 0?)

	* percent (U+0025): X=171.0,Y=1.5 (should be at baseline 0?)

	* percent (U+0025): X=132.0,Y=-2.0 (should be at baseline 0?)

	* quotesingle (U+0027): X=122.0,Y=702.0 (should be at cap-height 700?)

	* slash (U+002F): X=55.0,Y=-1.0 (should be at baseline 0?)

	* three (U+0033): X=136.0,Y=1.0 (should be at baseline 0?)

	* four (U+0034): X=201.5,Y=699.0 (should be at cap-height 700?)

	* J (U+004A): X=106.0,Y=-1.5 (should be at baseline 0?)

	* M (U+004D): X=455.0,Y=2.0 (should be at baseline 0?)

	* S (U+0053): X=158.0,Y=-2.0 (should be at baseline 0?)

	* backslash (U+005C): X=373.0,Y=-1.0 (should be at baseline 0?)

	* g (U+0067): X=325.0,Y=-1.0 (should be at baseline 0?)

	* h (U+0068): X=224.0,Y=499.0 (should be at x-height 500?)

	* v (U+0076): X=201.5,Y=0.5 (should be at baseline 0?)

	* v (U+0076): X=54.0,Y=499.5 (should be at x-height 500?)

	* v (U+0076): X=287.0,Y=1.0 (should be at baseline 0?)

	* w (U+0077): X=137.5,Y=499.0 (should be at x-height 500?)

	* w (U+0077): X=431.0,Y=498.0 (should be at x-height 500?)

	* x (U+0078): X=85.5,Y=-1.5 (should be at baseline 0?)

	* x (U+0078): X=389.0,Y=1.0 (should be at baseline 0?)

	* y (U+0079): X=144.5,Y=498.5 (should be at x-height 500?)

	* y (U+0079): X=465.5,Y=498.5 (should be at x-height 500?)

	* braceleft (U+007B): X=303.0,Y=702.0 (should be at cap-height 700?)

	* braceright (U+007D): X=80.0,Y=702.0 (should be at cap-height 700?)

	* sterling (U+00A3): X=474.5,Y=698.0 (should be at cap-height 700?)

	* paragraph (U+00B6): X=187.5,Y=700.5 (should be at cap-height 700?)

	* paragraph (U+00B6): X=363.0,Y=701.5 (should be at cap-height 700?)

	* Ccedilla (U+00C7): X=253.0,Y=1.0 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=419.0,Y=0.5 (should be at baseline 0?)

	* Oslash (U+00D8): X=406.5,Y=702.0 (should be at cap-height 700?)

	* germandbls (U+00DF): X=121.0,Y=702.0 (should be at cap-height 700?)

	* atilde (U+00E3): X=238.0,Y=701.5 (should be at cap-height 700?)

	* eth (U+00F0): X=489.0,Y=698.0 (should be at cap-height 700?)

	* ntilde (U+00F1): X=268.0,Y=701.5 (should be at cap-height 700?)

	* otilde (U+00F5): X=249.0,Y=701.5 (should be at cap-height 700?)

	* ccaron (U+010D): X=95.0,Y=701.0 (should be at cap-height 700?)

	* ccaron (U+010D): X=438.0,Y=701.0 (should be at cap-height 700?)

	* ecaron (U+011B): X=79.0,Y=701.0 (should be at cap-height 700?)

	* ecaron (U+011B): X=422.0,Y=701.0 (should be at cap-height 700?)

	* gbreve (U+011F): X=325.0,Y=-1.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=325.0,Y=-1.0 (should be at baseline 0?)

	* uni0123 (U+0123): X=325.0,Y=-1.0 (should be at baseline 0?)

	* lacute (U+013A): X=191.0,Y=1008.0 (should be at ascender 1010?)

	* ncaron (U+0148): X=114.0,Y=701.0 (should be at cap-height 700?)

	* ncaron (U+0148): X=457.0,Y=701.0 (should be at cap-height 700?)

	* rcaron (U+0159): X=38.0,Y=701.0 (should be at cap-height 700?)

	* rcaron (U+0159): X=381.0,Y=701.0 (should be at cap-height 700?)

	* Sacute (U+015A): X=158.0,Y=-2.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=137.0,Y=1.0 (should be at baseline 0?)

	* Scaron (U+0160): X=158.0,Y=-2.0 (should be at baseline 0?)

	* scaron (U+0161): X=63.0,Y=701.0 (should be at cap-height 700?)

	* scaron (U+0161): X=406.0,Y=701.0 (should be at cap-height 700?)

	* zcaron (U+017E): X=65.0,Y=701.0 (should be at cap-height 700?)

	* zcaron (U+017E): X=408.0,Y=701.0 (should be at cap-height 700?)

	* florin (U+0192): X=537.0,Y=698.0 (should be at cap-height 700?)

	* uni0218 (U+0218): X=158.0,Y=-2.0 (should be at baseline 0?)

	* circumflex (U+02C6): X=312.0,Y=702.0 (should be at cap-height 700?)

	* circumflex (U+02C6): X=70.0,Y=702.0 (should be at cap-height 700?)

	* caron (U+02C7): X=20.0,Y=701.0 (should be at cap-height 700?)

	* caron (U+02C7): X=363.0,Y=701.0 (should be at cap-height 700?)

	* tilde (U+02DC): X=189.0,Y=701.5 (should be at cap-height 700?)

	* tildecomb (U+0303): X=169.0,Y=701.5 (should be at cap-height 700?)

	* uni030C (U+030C): X=4.0,Y=701.0 (should be at cap-height 700?)

	* uni030C (U+030C): X=347.0,Y=701.0 (should be at cap-height 700?)

	* trademark (U+2122): X=509.0,Y=702.0 (should be at cap-height 700?)

	* trademark (U+2122): X=763.0,Y=702.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Outline Correctness Checks.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


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

	* at (U+0040) contains a short segment B<<607.5,-90.0>-<620.0,-104.0>-<620.0,-118.0>>

	* Z (U+005A) contains a short segment B<<355.0,561.0>-<368.0,568.0>-<366.0,568.0>>

	* Z (U+005A) contains a short segment B<<241.0,144.5>-<232.0,139.0>-<233.0,139.0>>

	* backslash (U+005C) contains a short segment B<<373.0,-1.0>-<375.0,-5.0>-<375.0,-9.5>>

	* backslash (U+005C) contains a short segment B<<375.0,-9.5>-<375.0,-14.0>-<375.0,-19.0>>

	* backslash (U+005C) contains a short segment B<<55.0,706.0>-<54.0,711.0>-<53.5,716.5>>

	* backslash (U+005C) contains a short segment B<<53.5,716.5>-<53.0,722.0>-<53.0,726.0>>

	* f (U+0066) contains a short segment L<<98.0,379.0>--<84.0,379.0>>

	* f (U+0066) contains a short segment L<<98.0,500.0>--<98.0,504.0>>

	* f (U+0066) contains a short segment L<<301.0,762.0>--<301.0,762.0>>

	* f (U+0066) contains a short segment B<<301.0,762.0>-<302.0,762.0>-<303.0,762.0>>

	* f (U+0066) contains a short segment B<<304.0,762.0>-<307.0,762.0>-<310.0,762.0>>

	* Eogonek (U+0118) contains a short segment L<<512.0,63.0>--<512.0,63.0>>

	* eogonek (U+0119) contains a short segment L<<443.0,74.0>--<443.0,74.0>>

	* eogonek (U+0119) contains a short segment B<<443.0,74.0>-<443.0,72.0>-<443.0,73.0>>

	* eogonek (U+0119) contains a short segment B<<443.0,72.0>-<443.0,70.0>-<443.0,68.0>>

	* eogonek (U+0119) contains a short segment L<<405.0,10.0>--<405.0,10.0>>

	* Iogonek (U+012E) contains a short segment B<<216.0,59.0>-<216.0,54.0>-<216.0,50.0>>

	* Zacute (U+0179) contains a short segment B<<355.0,561.0>-<368.0,568.0>-<366.0,568.0>>

	* Zacute (U+0179) contains a short segment B<<241.0,144.5>-<232.0,139.0>-<233.0,139.0>>

	* Zdotaccent (U+017B) contains a short segment B<<355.0,561.0>-<368.0,568.0>-<366.0,568.0>>

	* Zdotaccent (U+017B) contains a short segment B<<241.0,144.5>-<232.0,139.0>-<233.0,139.0>>

	* Zcaron (U+017D) contains a short segment B<<355.0,561.0>-<368.0,568.0>-<366.0,568.0>>

	* Zcaron (U+017D) contains a short segment B<<241.0,144.5>-<232.0,139.0>-<233.0,139.0>>

	* florin (U+0192) contains a short segment L<<193.0,379.0>--<179.0,379.0>>

	* florin (U+0192) contains a short segment L<<193.0,500.0>--<193.0,504.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<259.0,372.0>-<259.0,381.0>-<263.0,391.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<364.0,543.0>-<371.0,554.0>-<368.0,561.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<368.0,561.0>-<365.0,568.0>-<354.0,568.0>>

	* Euro (U+20AC) contains a short segment B<<48.0,333.0>-<48.0,340.0>-<48.0,347.0>>

	* Euro (U+20AC) contains a short segment B<<198.0,347.0>-<198.0,339.0>-<198.0,333.0>>

	* emptyset (U+2205) contains a short segment L<<397.0,599.0>--<392.0,599.0>>

	* notequal (U+2260) contains a short segment L<<463.0,496.0>--<471.0,496.0>>

	* fi (U+FB01) contains a short segment L<<98.0,379.0>--<84.0,379.0>>

	* fi (U+FB01) contains a short segment L<<98.0,500.0>--<98.0,504.0>>

	* fl (U+FB02) contains a short segment L<<98.0,379.0>--<84.0,379.0>>

	* fl (U+FB02) contains a short segment L<<98.0,500.0>--<98.0,504.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Outline Correctness Checks.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


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

	* trademark (U+2122): B<<159.0,617.0>-<164.0,621.0>-<177.0,623.0>>/L<<177.0,623.0>--<80.0,623.0>> = 8.746162262555211

	* z (U+007A): B<<243.0,154.0>-<225.0,126.0>-<202.0,122.0>>/L<<202.0,122.0>--<372.0,122.0>> = 9.865806943084365

	* zacute (U+017A): B<<243.0,154.0>-<225.0,126.0>-<202.0,122.0>>/L<<202.0,122.0>--<372.0,122.0>> = 9.865806943084365

	* zcaron (U+017E): B<<243.0,154.0>-<225.0,126.0>-<202.0,122.0>>/L<<202.0,122.0>--<372.0,122.0>> = 9.865806943084365

	* zdotaccent (U+017C): B<<243.0,154.0>-<225.0,126.0>-<202.0,122.0>>/L<<202.0,122.0>--<372.0,122.0>> = 9.865806943084365 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Shaping Checks.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Shaping Checks.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̣̀ į̣́ į̣̂ į̣̃ į̣̄ į̣̆ į̣̇ į̣̈ į̣̊ į̣̋ į̣̌ į̣̒ į̦̀ į̦́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers), Ekpeye (Latn, 226,000 speakers), Ebira (Latn, 2,200,000 speakers), Igbo (Latn, 27,823,640 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Sar (Latn, 500,000 speakers), Basaa (Latn, 332,940 speakers), Ejagham (Latn, 120,000 speakers), Navajo (Latn, 166,319 speakers), Fur (Latn, 1,230,163 speakers), Mundani (Latn, 34,000 speakers), Lugbara (Latn, 2,200,000 speakers), Cicipu (Latn, 44,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Yala (Latn, 200,000 speakers), Mango (Latn, 77,000 speakers), Gulay (Latn, 250,478 speakers), Koonzime (Latn, 40,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ma’di (Latn, 584,000 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Southern Kisi (Latn, 360,000 speakers), Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), South Central Banda (Latn, 244,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Dan (Latn, 1,099,244 speakers), Zapotec (Latn, 490,000 speakers), Nzakara (Latn, 50,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Kom (Latn, 360,685 speakers), Makaa (Latn, 221,000 speakers), Dii (Latn, 71,000 speakers), Bafut (Latn, 158,146 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | ☠ FATAL | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| 2 | 0 | 0 | 12 | 124 | 7 | 115 | 0 |
| 1% | 0% | 0% | 5% | 48% | 3% | 44% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
