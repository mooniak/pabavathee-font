## FontBakery report

fontbakery version: 0.12.6



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] Pabavathee-Regular.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Validate location, size and resolution of article images. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[19] Pabavathee-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Font contains '.notdef' as its first glyph? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The '.notdef' glyph should contain a drawing, but it is blank.</p>
 [code: notdef-is-blank]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Font contains glyphs for whitespace characters? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Whitespace glyph missing for codepoint 0x00A0.</p>
 [code: missing-whitespace-glyph-0x00A0]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>No GF glyphset was found to be supported &gt;80%, so language shaping support couldn't get checked.</p>
 [code: no-glyphset-supported]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.copyright.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2019 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2002 Pushpanada Eknayaka, 2024 Mooniak. All rights reserved.&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x0022 (QUOTATION MARK)


- 0x0023 (NUMBER SIGN)


- 0x0024 (DOLLAR SIGN)


- 0x0026 (AMPERSAND)


- 0x0027 (APOSTROPHE)


- 0x003C (LESS-THAN SIGN)


- 0x003E (GREATER-THAN SIGN)


- 0x0040 (COMMERCIAL AT)


- 0x0041 (LATIN CAPITAL LETTER A)


- 0x0042 (LATIN CAPITAL LETTER B)


- 0x0043 (LATIN CAPITAL LETTER C)


- 0x0044 (LATIN CAPITAL LETTER D)


- 0x0045 (LATIN CAPITAL LETTER E)


- 0x0046 (LATIN CAPITAL LETTER F)


- 0x0047 (LATIN CAPITAL LETTER G)


- 0x0048 (LATIN CAPITAL LETTER H)


- 0x0049 (LATIN CAPITAL LETTER I)


- 0x004A (LATIN CAPITAL LETTER J)


- 0x004B (LATIN CAPITAL LETTER K)


- 0x004C (LATIN CAPITAL LETTER L)


- 0x004D (LATIN CAPITAL LETTER M)


- 0x004E (LATIN CAPITAL LETTER N)


- 0x004F (LATIN CAPITAL LETTER O)


- 0x0050 (LATIN CAPITAL LETTER P)


- 0x0051 (LATIN CAPITAL LETTER Q)


- 0x0052 (LATIN CAPITAL LETTER R)


- 0x0053 (LATIN CAPITAL LETTER S)


- 0x0054 (LATIN CAPITAL LETTER T)


- 0x0055 (LATIN CAPITAL LETTER U)


- 0x0056 (LATIN CAPITAL LETTER V)


- 0x0057 (LATIN CAPITAL LETTER W)


- 0x0058 (LATIN CAPITAL LETTER X)


- 0x0059 (LATIN CAPITAL LETTER Y)


- 0x005A (LATIN CAPITAL LETTER Z)


- 0x005B (LEFT SQUARE BRACKET)


- 0x005C (REVERSE SOLIDUS)


- 0x005D (RIGHT SQUARE BRACKET)


- 0x005E (CIRCUMFLEX ACCENT)


- 0x005F (LOW LINE)


- 0x0060 (GRAVE ACCENT)


- 0x0061 (LATIN SMALL LETTER A)


- 0x0062 (LATIN SMALL LETTER B)


- 0x0063 (LATIN SMALL LETTER C)


- 0x0064 (LATIN SMALL LETTER D)


- 0x0065 (LATIN SMALL LETTER E)


- 0x0066 (LATIN SMALL LETTER F)


- 0x0067 (LATIN SMALL LETTER G)


- 0x0068 (LATIN SMALL LETTER H)


- 0x0069 (LATIN SMALL LETTER I)


- 0x006A (LATIN SMALL LETTER J)


- 0x006B (LATIN SMALL LETTER K)


- 0x006C (LATIN SMALL LETTER L)


- 0x006D (LATIN SMALL LETTER M)


- 0x006E (LATIN SMALL LETTER N)


- 0x006F (LATIN SMALL LETTER O)


- 0x0070 (LATIN SMALL LETTER P)


- 0x0071 (LATIN SMALL LETTER Q)


- 0x0072 (LATIN SMALL LETTER R)


- 0x0073 (LATIN SMALL LETTER S)


- 0x0074 (LATIN SMALL LETTER T)


- 0x0075 (LATIN SMALL LETTER U)


- 0x0076 (LATIN SMALL LETTER V)


- 0x0077 (LATIN SMALL LETTER W)


- 0x0078 (LATIN SMALL LETTER X)


- 0x0079 (LATIN SMALL LETTER Y)


- 0x007A (LATIN SMALL LETTER Z)


- 0x007B (LEFT CURLY BRACKET)


- 0x007C (VERTICAL LINE)


- 0x007D (RIGHT CURLY BRACKET)


- 0x007E (TILDE)


- 0x00A0 (NO-BREAK SPACE)


- 0x00A1 (INVERTED EXCLAMATION MARK)


- 0x00A2 (CENT SIGN)


- 0x00A3 (POUND SIGN)


- 0x00A5 (YEN SIGN)


- 0x00A7 (SECTION SIGN)


- 0x00A8 (DIAERESIS)


- 0x00A9 (COPYRIGHT SIGN)


- 0x00AA (FEMININE ORDINAL INDICATOR)


- 0x00AB (LEFT-POINTING DOUBLE ANGLE QUOTATION MARK)


- 0x00AE (REGISTERED SIGN)


