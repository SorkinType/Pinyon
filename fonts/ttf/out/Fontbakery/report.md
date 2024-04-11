## FontBakery report

fontbakery version: 0.11.2

<h2>Experimental checks</h2><p>These won't break the CI job for now, but will become effective after some time if nobody raises any concern.</p><details><summary><b>[1] PinyonScript-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure the font supports case swapping for all its glyphs. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/case_mapping">com.google.fonts/check/case_mapping</a>)</summary><div>


* 🔥 **FAIL** The following glyphs lack their case-swapping counterparts:

| Glyph present in the font | Missing case-swapping counterpart |
| :--- | :--- |
| U+0189: LATIN CAPITAL LETTER AFRICAN D | U+0256: LATIN SMALL LETTER D WITH TAIL |
| U+01DD: LATIN SMALL LETTER TURNED E | U+018E: LATIN CAPITAL LETTER REVERSED E |
| U+01E0: LATIN CAPITAL LETTER A WITH DOT ABOVE AND MACRON | U+01E1: LATIN SMALL LETTER A WITH DOT ABOVE AND MACRON |
| U+1E29: LATIN SMALL LETTER H WITH CEDILLA | U+1E28: LATIN CAPITAL LETTER H WITH CEDILLA |
| U+1E2D: LATIN SMALL LETTER I WITH TILDE BELOW | U+1E2C: LATIN CAPITAL LETTER I WITH TILDE BELOW |
| U+1E7D: LATIN SMALL LETTER V WITH TILDE | U+1E7C: LATIN CAPITAL LETTER V WITH TILDE |

 [code: missing-case-counterparts]
</div></details><br></div></details><h2>All other checks</h2><details><summary><b>[1] Family checks</b></summary><div><details><summary>ℹ <b>INFO:</b> Check axis ordering on the STAT table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT/axis_order">com.google.fonts/check/STAT/axis_order</a>)</summary><div>


* ℹ **INFO** All of the fonts lack a STAT table.
 [code: summary]
</div></details><br></div></details><details><summary><b>[13] PinyonScript-Regular.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, coptic, tifinagh, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: math, tai-le, old-permic, tifinagh, coptic, malayalam, canadian-aboriginal, syriac
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
35 more.

