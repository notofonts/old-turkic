## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[8] NotoSansOldTurkic-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansOldTurkic/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, coptic, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, old-permic, math, hebrew, duployan, tifinagh, todhri, malayalam, syriac, canadian-aboriginal, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: batak, javanese, psalter-pahlavi, siddham, tai-le, khmer, mongolian, lao, sharada, tibetan, meetei-mayek, new-tai-lue, tai-viet, thai, avestan, thaana, takri, rejang, cham, dogra, mandaic, masaram-gondi, telugu, grantha, khudawadi, tirhuta, malayalam, syriac, tagbanwa, gunjala-gondi, buginese, brahmi, manichaean, tai-tham, kayah-li, oriya, arabic, kharoshthi, hebrew, bengali, duployan, tagalog, bhaiksuki, buhid, myanmar, syloti-nagri, pahawh-hmong, zanabazar-square, sundanese, modi, devanagari, warang-citi, khojki, hanunoo, kaithi, kannada, mahajani, saurashtra, old-hungarian, tamil, sinhala, newa, lepcha, chakma, limbu, nko, tifinagh, yi, balinese, gurmukhi, sogdian, gujarati, phags-pa, hanifi-rohingya</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>old-turkic</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Kaska (Latn, 125 speakers), Sar (Latn, 500,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Lugbara (Latn, 2,200,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Dan (Latn, 1,099,244 speakers), South Central Banda (Latn, 244,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Bafut (Latn, 158,146 speakers), Navajo (Latn, 166,319 speakers), Belarusian (Cyrl, 10,064,517 speakers), Vute (Latn, 21,000 speakers), Zapotec (Latn, 490,000 speakers), Mango (Latn, 77,000 speakers), Dii (Latn, 71,000 speakers), Ebira (Latn, 2,200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Avokaya (Latn, 100,000 speakers), Han (Latn, 6 speakers), Ekpeye (Latn, 226,000 speakers), Basaa (Latn, 332,940 speakers), Ma’di (Latn, 584,000 speakers), Nateni (Latn, 100,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Mfumte (Latn, 79,000 speakers), Mundani (Latn, 34,000 speakers), Ejagham (Latn, 120,000 speakers), Nzakara (Latn, 50,000 speakers), Gulay (Latn, 250,478 speakers), Fur (Latn, 1,230,163 speakers), Heiltsuk (Latn, 300 speakers), Makaa (Latn, 221,000 speakers), Southern Kisi (Latn, 360,000 speakers), Igbo (Latn, 27,823,640 speakers), Yala (Latn, 200,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Cicipu (Latn, 44,000 speakers), Koonzime (Latn, 40,000 speakers), Kom (Latn, 360,685 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have segments which seem very short:</p>
<pre><code>* u10C11 (U+10C11) contains a short segment L&lt;&lt;479.0,180.0&gt;--&lt;479.0,184.0&gt;&gt;

* u10C11 (U+10C11) contains a short segment L&lt;&lt;307.0,345.0&gt;--&lt;307.0,350.0&gt;&gt;

* u10C11 (U+10C11) contains a short segment L&lt;&lt;479.0,530.0&gt;--&lt;479.0,534.0&gt;&gt;

* u10C11 (U+10C11) contains a short segment L&lt;&lt;599.0,534.0&gt;--&lt;599.0,530.0&gt;&gt;

* u10C11 (U+10C11) contains a short segment L&lt;&lt;429.0,350.0&gt;--&lt;429.0,346.0&gt;&gt;

* u10C11 (U+10C11) contains a short segment L&lt;&lt;599.0,184.0&gt;--&lt;599.0,180.0&gt;&gt;

* u10C11 (U+10C11) contains a short segment L&lt;&lt;192.0,180.0&gt;--&lt;192.0,184.0&gt;&gt;

* u10C11 (U+10C11) contains a short segment L&lt;&lt;20.0,345.0&gt;--&lt;20.0,350.0&gt;&gt;

* u10C11 (U+10C11) contains a short segment L&lt;&lt;192.0,530.0&gt;--&lt;192.0,534.0&gt;&gt;

* u10C11 (U+10C11) contains a short segment L&lt;&lt;312.0,534.0&gt;--&lt;312.0,530.0&gt;&gt;

* u10C11 (U+10C11) contains a short segment L&lt;&lt;142.0,350.0&gt;--&lt;142.0,346.0&gt;&gt;