- 0x00AF (MACRON)


- 0x00B0 (DEGREE SIGN)


- 0x00B4 (ACUTE ACCENT)


- 0x00B6 (PILCROW SIGN)


- 0x00B7 (MIDDLE DOT)


- 0x00B8 (CEDILLA)


- 0x00BA (MASCULINE ORDINAL INDICATOR)


- 0x00BB (RIGHT-POINTING DOUBLE ANGLE QUOTATION MARK)


- 0x00BF (INVERTED QUESTION MARK)


- 0x00C0 (LATIN CAPITAL LETTER A WITH GRAVE)


- 0x00C1 (LATIN CAPITAL LETTER A WITH ACUTE)


- 0x00C2 (LATIN CAPITAL LETTER A WITH CIRCUMFLEX)


- 0x00C3 (LATIN CAPITAL LETTER A WITH TILDE)


- 0x00C4 (LATIN CAPITAL LETTER A WITH DIAERESIS)


- 0x00C5 (LATIN CAPITAL LETTER A WITH RING ABOVE)


- 0x00C6 (LATIN CAPITAL LETTER AE)


- 0x00C7 (LATIN CAPITAL LETTER C WITH CEDILLA)


- 0x00C8 (LATIN CAPITAL LETTER E WITH GRAVE)


- 0x00C9 (LATIN CAPITAL LETTER E WITH ACUTE)


- 0x00CA (LATIN CAPITAL LETTER E WITH CIRCUMFLEX)


- 0x00CB (LATIN CAPITAL LETTER E WITH DIAERESIS)


- 0x00CC (LATIN CAPITAL LETTER I WITH GRAVE)


- 0x00CD (LATIN CAPITAL LETTER I WITH ACUTE)


- 0x00CE (LATIN CAPITAL LETTER I WITH CIRCUMFLEX)


- 0x00CF (LATIN CAPITAL LETTER I WITH DIAERESIS)


- 0x00D0 (LATIN CAPITAL LETTER ETH)


- 0x00D1 (LATIN CAPITAL LETTER N WITH TILDE)


- 0x00D2 (LATIN CAPITAL LETTER O WITH GRAVE)


- 0x00D3 (LATIN CAPITAL LETTER O WITH ACUTE)


- 0x00D4 (LATIN CAPITAL LETTER O WITH CIRCUMFLEX)


- 0x00D5 (LATIN CAPITAL LETTER O WITH TILDE)


- 0x00D6 (LATIN CAPITAL LETTER O WITH DIAERESIS)


- 0x00D7 (MULTIPLICATION SIGN)


- 0x00D8 (LATIN CAPITAL LETTER O WITH STROKE)


- 0x00D9 (LATIN CAPITAL LETTER U WITH GRAVE)


- 0x00DA (LATIN CAPITAL LETTER U WITH ACUTE)


- 0x00DB (LATIN CAPITAL LETTER U WITH CIRCUMFLEX)


- 0x00DC (LATIN CAPITAL LETTER U WITH DIAERESIS)


- 0x00DD (LATIN CAPITAL LETTER Y WITH ACUTE)


- 0x00DE (LATIN CAPITAL LETTER THORN)


- 0x00DF (LATIN SMALL LETTER SHARP S)


- 0x00E0 (LATIN SMALL LETTER A WITH GRAVE)


- 0x00E1 (LATIN SMALL LETTER A WITH ACUTE)


- 0x00E2 (LATIN SMALL LETTER A WITH CIRCUMFLEX)


- 0x00E3 (LATIN SMALL LETTER A WITH TILDE)


- 0x00E4 (LATIN SMALL LETTER A WITH DIAERESIS)


- 0x00E5 (LATIN SMALL LETTER A WITH RING ABOVE)


- 0x00E6 (LATIN SMALL LETTER AE)


- 0x00E7 (LATIN SMALL LETTER C WITH CEDILLA)


- 0x00E8 (LATIN SMALL LETTER E WITH GRAVE)


- 0x00E9 (LATIN SMALL LETTER E WITH ACUTE)


- 0x00EA (LATIN SMALL LETTER E WITH CIRCUMFLEX)


- 0x00EB (LATIN SMALL LETTER E WITH DIAERESIS)


- 0x00EC (LATIN SMALL LETTER I WITH GRAVE)


- 0x00ED (LATIN SMALL LETTER I WITH ACUTE)


- 0x00EE (LATIN SMALL LETTER I WITH CIRCUMFLEX)


- 0x00EF (LATIN SMALL LETTER I WITH DIAERESIS)


- 0x00F0 (LATIN SMALL LETTER ETH)


- 0x00F1 (LATIN SMALL LETTER N WITH TILDE)


- 0x00F2 (LATIN SMALL LETTER O WITH GRAVE)


- 0x00F3 (LATIN SMALL LETTER O WITH ACUTE)


- 0x00F4 (LATIN SMALL LETTER O WITH CIRCUMFLEX)


- 0x00F5 (LATIN SMALL LETTER O WITH TILDE)


- 0x00F6 (LATIN SMALL LETTER O WITH DIAERESIS)


- 0x00F7 (DIVISION SIGN)


- 0x00F8 (LATIN SMALL LETTER O WITH STROKE)


- 0x00F9 (LATIN SMALL LETTER U WITH GRAVE)


- 0x00FA (LATIN SMALL LETTER U WITH ACUTE)


- 0x00FB (LATIN SMALL LETTER U WITH CIRCUMFLEX)