Use -F or --full-lists to disable shortening of long lists.

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `greek-ext`, `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- lslash + lslash [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0253.001

	- uni0257.001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 3	Expected: 2

	- Glyph name: A	Contours detected: 4	Expected: 2

	- Glyph name: C	Contours detected: 3	Expected: 1

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: E	Contours detected: 4	Expected: 1

	- Glyph name: F	Contours detected: 2	Expected: 1

	- Glyph name: G	Contours detected: 2	Expected: 1

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: I	Contours detected: 2	Expected: 1

	- Glyph name: J	Contours detected: 3	Expected: 1

	- 514 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 649 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 815:
less

Width = 821:
equal, notequal

Width = 755:
greater

Width = 921:
logicalnot

Width = 814:
plusminus

Width = 693:
multiply

Width = 656:
divide
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Outline Correctness Checks.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Eng (U+014A): B<<1224.5,400.0>-<1173.0,308.0>-<1099.0,178.0>>/B<<1099.0,178.0>-<1146.0,235.0>-<1225.0,329.5>> = 9.857811935296947

	* Eng (U+014A): B<<1260.5,783.0>-<1360.0,1001.0>-<1481.0,1209.0>>/B<<1481.0,1209.0>-<1405.0,1114.0>-<1341.0,1034.5>> = 8.471927180503886

	* G (U+0047): B<<930.5,597.5>-<998.0,676.0>-<1053.0,736.0>>/B<<1053.0,736.0>-<890.0,621.0>-<779.5,575.0>> = 12.285762839473662

	* Gbreve (U+011E): B<<930.5,597.5>-<998.0,676.0>-<1053.0,736.0>>/B<<1053.0,736.0>-<890.0,621.0>-<779.5,575.0>> = 12.285762839473662

	* Gcaron (U+01E6): B<<930.5,597.5>-<998.0,676.0>-<1053.0,736.0>>/B<<1053.0,736.0>-<890.0,621.0>-<779.5,575.0>> = 12.285762839473662

	* Gcircumflex (U+011C): B<<930.5,597.5>-<998.0,676.0>-<1053.0,736.0>>/B<<1053.0,736.0>-<890.0,621.0>-<779.5,575.0>> = 12.285762839473662

	* Gdotaccent (U+0120): B<<930.5,597.5>-<998.0,676.0>-<1053.0,736.0>>/B<<1053.0,736.0>-<890.0,621.0>-<779.5,575.0>> = 12.285762839473662

	* H (U+0048): B<<1073.0,843.5>-<1179.0,965.0>-<1241.0,1029.0>>/B<<1241.0,1029.0>-<1141.0,967.0>-<1073.5,943.5>> = 14.110467624904652

	* Hbar (U+0126): B<<1149.5,937.0>-<1200.0,987.0>-<1241.0,1029.0>>/B<<1241.0,1029.0>-<1141.0,967.0>-<1073.5,943.5>> = 13.891364373570608

	* Hcircumflex (U+0124): B<<1073.0,843.5>-<1179.0,965.0>-<1241.0,1029.0>>/B<<1241.0,1029.0>-<1141.0,967.0>-<1073.5,943.5>> = 14.110467624904652

	* 156 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>ℹ <b>INFO:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* ℹ **INFO** Hinting filesize impact:

 |               | PinyonScript-Regular.ttf          |
 |:------------- | ---------------:|
 | Dehinted Size | 110.1kb |
 | Hinted Size   | 146.2kb   |
 | Increase      | 36.1kb      |
 | Change        | 32.8 %  |
 [code: size-impact]
</div></details><details><summary>ℹ <b>INFO:</b> EPAR table present in font? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/epar">com.google.fonts/check/epar</a>)</summary><div>


* ℹ **INFO** EPAR table not present in font. To learn more see https://github.com/fonttools/fontbakery/issues/818 [code: lacks-EPAR]
</div></details><details><summary>ℹ <b>INFO:</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/gasp">com.google.fonts/check/gasp</a>)</summary><div>


* ℹ **INFO** These are the ppm ranges declared on the gasp table:

PPM <= 65535:
	flag = 0x0F
	- Use grid-fitting
	- Use grayscale rendering
	- Use gridfitting with ClearType symmetric smoothing
	- Use smoothing along multiple axes with ClearType®
 [code: ranges]
</div></details><details><summary>ℹ <b>INFO:</b> Check for font-v versioning. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fontv">com.google.fonts/check/fontv</a>)</summary><div>


* ℹ **INFO** Version string is: "Version 1.008; ttfautohint (v1.8.4.7-5d5b)"
The version string must ideally include a git commit hash and either a "dev" or a "release" suffix such as in the example below:
"Version 1.3; git-0d08353-release" [code: bad-format]
</div></details><details><summary>ℹ <b>INFO:</b> Font contains all required tables? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/required_tables">com.google.fonts/check/required_tables</a>)</summary><div>


* ℹ **INFO** This font contains the following optional tables:

	- cvt 

	- fpgm

	- loca

	- prep

	- GPOS

	- GSUB

	- gasp [code: optional-tables]
</div></details><details><summary>ℹ <b>INFO:</b> List all superfamily filepaths (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/superfamily/list">com.google.fonts/check/superfamily/list</a>)</summary><div>


* ℹ **INFO** . [code: family-path]
</div></details><br></div></details>

### Summary

| 💔 ERROR | ☠ FATAL | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| 0 | 0 | 1 | 7 | 126 | 7 | 119 | 0 |
| 0% | 0% | 0% | 3% | 48% | 3% | 46% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **PASS**
* **DEBUG**