* u10C11 (U+10C11) contains a short segment L&lt;&lt;312.0,184.0&gt;--&lt;312.0,180.0&gt;&gt;

* u10C12 (U+10C12) contains a short segment L&lt;&lt;307.0,235.0&gt;--&lt;307.0,240.0&gt;&gt;

* u10C12 (U+10C12) contains a short segment L&lt;&lt;540.0,481.0&gt;--&lt;540.0,485.0&gt;&gt;

* u10C12 (U+10C12) contains a short segment L&lt;&lt;660.0,485.0&gt;--&lt;660.0,481.0&gt;&gt;

* u10C12 (U+10C12) contains a short segment L&lt;&lt;429.0,240.0&gt;--&lt;429.0,236.0&gt;&gt;

* u10C12 (U+10C12) contains a short segment L&lt;&lt;20.0,235.0&gt;--&lt;20.0,240.0&gt;&gt;

* u10C12 (U+10C12) contains a short segment L&lt;&lt;253.0,481.0&gt;--&lt;253.0,485.0&gt;&gt;

* u10C12 (U+10C12) contains a short segment L&lt;&lt;373.0,485.0&gt;--&lt;373.0,481.0&gt;&gt;

* u10C12 (U+10C12) contains a short segment L&lt;&lt;142.0,240.0&gt;--&lt;142.0,236.0&gt;&gt;

* u10C47 (U+10C47) contains a short segment B&lt;&lt;486.0,543.0&gt;-&lt;486.0,548.0&gt;-&lt;485.5,554.0&gt;&gt;

* u10C47 (U+10C47) contains a short segment B&lt;&lt;485.5,554.0&gt;-&lt;485.0,560.0&gt;-&lt;485.0,566.0&gt;&gt;

* u10C47 (U+10C47) contains a short segment B&lt;&lt;594.5,457.0&gt;-&lt;598.0,443.0&gt;-&lt;598.0,443.0&gt;&gt;

* u10C48 (U+10C48) contains a short segment L&lt;&lt;599.0,144.0&gt;--&lt;603.0,144.0&gt;&gt;

* u10C48 (U+10C48) contains a short segment L&lt;&lt;603.0,569.0&gt;--&lt;599.0,569.0&gt;&gt;

* u10C48 (U+10C48) contains a short segment L&lt;&lt;188.0,150.0&gt;--&lt;192.0,150.0&gt;&gt;

* u10C48 (U+10C48) contains a short segment L&lt;&lt;192.0,563.0&gt;--&lt;188.0,563.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;177.0,626.0&gt;--&lt;173.0,626.0&gt;&gt;

* M (U+004D) contains a short segment L&lt;&lt;450.0,129.0&gt;--&lt;454.0,129.0&gt;&gt;

* N (U+004E) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* N (U+004E) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* Nacute (U+0143) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* Nacute (U+0143) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* Ncaron (U+0147) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* Ncaron (U+0147) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* uni0145 (U+0145) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* uni0145 (U+0145) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* Ntilde (U+00D1) contains a short segment L&lt;&lt;176.0,593.0&gt;--&lt;172.0,593.0&gt;&gt;

* Ntilde (U+00D1) contains a short segment L&lt;&lt;582.0,123.0&gt;--&lt;586.0,123.0&gt;&gt;

* Q (U+0051) contains a short segment B&lt;&lt;416.0,-9.0&gt;-&lt;410.0,-9.0&gt;-&lt;403.5,-9.5&gt;&gt;

* Q (U+0051) contains a short segment B&lt;&lt;403.5,-9.5&gt;-&lt;397.0,-10.0&gt;-&lt;391.0,-10.0&gt;&gt;

* Uogonek (U+0172) contains a short segment B&lt;&lt;539.5,-158.5&gt;-&lt;551.0,-156.0&gt;-&lt;559.0,-155.0&gt;&gt;

* W (U+0057) contains a short segment B&lt;&lt;468.0,577.5&gt;-&lt;463.0,600.0&gt;-&lt;461.0,609.0&gt;&gt;

* Wacute (U+1E82) contains a short segment B&lt;&lt;468.0,577.5&gt;-&lt;463.0,600.0&gt;-&lt;461.0,609.0&gt;&gt;