- 0x00FC (LATIN SMALL LETTER U WITH DIAERESIS)


- 0x00FD (LATIN SMALL LETTER Y WITH ACUTE)


- 0x00FE (LATIN SMALL LETTER THORN)


- 0x00FF (LATIN SMALL LETTER Y WITH DIAERESIS)


- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


- 0x0104 (LATIN CAPITAL LETTER A WITH OGONEK)


- 0x0105 (LATIN SMALL LETTER A WITH OGONEK)


- 0x0106 (LATIN CAPITAL LETTER C WITH ACUTE)


- 0x0107 (LATIN SMALL LETTER C WITH ACUTE)


- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


- 0x010C (LATIN CAPITAL LETTER C WITH CARON)


- 0x010D (LATIN SMALL LETTER C WITH CARON)


- 0x010E (LATIN CAPITAL LETTER D WITH CARON)


- 0x010F (LATIN SMALL LETTER D WITH CARON)


- 0x0110 (LATIN CAPITAL LETTER D WITH STROKE)


- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


- 0x0112 (LATIN CAPITAL LETTER E WITH MACRON)


- 0x0113 (LATIN SMALL LETTER E WITH MACRON)


- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


- 0x0118 (LATIN CAPITAL LETTER E WITH OGONEK)


- 0x0119 (LATIN SMALL LETTER E WITH OGONEK)


- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


- 0x011B (LATIN SMALL LETTER E WITH CARON)


- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


- 0x011F (LATIN SMALL LETTER G WITH BREVE)


- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x012A (LATIN CAPITAL LETTER I WITH MACRON)


- 0x012B (LATIN SMALL LETTER I WITH MACRON)


- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


- 0x0130 (LATIN CAPITAL LETTER I WITH DOT ABOVE)


- 0x0131 (LATIN SMALL LETTER DOTLESS I)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0141 (LATIN CAPITAL LETTER L WITH STROKE)


- 0x0142 (LATIN SMALL LETTER L WITH STROKE)


- 0x0143 (LATIN CAPITAL LETTER N WITH ACUTE)


- 0x0144 (LATIN SMALL LETTER N WITH ACUTE)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


- 0x0148 (LATIN SMALL LETTER N WITH CARON)


- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x0152 (LATIN CAPITAL LIGATURE OE)


- 0x0153 (LATIN SMALL LIGATURE OE)


- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


- 0x0159 (LATIN SMALL LETTER R WITH CARON)


- 0x015A (LATIN CAPITAL LETTER S WITH ACUTE)


- 0x015B (LATIN SMALL LETTER S WITH ACUTE)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0160 (LATIN CAPITAL LETTER S WITH CARON)


- 0x0161 (LATIN SMALL LETTER S WITH CARON)


- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


- 0x0165 (LATIN SMALL LETTER T WITH CARON)


- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


- 0x016B (LATIN SMALL LETTER U WITH MACRON)


- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


- 0x0178 (LATIN CAPITAL LETTER Y WITH DIAERESIS)


- 0x0179 (LATIN CAPITAL LETTER Z WITH ACUTE)


- 0x017A (LATIN SMALL LETTER Z WITH ACUTE)


- 0x017B (LATIN CAPITAL LETTER Z WITH DOT ABOVE)


- 0x017C (LATIN SMALL LETTER Z WITH DOT ABOVE)


- 0x017D (LATIN CAPITAL LETTER Z WITH CARON)


- 0x017E (LATIN SMALL LETTER Z WITH CARON)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0237 (LATIN SMALL LETTER DOTLESS J)


- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


- 0x02C7 (CARON)


- 0x02D8 (BREVE)


- 0x02D9 (DOT ABOVE)


- 0x02DA (RING ABOVE)


- 0x02DB (OGONEK)


- 0x02DC (SMALL TILDE)


- 0x02DD (DOUBLE ACUTE ACCENT)


- 0x0300 (COMBINING GRAVE ACCENT)


- 0x0301 (COMBINING ACUTE ACCENT)


- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


- 0x0303 (COMBINING TILDE)


- 0x0304 (COMBINING MACRON)


- 0x0306 (COMBINING BREVE)


- 0x0307 (COMBINING DOT ABOVE)


- 0x0308 (COMBINING DIAERESIS)


- 0x030A (COMBINING RING ABOVE)


- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


- 0x030C (COMBINING CARON)


- 0x0326 (COMBINING COMMA BELOW)


- 0x0327 (COMBINING CEDILLA)


- 0x0328 (COMBINING OGONEK)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1E9E (LATIN CAPITAL LETTER SHARP S)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)


- 0x2013 (EN DASH)


- 0x2014 (EM DASH)


- 0x201A (SINGLE LOW-9 QUOTATION MARK)


- 0x201E (DOUBLE LOW-9 QUOTATION MARK)


- 0x2022 (BULLET)


- 0x2026 (HORIZONTAL ELLIPSIS)


- 0x2039 (SINGLE LEFT-POINTING ANGLE QUOTATION MARK)


- 0x203A (SINGLE RIGHT-POINTING ANGLE QUOTATION MARK)


- 0x20AC (EURO SIGN)


- 0x2122 (TRADE MARK SIGN)


