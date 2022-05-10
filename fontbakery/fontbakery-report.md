## Fontbakery report

Fontbakery version: 0.8.8

<details><summary><b>[13] PinyonScript-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "Copyright 2019 The Pinyon Script Project Authors https://github.com/SorkinType/Pinyon 
  " Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Name table entries should not contain line-breaks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/line_breaks">com.google.fonts/check/name/line_breaks</a>)</summary><div>


* 🔥 **FAIL** Name entry LICENSE_DESCRIPTION on platform WINDOWS contains a line-break. [code: line-break]
</div></details><details><summary>🔥 <b>FAIL:</b> Name table records must not have trailing spaces. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/name/trailing_spaces">com.google.fonts/check/name/trailing_spaces</a>)</summary><div>


* 🔥 **FAIL** Name table record with key = (3, 1, 1033, 13) has trailing spaces that must be removed: 'Copyright [...]Pinyon 
  ' [code: trailing-space]
</div></details><details><summary>⚠ <b>WARN:</b> Description strings in the name table must not exceed 200 characters. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/description_max_length">com.google.fonts/check/name/description_max_length</a>)</summary><div>


* ⚠ **WARN** A few name table entries with ID=10 (NameID.DESCRIPTION) are longer than 200 characters. Please check whether those entries are copyright notices mistakenly stored in the description string entries by a bug in an old FontLab version. If that's the case, then such copyright notices must be removed from these entries. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Z
	* Ccedilla
	* .notdef
	* underscore and lslash
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:
	- f + f
	- f + i
	- lslash + lslash

   [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- NULL
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
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
	- And 484 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:
	* w (U+0077): L<<535.0,401.0>--<558.0,429.0>> -> L<<558.0,429.0>--<562.0,434.0>>
	* wacute (U+1E83): L<<535.0,401.0>--<558.0,429.0>> -> L<<558.0,429.0>--<562.0,434.0>>
	* wcircumflex (U+0175): L<<535.0,401.0>--<558.0,429.0>> -> L<<558.0,429.0>--<562.0,434.0>>
	* wdieresis (U+1E85): L<<535.0,401.0>--<558.0,429.0>> -> L<<558.0,429.0>--<562.0,434.0>> and wgrave (U+1E81): L<<535.0,401.0>--<558.0,429.0>> -> L<<558.0,429.0>--<562.0,434.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


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
	* Hcircumflex (U+0124): B<<1073.0,843.5>-<1179.0,965.0>-<1241.0,1029.0>>/B<<1241.0,1029.0>-<1141.0,967.0>-<1073.5,943.5>> = 14.110467624904652 and 128 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 4 | 9 | 105 | 7 | 100 | 0 |
| 0% | 2% | 4% | 47% | 3% | 44% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