* Wcircumflex (U+0174) contains a short segment B&lt;&lt;468.0,577.5&gt;-&lt;463.0,600.0&gt;-&lt;461.0,609.0&gt;&gt;

* Wdieresis (U+1E84) contains a short segment B&lt;&lt;468.0,577.5&gt;-&lt;463.0,600.0&gt;-&lt;461.0,609.0&gt;&gt;

* Wgrave (U+1E80) contains a short segment B&lt;&lt;468.0,577.5&gt;-&lt;463.0,600.0&gt;-&lt;461.0,609.0&gt;&gt;

* a (U+0061) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* aacute (U+00E1) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* abreve (U+0103) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* acircumflex (U+00E2) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* adieresis (U+00E4) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* agrave (U+00E0) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* amacron (U+0101) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* aogonek (U+0105) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* aring (U+00E5) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* at (U+0040) contains a short segment B&lt;&lt;613.0,293.0&gt;-&lt;612.0,275.0&gt;-&lt;612.0,267.5&gt;&gt;

* at (U+0040) contains a short segment B&lt;&lt;612.0,267.5&gt;-&lt;612.0,260.0&gt;-&lt;612.0,257.0&gt;&gt;

* atilde (U+00E3) contains a short segment L&lt;&lt;399.0,76.0&gt;--&lt;395.0,76.0&gt;&gt;

* d (U+0064) contains a short segment L&lt;&lt;446.0,72.0&gt;--&lt;442.0,72.0&gt;&gt;

* dcaron (U+010F) contains a short segment L&lt;&lt;446.0,72.0&gt;--&lt;442.0,72.0&gt;&gt;

* dcroat (U+0111) contains a short segment L&lt;&lt;445.0,72.0&gt;--&lt;441.0,72.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;184.0,390.0&gt;-&lt;183.0,380.0&gt;-&lt;183.0,371.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;183.0,371.0&gt;-&lt;183.0,362.0&gt;-&lt;183.0,352.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;183.0,352.0&gt;-&lt;183.0,343.0&gt;-&lt;183.0,332.5&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;183.0,332.5&gt;-&lt;183.0,322.0&gt;-&lt;184.0,311.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;95.0,311.0&gt;-&lt;94.0,323.0&gt;-&lt;94.0,331.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;94.0,331.0&gt;-&lt;94.0,339.0&gt;-&lt;94.0,352.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;94.0,352.0&gt;-&lt;94.0,363.0&gt;-&lt;94.5,373.5&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;94.5,373.5&gt;-&lt;95.0,384.0&gt;-&lt;95.0,390.0&gt;&gt;

* germandbls (U+00DF) contains a short segment B&lt;&lt;382.0,412.0&gt;-&lt;382.0,399.0&gt;-&lt;388.5,388.0&gt;&gt;

* m (U+006D) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* n (U+006E) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* nacute (U+0144) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* ncaron (U+0148) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* uni0146 (U+0146) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* ntilde (U+00F1) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;174.0,463.0&gt;&gt;

* p (U+0070) contains a short segment L&lt;&lt;169.0,463.0&gt;--&lt;173.0,463.0&gt;&gt;

* r (U+0072) contains a short segment L&lt;&lt;167.0,438.0&gt;--&lt;171.0,438.0&gt;&gt;

* racute (U+0155) contains a short segment L&lt;&lt;167.0,438.0&gt;--&lt;171.0,438.0&gt;&gt;

* rcaron (U+0159) contains a short segment L&lt;&lt;167.0,438.0&gt;--&lt;171.0,438.0&gt;&gt;

* trademark (U+2122) contains a short segment L&lt;&lt;386.0,633.0&gt;--&lt;382.0,633.0&gt;&gt;

* two (U+0032) contains a short segment L&lt;&lt;159.0,84.0&gt;--&lt;159.0,80.0&gt;&gt;

* u (U+0075) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* uacute (U+00FA) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* ucircumflex (U+00FB) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* udieresis (U+00FC) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* ugrave (U+00F9) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* uhungarumlaut (U+0171) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* umacron (U+016B) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* uogonek (U+0173) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;

* uring (U+016F) contains a short segment L&lt;&lt;448.0,71.0&gt;--&lt;444.0,71.0&gt;&gt;
</code></pre>
 [code: found-short-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 1 | 7 | 117 | 6 | 120 | 0 | 
| 0% | 0% | 0% | 3% | 47% | 2% | 48% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