- 0x2212 (MINUS SIGN)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Version format is correct in 'name' table? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The NameID.VERSION_STRING (nameID=5) value must follow the pattern &quot;Version X.Y&quot; with X.Y greater than or equal to 1.000. Current version string is: &quot;Version 0.010; ttfautohint (v1.8.4.7-5d5b)&quot;</p>
 [code: bad-version-strings]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font can render its own name. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>.notdef glyphs were found when attempting to render Pabavathee</p>
 [code: render-own-name]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check glyphs in mark glyph class are non-spacing. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following spacing glyphs may be in the GDEF mark glyph class by mistake:
bullet.001 (U+0D82), bullet.012 (U+0DD3), bullet.013 (U+0DDC), emdash.012 (U+0DD6), emdash.013 (U+0DDE), endash.001 (U+0D83), endash.012 (U+0DD4), endash.013 (U+0DDD), quotedblleft.022 (U+0DCF), quotedblleft.023 (U+0DD1), quotedblleft.024 (U+0DD8), quotedblleft.025 (U+0DDA), quotedblleft.027 (U+0DF3), quotedblright.021 (U+0DCA), quotedblright.022 (U+0DD0), quotedblright.023 (U+0DD2), quotedblright.024 (U+0DD9), quotedblright.025 (U+0DDB), quotedblright.026 (U+0DF2) and quoteright.014 (U+0DDF)</p>
 [code: spacing-mark-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check GDEF mark glyph class doesn't have characters that are not marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following non-mark characters should not be in the GDEF mark glyph class:
U+0D82, U+0D83, U+0DCF, U+0DD0, U+0DD1, U+0DD8, U+0DD9, U+0DDA, U+0DDB, U+0DDC, U+0DDD, U+0DDE, U+0DDF, U+0DF2 and U+0DF3</p>
 [code: non-mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning information.</p>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 380 among a set of 1 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 370:
equal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- NULL

- bullet.017

- bullet.074

- bullet.079

- bullet.080

- bullet.081

- bullet.082

- bullet.083

- bullet.084

- bullet.085

- bullet.086

- bullet.093

- bullet.110

- emdash.014

- emdash.071

- emdash.079

- emdash.080

- emdash.081

- emdash.082

- emdash.083

- emdash.084

- emdash.085

- emdash.086

- emdash.087

- emdash.089

- emdash.100

- emdash.101

- endash.014

- endash.041

- endash.079

- endash.080

- endash.081

- endash.082

- endash.083

- endash.084

- endash.085

- endash.086

- endash.093

- mooniakpushpalksymbol

- pushpalksymbol

- quotedblleft.028

- quotedblleft.029

- quotedblleft.033

- quotedblleft.110

- quotedblleft.126

- quotedblleft.158

- quotedblleft.159

- quotedblleft.160

- quotedblleft.161

- quotedblleft.162

- quotedblleft.163

- quotedblleft.164

- quotedblleft.165

- quotedblleft.166

- quotedblleft.167

- quotedblleft.168

- quotedblleft.169

- quotedblleft.170

- quotedblleft.190

- quotedblleft.191

- quotedblright.030

- quotedblright.033

- quotedblright.110

- quotedblright.159

- quotedblright.160

- quotedblright.161

- quotedblright.162

- quotedblright.163

- quotedblright.164

- quotedblright.165

- quotedblright.166

- quotedblright.167

- quotedblright.168

- quotedblright.169

- quotedblright.170

- quotedblright.171

- quotedblright.172

- quotedblright.191

- quotedblright.192

- quotedblright.214

- quotedblright.262

- quoteright.081

- quoteright.082

- quoteright.083

- quoteright.084

- quoteright.085

- quoteright.086

- quoteright.088

- quoteright.101

- quoteright.108
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* quotedblleft.062: L&lt;&lt;421.0,336.0&gt;--&lt;430.0,346.0&gt;&gt; -&gt; L&lt;&lt;430.0,346.0&gt;--&lt;433.0,349.0&gt;&gt;

* quoteright.016 (U+200D): L&lt;&lt;7.0,614.0&gt;--&lt;-14.0,482.0&gt;&gt; -&gt; L&lt;&lt;-14.0,482.0&gt;--&lt;-41.0,283.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* bullet.032: B&lt;&lt;218.5,318.0&gt;-&lt;210.0,312.0&gt;-&lt;203.0,307.0&gt;&gt;/B&lt;&lt;203.0,307.0&gt;-&lt;212.0,311.0&gt;-&lt;229.0,311.0&gt;&gt; = 11.57518881739615

* bullet.034: B&lt;&lt;508.0,413.0&gt;-&lt;485.0,396.0&gt;-&lt;461.0,396.0&gt;&gt;/B&lt;&lt;461.0,396.0&gt;-&lt;466.0,395.0&gt;-&lt;471.5,394.0&gt;&gt; = 11.309932474020195

* bullet.034: L&lt;&lt;443.0,397.0&gt;--&lt;446.0,397.0&gt;&gt;/B&lt;&lt;446.0,397.0&gt;-&lt;425.0,400.0&gt;-&lt;409.5,413.0&gt;&gt; = 8.13010235415596

* bullet.072: B&lt;&lt;589.0,191.0&gt;-&lt;635.0,230.0&gt;-&lt;659.0,238.0&gt;&gt;/B&lt;&lt;659.0,238.0&gt;-&lt;655.0,237.0&gt;-&lt;648.5,237.5&gt;&gt; = 4.398705354995508

* bullet.085: B&lt;&lt;356.0,122.5&gt;-&lt;356.0,127.0&gt;-&lt;357.0,131.0&gt;&gt;/B&lt;&lt;357.0,131.0&gt;-&lt;327.0,65.0&gt;-&lt;272.0,27.0&gt;&gt; = 10.40771131249005

* eight (U+0038): B&lt;&lt;292.0,318.5&gt;-&lt;253.0,293.0&gt;-&lt;191.0,281.0&gt;&gt;/B&lt;&lt;191.0,281.0&gt;-&lt;250.0,283.0&gt;-&lt;294.0,244.0&gt;&gt; = 9.012576252483942

* emdash.027: B&lt;&lt;242.0,398.0&gt;-&lt;255.0,398.0&gt;-&lt;265.0,397.0&gt;&gt;/B&lt;&lt;265.0,397.0&gt;-&lt;244.0,400.0&gt;-&lt;228.5,413.0&gt;&gt; = 2.419509216656149

* emdash.027: L&lt;&lt;278.0,396.0&gt;--&lt;274.0,396.0&gt;&gt;/B&lt;&lt;274.0,396.0&gt;-&lt;321.0,390.0&gt;-&lt;321.0,362.0&gt;&gt; = 7.275004957889232

* emdash.043: L&lt;&lt;143.0,397.0&gt;--&lt;145.0,397.0&gt;&gt;/B&lt;&lt;145.0,397.0&gt;-&lt;124.0,400.0&gt;-&lt;108.5,413.0&gt;&gt; = 8.13010235415596

* emdash.060: L&lt;&lt;145.0,397.0&gt;--&lt;146.0,397.0&gt;&gt;/B&lt;&lt;146.0,397.0&gt;-&lt;125.0,400.0&gt;-&lt;109.5,413.0&gt;&gt; = 8.13010235415596

* emdash.060: L&lt;&lt;159.0,396.0&gt;--&lt;157.0,396.0&gt;&gt;/B&lt;&lt;157.0,396.0&gt;-&lt;177.0,392.0&gt;-&lt;192.0,377.0&gt;&gt; = 11.309932474020195

* emdash.070: B&lt;&lt;112.0,390.0&gt;-&lt;139.0,399.0&gt;-&lt;158.0,398.0&gt;&gt;/B&lt;&lt;158.0,398.0&gt;-&lt;140.0,403.0&gt;-&lt;126.5,415.0&gt;&gt; = 12.51132349257091

* emdash.070: B&lt;&lt;227.0,413.0&gt;-&lt;204.0,396.0&gt;-&lt;178.0,396.0&gt;&gt;/B&lt;&lt;178.0,396.0&gt;-&lt;208.0,389.0&gt;-&lt;221.5,366.0&gt;&gt; = 13.134022306396327

* emdash.071: L&lt;&lt;119.0,397.0&gt;--&lt;122.0,397.0&gt;&gt;/B&lt;&lt;122.0,397.0&gt;-&lt;101.0,400.0&gt;-&lt;85.5,413.0&gt;&gt; = 8.13010235415596

* emdash.071: L&lt;&lt;135.0,396.0&gt;--&lt;131.0,396.0&gt;&gt;/B&lt;&lt;131.0,396.0&gt;-&lt;151.0,392.0&gt;-&lt;166.0,377.0&gt;&gt; = 11.309932474020195

* endash.032: B&lt;&lt;218.5,318.0&gt;-&lt;210.0,312.0&gt;-&lt;203.0,307.0&gt;&gt;/B&lt;&lt;203.0,307.0&gt;-&lt;212.0,311.0&gt;-&lt;229.0,311.0&gt;&gt; = 11.57518881739615

* endash.034: B&lt;&lt;372.0,377.0&gt;-&lt;400.0,397.0&gt;-&lt;442.0,397.0&gt;&gt;/B&lt;&lt;442.0,397.0&gt;-&lt;421.0,400.0&gt;-&lt;405.5,413.0&gt;&gt; = 8.13010235415596

* endash.034: B&lt;&lt;504.0,413.0&gt;-&lt;482.0,397.0&gt;-&lt;461.0,396.0&gt;&gt;/B&lt;&lt;461.0,396.0&gt;-&lt;466.0,395.0&gt;-&lt;471.5,394.0&gt;&gt; = 14.036243467926457

* endash.064: B&lt;&lt;314.0,137.0&gt;-&lt;314.0,163.0&gt;-&lt;317.0,189.0&gt;&gt;/B&lt;&lt;317.0,189.0&gt;-&lt;313.0,176.0&gt;-&lt;308.0,162.0&gt;&gt; = 10.52078431387435

* endash.064: B&lt;&lt;328.0,270.0&gt;-&lt;328.0,263.0&gt;-&lt;328.0,255.0&gt;&gt;/B&lt;&lt;328.0,255.0&gt;-&lt;338.0,302.0&gt;-&lt;358.0,347.0&gt;&gt; = 12.01147838636543

* endash.070: B&lt;&lt;112.0,390.0&gt;-&lt;139.0,399.0&gt;-&lt;158.0,398.0&gt;&gt;/B&lt;&lt;158.0,398.0&gt;-&lt;140.0,403.0&gt;-&lt;126.5,415.0&gt;&gt; = 12.51132349257091

* endash.070: B&lt;&lt;227.0,413.0&gt;-&lt;204.0,396.0&gt;-&lt;178.0,396.0&gt;&gt;/B&lt;&lt;178.0,396.0&gt;-&lt;208.0,389.0&gt;-&lt;221.5,366.0&gt;&gt; = 13.134022306396327

* endash.071: B&lt;&lt;437.0,109.0&gt;-&lt;422.0,72.0&gt;-&lt;401.0,47.0&gt;&gt;/B&lt;&lt;401.0,47.0&gt;-&lt;402.0,48.0&gt;-&lt;404.0,48.0&gt;&gt; = 4.969740728110289

* quotedblleft.003 (U+0D88): B&lt;&lt;461.0,191.0&gt;-&lt;507.0,230.0&gt;-&lt;531.0,238.0&gt;&gt;/B&lt;&lt;531.0,238.0&gt;-&lt;527.0,237.0&gt;-&lt;520.5,237.5&gt;&gt; = 4.398705354995508

* quotedblleft.010 (U+0DA3): B&lt;&lt;218.5,318.0&gt;-&lt;210.0,312.0&gt;-&lt;203.0,307.0&gt;&gt;/B&lt;&lt;203.0,307.0&gt;-&lt;212.0,311.0&gt;-&lt;229.0,311.0&gt;&gt; = 11.57518881739615

* quotedblleft.023 (U+0DD1): B&lt;&lt;60.0,191.0&gt;-&lt;106.0,230.0&gt;-&lt;130.0,238.0&gt;&gt;/B&lt;&lt;130.0,238.0&gt;-&lt;126.0,237.0&gt;-&lt;119.5,237.5&gt;&gt; = 4.398705354995508

* quotedblleft.047: B&lt;&lt;161.0,397.0&gt;-&lt;165.0,397.0&gt;-&lt;167.0,397.0&gt;&gt;/B&lt;&lt;167.0,397.0&gt;-&lt;147.0,401.0&gt;-&lt;132.0,413.5&gt;&gt; = 11.309932474020195

* quotedblleft.047: L&lt;&lt;182.0,396.0&gt;--&lt;172.0,396.0&gt;&gt;/B&lt;&lt;172.0,396.0&gt;-&lt;201.0,391.0&gt;-&lt;201.0,365.0&gt;&gt; = 9.782407031807285

* quotedblleft.049: B&lt;&lt;40.0,303.0&gt;-&lt;88.0,389.0&gt;-&lt;149.0,396.0&gt;&gt;/B&lt;&lt;149.0,396.0&gt;-&lt;127.0,398.0&gt;-&lt;109.0,411.0&gt;&gt; = 11.740719691028835

* quotedblleft.084: L&lt;&lt;143.0,397.0&gt;--&lt;146.0,397.0&gt;&gt;/B&lt;&lt;146.0,397.0&gt;-&lt;125.0,400.0&gt;-&lt;109.0,413.0&gt;&gt; = 8.13010235415596

* quotedblleft.092: B&lt;&lt;425.0,191.0&gt;-&lt;471.0,230.0&gt;-&lt;495.0,238.0&gt;&gt;/B&lt;&lt;495.0,238.0&gt;-&lt;491.0,237.0&gt;-&lt;484.5,237.5&gt;&gt; = 4.398705354995508

* quotedblleft.099: B&lt;&lt;195.0,413.0&gt;-&lt;175.0,398.0&gt;-&lt;154.0,396.0&gt;&gt;/B&lt;&lt;154.0,396.0&gt;-&lt;160.0,396.0&gt;-&lt;166.0,394.0&gt;&gt; = 5.4403320310054815

* quotedblleft.099: B&lt;&lt;56.0,342.0&gt;-&lt;85.0,393.0&gt;-&lt;136.0,397.0&gt;&gt;/B&lt;&lt;136.0,397.0&gt;-&lt;114.0,400.0&gt;-&lt;97.5,412.5&gt;&gt; = 12.249772027969946

* quotedblleft.117: B&lt;&lt;348.5,79.0&gt;-&lt;339.0,61.0&gt;-&lt;329.0,47.0&gt;&gt;/B&lt;&lt;329.0,47.0&gt;-&lt;330.0,48.0&gt;-&lt;333.0,48.0&gt;&gt; = 9.462322208025574

* quotedblleft.118: L&lt;&lt;145.0,397.0&gt;--&lt;146.0,397.0&gt;&gt;/B&lt;&lt;146.0,397.0&gt;-&lt;125.0,400.0&gt;-&lt;109.5,413.0&gt;&gt; = 8.13010235415596

* quotedblleft.118: L&lt;&lt;159.0,396.0&gt;--&lt;157.0,396.0&gt;&gt;/B&lt;&lt;157.0,396.0&gt;-&lt;177.0,392.0&gt;-&lt;192.0,377.0&gt;&gt; = 11.309932474020195

* quotedblleft.119: B&lt;&lt;304.0,-33.0&gt;-&lt;316.0,-15.0&gt;-&lt;348.0,-1.0&gt;&gt;/B&lt;&lt;348.0,-1.0&gt;-&lt;344.0,-2.0&gt;-&lt;340.0,-2.0&gt;&gt; = 9.593134262730318

* quotedblleft.129: B&lt;&lt;394.0,191.0&gt;-&lt;440.0,230.0&gt;-&lt;464.0,238.0&gt;&gt;/B&lt;&lt;464.0,238.0&gt;-&lt;460.0,237.0&gt;-&lt;453.5,237.5&gt;&gt; = 4.398705354995508

* quotedblleft.138: B&lt;&lt;112.0,390.0&gt;-&lt;139.0,399.0&gt;-&lt;158.0,398.0&gt;&gt;/B&lt;&lt;158.0,398.0&gt;-&lt;140.0,403.0&gt;-&lt;126.5,415.0&gt;&gt; = 12.51132349257091

* quotedblleft.138: B&lt;&lt;227.0,413.0&gt;-&lt;204.0,396.0&gt;-&lt;178.0,396.0&gt;&gt;/B&lt;&lt;178.0,396.0&gt;-&lt;208.0,389.0&gt;-&lt;221.5,366.0&gt;&gt; = 13.134022306396327

* quotedblleft.140: L&lt;&lt;119.0,397.0&gt;--&lt;122.0,397.0&gt;&gt;/B&lt;&lt;122.0,397.0&gt;-&lt;101.0,400.0&gt;-&lt;85.5,413.0&gt;&gt; = 8.13010235415596

* quotedblleft.140: L&lt;&lt;135.0,396.0&gt;--&lt;131.0,396.0&gt;&gt;/B&lt;&lt;131.0,396.0&gt;-&lt;151.0,392.0&gt;-&lt;166.0,377.0&gt;&gt; = 11.309932474020195

* quotedblleft.146: B&lt;&lt;218.5,318.0&gt;-&lt;210.0,312.0&gt;-&lt;203.0,307.0&gt;&gt;/B&lt;&lt;203.0,307.0&gt;-&lt;212.0,311.0&gt;-&lt;229.0,311.0&gt;&gt; = 11.57518881739615

* quotedblleft.158: B&lt;&lt;479.0,161.0&gt;-&lt;477.0,153.0&gt;-&lt;475.0,145.0&gt;&gt;/B&lt;&lt;475.0,145.0&gt;-&lt;486.0,167.0&gt;-&lt;501.0,190.5&gt;&gt; = 12.528807709151492

* quotedblleft.161: B&lt;&lt;373.0,121.5&gt;-&lt;373.0,125.0&gt;-&lt;374.0,129.0&gt;&gt;/B&lt;&lt;374.0,129.0&gt;-&lt;346.0,71.0&gt;-&lt;292.0,34.0&gt;&gt; = 11.733084156412218

* quotedblleft.162: B&lt;&lt;960.5,318.0&gt;-&lt;952.0,312.0&gt;-&lt;945.0,307.0&gt;&gt;/B&lt;&lt;945.0,307.0&gt;-&lt;954.0,311.0&gt;-&lt;971.0,311.0&gt;&gt; = 11.57518881739615

* quotedblleft.198: B&lt;&lt;158.0,404.0&gt;-&lt;150.0,400.0&gt;-&lt;142.0,398.0&gt;&gt;/B&lt;&lt;142.0,398.0&gt;-&lt;148.0,398.0&gt;-&lt;155.5,398.0&gt;&gt; = 14.036243467926484

* quotedblleft.198: B&lt;&lt;67.0,356.0&gt;-&lt;97.0,389.0&gt;-&lt;130.0,396.0&gt;&gt;/L&lt;&lt;130.0,396.0&gt;--&lt;124.0,396.0&gt;&gt; = 11.976132444203333

* quotedblright.047: B&lt;&lt;205.0,413.0&gt;-&lt;187.0,400.0&gt;-&lt;167.0,397.0&gt;&gt;/B&lt;&lt;167.0,397.0&gt;-&lt;201.0,395.0&gt;-&lt;201.0,365.0&gt;&gt; = 11.897226273377932

* quotedblright.047: B&lt;&lt;40.0,303.0&gt;-&lt;88.0,389.0&gt;-&lt;149.0,396.0&gt;&gt;/B&lt;&lt;149.0,396.0&gt;-&lt;127.0,398.0&gt;-&lt;109.5,411.0&gt;&gt; = 11.740719691028835

* quotedblright.063: B&lt;&lt;218.5,318.0&gt;-&lt;210.0,312.0&gt;-&lt;203.0,307.0&gt;&gt;/B&lt;&lt;203.0,307.0&gt;-&lt;212.0,311.0&gt;-&lt;229.0,311.0&gt;&gt; = 11.57518881739615

* quotedblright.084: B&lt;&lt;206.0,413.0&gt;-&lt;183.0,396.0&gt;-&lt;158.0,396.0&gt;&gt;/B&lt;&lt;158.0,396.0&gt;-&lt;164.0,395.0&gt;-&lt;169.0,393.0&gt;&gt; = 9.462322208025613

* quotedblright.084: L&lt;&lt;143.0,397.0&gt;--&lt;145.0,397.0&gt;&gt;/B&lt;&lt;145.0,397.0&gt;-&lt;124.0,400.0&gt;-&lt;108.0,413.0&gt;&gt; = 8.13010235415596

* quotedblright.099: B&lt;&lt;198.0,413.0&gt;-&lt;177.0,398.0&gt;-&lt;155.0,396.0&gt;&gt;/B&lt;&lt;155.0,396.0&gt;-&lt;161.0,396.0&gt;-&lt;166.0,394.0&gt;&gt; = 5.1944289077348

* quotedblright.099: B&lt;&lt;56.0,342.0&gt;-&lt;86.0,394.0&gt;-&lt;138.0,397.0&gt;&gt;/B&lt;&lt;138.0,397.0&gt;-&lt;116.0,400.0&gt;-&lt;100.0,412.5&gt;&gt; = 11.06703169286027

* quotedblright.140: L&lt;&lt;119.0,397.0&gt;--&lt;121.0,397.0&gt;&gt;/B&lt;&lt;121.0,397.0&gt;-&lt;100.0,400.0&gt;-&lt;84.5,413.0&gt;&gt; = 8.13010235415596

* quotedblright.140: L&lt;&lt;134.0,396.0&gt;--&lt;131.0,396.0&gt;&gt;/B&lt;&lt;131.0,396.0&gt;-&lt;151.0,392.0&gt;-&lt;166.0,377.0&gt;&gt; = 11.309932474020195

* quotedblright.166: B&lt;&lt;409.0,41.0&gt;-&lt;413.0,54.0&gt;-&lt;420.0,70.0&gt;&gt;/B&lt;&lt;420.0,70.0&gt;-&lt;399.0,36.0&gt;-&lt;368.0,15.0&gt;&gt; = 8.07205193884889

* quotedblright.167: B&lt;&lt;374.0,391.0&gt;-&lt;423.0,373.0&gt;-&lt;439.0,310.0&gt;&gt;/B&lt;&lt;439.0,310.0&gt;-&lt;439.0,326.0&gt;-&lt;448.0,342.0&gt;&gt; = 14.250032697803595

* quotedblright.187: B&lt;&lt;547.0,191.0&gt;-&lt;593.0,230.0&gt;-&lt;617.0,238.0&gt;&gt;/B&lt;&lt;617.0,238.0&gt;-&lt;613.0,237.0&gt;-&lt;606.5,237.5&gt;&gt; = 4.398705354995508

* quoteright.028: B&lt;&lt;242.0,398.0&gt;-&lt;252.0,398.0&gt;-&lt;260.0,397.0&gt;&gt;/B&lt;&lt;260.0,397.0&gt;-&lt;240.0,401.0&gt;-&lt;225.0,413.5&gt;&gt; = 4.184916125118319

* quoteright.044: L&lt;&lt;143.0,397.0&gt;--&lt;144.0,397.0&gt;&gt;/B&lt;&lt;144.0,397.0&gt;-&lt;123.0,400.0&gt;-&lt;107.5,413.0&gt;&gt; = 8.13010235415596

* quoteright.070: B&lt;&lt;112.0,390.0&gt;-&lt;139.0,399.0&gt;-&lt;158.0,398.0&gt;&gt;/B&lt;&lt;158.0,398.0&gt;-&lt;140.0,403.0&gt;-&lt;126.5,415.0&gt;&gt; = 12.51132349257091

* quoteright.070: B&lt;&lt;227.0,413.0&gt;-&lt;204.0,396.0&gt;-&lt;178.0,396.0&gt;&gt;/B&lt;&lt;178.0,396.0&gt;-&lt;208.0,389.0&gt;-&lt;221.5,366.0&gt;&gt; = 13.134022306396327

* quoteright.072: L&lt;&lt;119.0,397.0&gt;--&lt;121.0,397.0&gt;&gt;/B&lt;&lt;121.0,397.0&gt;-&lt;100.0,400.0&gt;-&lt;84.5,413.0&gt;&gt; = 8.13010235415596

* quoteright.072: L&lt;&lt;134.0,396.0&gt;--&lt;131.0,396.0&gt;&gt;/B&lt;&lt;131.0,396.0&gt;-&lt;151.0,392.0&gt;-&lt;166.0,377.0&gt;&gt; = 11.309932474020195

* three (U+0033): B&lt;&lt;297.0,313.0&gt;-&lt;250.0,283.0&gt;-&lt;191.0,271.0&gt;&gt;/B&lt;&lt;191.0,271.0&gt;-&lt;257.0,273.0&gt;-&lt;291.0,243.0&gt;&gt; = 9.760858428657397
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* pushpalksymbol: L&lt;&lt;25.0,456.0&gt;--&lt;24.0,767.0&gt;&gt;

* pushpalksymbol: L&lt;&lt;308.0,266.0&gt;--&lt;307.0,756.0&gt;&gt;

* pushpalksymbol: L&lt;&lt;377.0,709.0&gt;--&lt;376.0,481.0&gt;&gt;

* pushpalksymbol: L&lt;&lt;516.0,456.0&gt;--&lt;518.0,752.0&gt;&gt;

* pushpalksymbol: L&lt;&lt;542.0,758.0&gt;--&lt;541.0,456.0&gt;&gt;

* pushpalksymbol: L&lt;&lt;676.0,456.0&gt;--&lt;675.0,767.0&gt;&gt;

* pushpalksymbol: L&lt;&lt;841.0,456.0&gt;--&lt;842.0,707.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* bullet.036 has a counter-clockwise outer contour

* emdash.034 has a counter-clockwise outer contour

* endash.056 has a counter-clockwise outer contour

* quotedblleft.059 has a counter-clockwise outer contour

* quotedblleft.061 has a counter-clockwise outer contour

* quotedblleft.137 has a counter-clockwise outer contour
</code></pre>
 [code: ccw-outer-contour]



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
<li>U+E3A2 : not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>sinhala</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[1] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Pabavathee-Regular.ttf'].</p>
 [code: missing-os2-fsselection-bit7]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 8 | 13 | 121 | 7 | 102 | 0 | 
| 0% | 0% | 3% | 5% | 48% | 3% | 41% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
