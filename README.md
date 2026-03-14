# Hekenic Shpre (F1E00 - F1EFF)

## Nahnya

The Neptunian syllabary, known locally as "Nahnya" (lit. Syllabary) is a mostly-pure syllabary, mapping almost 1:1 with the spoken sounds of the language, aside from syllable-final characters which are written separately. The character shapes are directly derived from an ancient logography, so there's not a pattern to derive the shapes of most characters.

To form lone consonants for syllable-final sounds, a "Shortener" mark is placed after the `-H` form of the consonant. For example, to write `P` on it's own, you'd write that as `NAHNYA SYLLABLE PH, PAHNYA SIGN VIRAMA`.

Nahnya has three levels of punctuation, Short, Medium, and Long. These are roughly equivalent to a comma, full stop, and end of paragrah in English.

Traditionally, Nahnya is written without spaces, however doing so is more common as of 2106 due to influence from nearby languages and from English.

The syllables are encoded in the traditional ordering of the characters, to allow numerical codepoint sorting to match the expected order by speakers of the language.

### Exepctions

As an exception to that, the `R` onset syllables are formed by adding a "silencer mark" to the respective `D` onset syllables. The position of the silencer mark is different per character, and linguistically it makes more sense to analyze these as separate characters. The silencer mark is the same as a "short" punctuation.

The pairs `P/B`, `F/V`, `K/G`, and (syllabic `-H`) `-H/-AH` are considered allophonic to each-other, so no distinction is made in the writing system. Some sounds are written the same as other characters, since dedicated glyphs do not exist, the glyphs in question are listed below.

- The syllable KYH is written as `NAHNYA SYLLABLE K, NAHNYA SYLLABLE YH` due to a lack of a character existing for that sound. This syllable is seen in words like `nwgyahk`.
- `KI` is written `NGI`.
- `YI` and `YW` are written `YE`.

There are also a couple exceptions in the spelling, caused by language sound changes. Some of these syllable-final characters have other ways to be written, which is also considered valid in these cases, but these exceptions are seen as more correct as of 2106.

- In syllable-final position, `T` after syllabic `H` may be written as `N`. This is the only place /t/ appears in the language.
- In syllable-final position, `K` after syllabic `H` may be written as `NG`. Normally, this would be written as `NAHNYA SYLLABLE KH, NAHNYA SIGN VIRAMA`.
- In syllable-final position, `P` after syllabic `H` may be written as `M`. Normally, this would be written as `NAHNYA SYLLABLE PH, NAHNYA SIGN VIRAMA`.

Some glyphs are also very similar to each-other, often written identically in handwriting, those pairs are listed here:

- `FRAI` and `MYAI` are very similar, and are generally written the same in handwriting, but officially have different shapes.
- `FRE` and `MYH` are [fully visually identical](https://discord.com/channels/1284943477984989258/1289355465658204210/1480365100211638303), but are [still analyzed as separate characters](https://discord.com/channels/1284943477984989258/1289355465658204210/1480367144536637612) (this matters when sorting characters), so they are encoded separately.

Since some consonants do not have `-H` forms, so to write them on their own, other forms are used instead.

- `H` is written as `NAHNYA SYLLABLE HW, NAHNYA SIGN VIRAMA`
- `NG` is written as `NAHNYA SYLLABLE NGW, NAHNYA SIGN VIRAMA`

### Proposed encoding

All text after `#` is considered errata for ease of understanding and is not part of the specification.

```
U+F1E00 - NAHNYA SYLLABLE PE
U+F1E01 - NAHNYA SYLLABLE PEI
U+F1E02 - NAHNYA SYLLABLE PA
U+F1E03 - NAHNYA SYLLABLE PAI
U+F1E04 - NAHNYA SYLLABLE PI
U+F1E05 - NAHNYA SYLLABLE PW
U+F1E06 - NAHNYA SYLLABLE PH
U+F1E07 - NAHNYA SYLLABLE PRE
U+F1E08 - NAHNYA SYLLABLE PREI
U+F1E09 - NAHNYA SYLLABLE PRA
U+F1E0A - NAHNYA SYLLABLE PRAI
U+F1E0B - NAHNYA SYLLABLE PRI
U+F1E0C - NAHNYA SYLLABLE PRW
U+F1E0D - NAHNYA SYLLABLE PRH
U+F1E0E - NAHNYA SYLLABLE PYE
U+F1E0F - NAHNYA SYLLABLE PYEI
U+F1E10 - NAHNYA SYLLABLE PYA
U+F1E11 - NAHNYA SYLLABLE PYAI
U+F1E12 - NAHNYA SYLLABLE PYH
U+F1E13 - NAHNYA SYLLABLE FE
U+F1E14 - NAHNYA SYLLABLE FEI
U+F1E15 - NAHNYA SYLLABLE FA
U+F1E16 - NAHNYA SYLLABLE FAI
U+F1E17 - NAHNYA SYLLABLE FI
U+F1E18 - NAHNYA SYLLABLE FW
U+F1E19 - NAHNYA SYLLABLE FH
U+F1E1A - NAHNYA SYLLABLE FRE
U+F1E1B - NAHNYA SYLLABLE FREI
U+F1E1C - NAHNYA SYLLABLE FRA
U+F1E1D - NAHNYA SYLLABLE FRAI
U+F1E1E - NAHNYA SYLLABLE FRI
U+F1E1F - NAHNYA SYLLABLE FRW
U+F1E20 - NAHNYA SYLLABLE FRH
U+F1E21 - NAHNYA SYLLABLE KE
U+F1E22 - NAHNYA SYLLABLE KEI
U+F1E23 - NAHNYA SYLLABLE KA
U+F1E24 - NAHNYA SYLLABLE KAI
U+F1E25 - NAHNYA SYLLABLE KW
U+F1E26 - NAHNYA SYLLABLE KH
U+F1E27 - NAHNYA SYLLABLE KRE
U+F1E28 - NAHNYA SYLLABLE KREI
U+F1E29 - NAHNYA SYLLABLE KRA
U+F1E2A - NAHNYA SYLLABLE KRAI
U+F1E2B - NAHNYA SYLLABLE KRI
U+F1E2C - NAHNYA SYLLABLE KRW
U+F1E2D - NAHNYA SYLLABLE KRH
U+F1E2E - NAHNYA SYLLABLE ME
U+F1E2F - NAHNYA SYLLABLE MEI
U+F1E30 - NAHNYA SYLLABLE MA
U+F1E31 - NAHNYA SYLLABLE MAI
U+F1E32 - NAHNYA SYLLABLE MI
U+F1E33 - NAHNYA SYLLABLE MW
U+F1E34 - NAHNYA SYLLABLE MH
U+F1E35 - NAHNYA SYLLABLE MYE
U+F1E36 - NAHNYA SYLLABLE MYEI
U+F1E37 - NAHNYA SYLLABLE MYA
U+F1E38 - NAHNYA SYLLABLE MYAI
U+F1E39 - NAHNYA SYLLABLE MYH
U+F1E3A - NAHNYA SYLLABLE NE
U+F1E3B - NAHNYA SYLLABLE NEI
U+F1E3C - NAHNYA SYLLABLE NA
U+F1E3D - NAHNYA SYLLABLE NAI
U+F1E3E - NAHNYA SYLLABLE NI
U+F1E3F - NAHNYA SYLLABLE NW
U+F1E40 - NAHNYA SYLLABLE NH
U+F1E41 - NAHNYA SYLLABLE NYE
U+F1E42 - NAHNYA SYLLABLE NYEI
U+F1E43 - NAHNYA SYLLABLE NYA
U+F1E44 - NAHNYA SYLLABLE NYAI
U+F1E45 - NAHNYA SYLLABLE NYH
U+F1E46 - NAHNYA SYLLABLE DE
U+F1E47 - NAHNYA SYLLABLE DEI
U+F1E48 - NAHNYA SYLLABLE DA
U+F1E49 - NAHNYA SYLLABLE DAI
U+F1E4A - NAHNYA SYLLABLE DI
U+F1E4B - NAHNYA SYLLABLE DW
U+F1E4C - NAHNYA SYLLABLE DH
U+F1E4D - NAHNYA SYLLABLE RE
U+F1E4E - NAHNYA SYLLABLE REI
U+F1E4F - NAHNYA SYLLABLE RA
U+F1E50 - NAHNYA SYLLABLE RAI
U+F1E51 - NAHNYA SYLLABLE RI
U+F1E52 - NAHNYA SYLLABLE RW
U+F1E53 - NAHNYA SYLLABLE RH
U+F1E54 - NAHNYA SYLLABLE SE
U+F1E55 - NAHNYA SYLLABLE SEI
U+F1E56 - NAHNYA SYLLABLE SA
U+F1E57 - NAHNYA SYLLABLE SAI
U+F1E58 - NAHNYA SYLLABLE SI
U+F1E59 - NAHNYA SYLLABLE SW
U+F1E5A - NAHNYA SYLLABLE SH
U+F1E5B - NAHNYA SYLLABLE CHE
U+F1E5C - NAHNYA SYLLABLE CHEI
U+F1E5D - NAHNYA SYLLABLE CHA
U+F1E5E - NAHNYA SYLLABLE CHAI
U+F1E5F - NAHNYA SYLLABLE CHI
U+F1E60 - NAHNYA SYLLABLE CHW
U+F1E61 - NAHNYA SYLLABLE CHH
U+F1E62 - NAHNYA SYLLABLE HE
U+F1E63 - NAHNYA SYLLABLE HEI
U+F1E64 - NAHNYA SYLLABLE HA
U+F1E65 - NAHNYA SYLLABLE HAI
U+F1E66 - NAHNYA SYLLABLE HI
U+F1E67 - NAHNYA SYLLABLE HW
U+F1E68 - NAHNYA SYLLABLE YE
U+F1E69 - NAHNYA SYLLABLE YEI
U+F1E6A - NAHNYA SYLLABLE YA
U+F1E6B - NAHNYA SYLLABLE YAI
U+F1E6C - NAHNYA SYLLABLE YH
U+F1E6D - NAHNYA SYLLABLE NGI
U+F1E6E - NAHNYA SYLLABLE NGW
U+F1E6F - NAHNYA SIGN VIRAMA
U+F1E70 - NAHNYA PUNCTUATION SHORT # This is visually the same glyph as the "Silencer Mark"
U+F1E71 - NAHNYA PUNCTUATION MEDIUM
U+F1E72 - NAHNYA PUNCTUATION LONG
```

## Nävein

The Martian alphabet, known locally as "Nävein", has 17 letters and is non-phonetic in modern Martian, due to sound changes.

Nävein has the same three levels of semantic punctuation as Nahnya, however they are written horizontally next to eachother as separate characters, rather than combined vertically as in Nahnya, and so longer pauses are encoded as multiple `NAVEIN PUNCTUATION` codepoints in direct sequence.

Nävein is written with spaces, and has multiple optional stylistic characters for when there are geminiates or clusters with R and Y. These styilistic characters bear no meaning on the pronunciation of the characters, and are best thought of as standardized ligatures, so they are not encoded and are instead encouraged to be implemented using ligatures based on the preferences of the font maker. See the [Laghari Portals](https://www.laghariportals.com/hekenic) website for what combining characters are standardized.

The letters are encoded in the traditional Nävein ordering, to allow numerical codepoint sorting to match alphabetical sorting. The codepoints are named after the standardized [names](https://discord.com/channels/1284943477984989258/1289355465658204210/1480325948753711186) for them. The reasoning for placing the role of the letter in the name is to disambiguate the vowel `pä` (`NAVEIN VOWEL LETTER PA`) from the consonant `pa` (`NAVEIN CONSONANT LETTER PA`) using only ASCII characters.

### Exceptions

While there are a lot of spelling exceptions inside Nävein, none are relevant to choices made when deciding the encoding itself, unlike Nahnya.

### Proposed Encoding

All text after `#` is errata and not part of the specification, it contains the sound this letter traditionally makes.

```
U+F1E80 - NAVEIN CONSONANT LETTER PA # P
U+F1E81 - NAVEIN CONSONANT LETTER MA # M
U+F1E82 - NAVEIN CONSONANT LETTER NA # N
U+F1E83 - NAVEIN CONSONANT LETTER TA # T
U+F1E84 - NAVEIN CONSONANT LETTER KA # K
U+F1E85 - NAVEIN CONSONANT LETTER QA # Q
U+F1E86 - NAVEIN CONSONANT LETTER CA # C
U+F1E87 - NAVEIN CONSONANT LETTER HA # H
U+F1E88 - NAVEIN CONSONANT LETTER A  # V
U+F1E89 - NAVEIN CONSONANT LETTER RA # R
U+F1E8A - NAVEIN CONSONANT LETTER YA # Y
U+F1E8B - NAVEIN VOWEL LETTER MI  # I
U+F1E8C - NAVEIN VOWEL LETTER PE  # E
U+F1E8D - NAVEIN VOWEL LETTER PA  # Ä
U+F1E8E - NAVEIN VOWEL LETTER AMA # A
U+F1E8F - NAVEIN VOWEL LETTER PEI # EI
U+F1E90 - NAVEIN VOWEL LETTER MAI # AI
U+F1E91 - NAVEIN PUNCTUATION
```

## Nunye

Nunye is best described as an Alphasyllabary, with base forms of consonants, marking vowels and certain clusters with diacritical marks. In some cases though, the diacritical marks have merged with the base character, leading to inconsistencies in the expected shapes for many letters. This document is encoding the form of Nunye as seen in 2106.

### Exceptions

Due to Nunye being standardized in the past during the time of Old Solar, when analyzed in it's written form it tends to resemble Neptunian more than it does Modern Solar, this leads to a lot of spelling and pronunciation inconsistencies.

#### Added characters

Some sounds were not present when Nunye was standardized, however have since appeared in Solar's pronunciation, these characters are as follows:

- TI - `NUNYE CONSONANT TA, NUNYE VOWEL SIGN MI`
- TU1 - `NUNYE CONSONANT TA, NUNYE VOWEL SIGN MW`
- YI - `NUNYE CONSONANT YA, NUNYE VOWEL SIGN MI`

These characters are still used in Modern Solar, but are often replaced by other letters due to being missing when spelling was standardized.

Codepoints are named after their local names in Modern Solar.

### Ordering

Ordering in Nunye is not as simple as other scripts due to the composite nature of the script, however it is consistent and has a strict pattern. This does mean that a simple numerical codepoint ordering will *not* produce the standardized order expected of the script.

When ordering, descenders are considered part of the base consonant and are treated in the following order:

- `NUNYE CONSONANT 00, NUNYE VOWEL SIGN 00`
- `NUNYE CONSONANT 00, NUNYE COMBINING DESCENDER R, NUNYE VOWEL SIGN 00`
- `NUNYE CONSONANT 00, NUNYE COMBINING DESCENDER Y, NUNYE VOWEL SIGN 00`
- `NUNYE CONSONANT 00, NUNYE VOWEL SIGN 01`
- `NUNYE CONSONANT 00, NUNYE COMBINING DESCENDER R, NUNYE VOWEL SIGN 01`
- `NUNYE CONSONANT 00, NUNYE COMBINING DESCENDER Y, NUNYE VOWEL SIGN 01`
- `NUNYE CONSONANT 01, NUNYE VOWEL SIGN 00`
- `NUNYE CONSONANT 01, NUNYE COMBINING DESCENDER R, NUNYE VOWEL SIGN 00`
- `NUNYE CONSONANT 01, NUNYE COMBINING DESCENDER Y, NUNYE VOWEL SIGN 00`
- `NUNYE CONSONANT 01, NUNYE VOWEL SIGN 01`
- `NUNYE CONSONANT 01, NUNYE COMBINING DESCENDER R, NUNYE VOWEL SIGN 01`
- `NUNYE CONSONANT 01, NUNYE COMBINING DESCENDER Y, NUNYE VOWEL SIGN 01`

The order of the individual consonants and vowels is the same as present in the encoding, with the first consonants being `PA, MA, NA, ...` and the first vowels being `MI, MW, PA, ...`

### Proposed Encoding

All text after `#` represents the historical pronunciation when Nunye was standardized, and all text after `;` represents the name used on the [Laghari Portals](https://www.laghariportals.com/hekenic) website to describe this letter, if different. These are errata and are only present to aid in understanding, not part of the specification.

#### Base consonant forms

```
U+F1EA0 - NUNYE CONSONANT PA # P ; P / F
U+F1EA1 - NUNYE CONSONANT MA # M
U+F1EA2 - NUNYE CONSONANT NA # N
U+F1EA3 - NUNYE CONSONANT TA # T ; T / S
U+F1EA4 - NUNYE CONSONANT KA # K ; K / H
U+F1EA5 - NUNYE CONSONANT A  # NG ; - / NG
U+F1EA6 - NUNYE CONSONANT HA # H
U+F1EA7 - NUNYE CONSONANT FA # F ; F / vv
U+F1EA8 - NUNYE CONSONANT DA # R ; D / S
U+F1EA9 - NUNYE CONSONANT YA # Y
```

#### Vowel Signs

```
U+F1EAA - NUNYE VOWEL SIGN MI  # I
U+F1EAB - NUNYE VOWEL SIGN MU  # W ; U1
U+F1EAC - NUNYE VOWEL SIGN PA  # Ä
U+F1EAD - NUNYE VOWEL SIGN AMA # A
U+F1EAE - NUNYE VOWEL SIGN PU  # E ; U2
U+F1EAF - NUNYE VOWEL SIGN PE  # EI ; E
U+F1EB0 - NUNYE VOWEL SIGN MAE # AI ; AE
```

#### Descenders

Attached to consonants, and placed before vowels, these change the sound of the final syllable in unpredictable ways, but when analyzing the historical spellings, consistently adds the consonant to the onset. For example `NUNYE CONSONANT FA, NUNYE COMBINING DESCENDER R, NUNYE VOWEL SIGN MAE` is analyzed as the character `frai`, and `NUNYE CONSONANT MA, NUNYE COMBINING DESCENDER Y, NUNYE VOWEL SIGN MAE` is analyzed as the character `myai`.

```
U+F1EB1 - NUNYE COMBINING DESCENDER R
U+F1EB2 - NUNYE COMBINING DESCENDER Y
```

#### Punctuation

Nunye has the same three punctuations as Nahnya, and you can read about their usage above. Because the Nahnya punctuation glyph is anaylzed as the same glyph as the Silencer, the Nunye punctuation are encoded as separate codepoints rather than encoding a single shared `HEKENIC PUNCTUATION SHORT/MEDIUM/LONG` for both of them.

```
U+F1EB3 - NUNYE PUNCTUATION SHORT
U+F1EB4 - NUNYE PUNCTUATION MEDIUM
U+F1EB5 - NUNYE PUNCTUATION LONG
```

## Äfubes

The Future Solar alphabet, known locally as Äfubes, is a nearly-phonetic alphabet used to encode Future Solar, an evolution of Modern Solar from the year 2399, with heavy influence from English and the Latin Alphabet. One of it's main goals was to make it possible to write the script without ligatures, compared to Modern Solar which needs uses lots of them, so that usage on a computer is easier. This is reflected in the encoding, using one codepoint per letter.

Äfubes has 28 letters officially, however there are 2 uncommon letters (that do see minor use) and so are included in the encoding, even if it is not standard practice to use these. They are listed as follows:

- `AFUBES LETTER UU` - This is a long form of the of `U` vowel.
- `AFUBES LETTER PAE` - Refer to the section on the [Pä-Pa-Pe Controversy](https://www.laghariportals.com/hekenic) on the Laghari Portals website for why this glyph was originally created.

While characters like `PÄ`, `PAE`, `PA`, and `PE` are sometimes referred to as ligatures, their usage effects the ordering of words, and so are listed as separate codepoints, with the user's IME autocompleting them in when the user types the separate characters. Codepoints are all listed in their standard ordering, so sorting by codepoint will sort by letter.

Some letters have multiple names, one for the native name, and one named loaned from English, this encoding uses the native name where possible, using loans to distinguish where not normally possible without the letter `Ä`.

### Proposed Encoding

All text after `#` or `;` is considered errata and is not part of the specification. It contains the sound the letter makes, for ease of understanding. All text after `;` is either an alternate name for this letter, or extra information.

```
U+F1EC0 - AFUBES LETTER AMA # A ; EI
U+F1EC1 - AFUBES LETTER MAE # AE
U+F1EC2 - AFUBES LETTER PA # Ä ; PÄ
U+F1EC3 - AFUBES LETTER PAA # ÄÄ ; PÄÄ
U+F1EC4 - AFUBES LETTER PIS # B ; BI
U+F1EC5 - AFUBES LETTER SI # CH
U+F1EC6 - AFUBES LETTER DI # D
U+F1EC7 - AFUBES LETTER PE # E ; II
U+F1EC8 - AFUBES LETTER PEI # EI
U+F1EC9 - AFUBES LETTER UA # F / U ; EF
U+F1ECA - AFUBES LETTER JII # G
U+F1ECB - AFUBES LETTER HA # H ; EICH
U+F1ECC - AFUBES LETTER MI # I ; AE
U+F1ECD - AFUBES LETTER MII # II
U+F1ECE - AFUBES LETTER JEI # J
U+F1ECF - AFUBES LETTER KA # K ; KEI
U+F1ED0 - AFUBES LETTER MA # M ; NEM
U+F1ED1 - AFUBES LETTER NA # N ; EN
U+F1ED2 - AFUBES LETTER A # NG
U+F1ED3 - AFUBES LETTER PII # P ; Traditional name PA, but to not conflict, the loan PII was chosen.
U+F1ED4 - AFUBES LETTER RHA # RH ; UAA
U+F1ED5 - AFUBES LETTER DA # S ; ES
U+F1ED6 - AFUBES LETTER TA # T ; DII
U+F1ED7 - AFUBES LETTER MU # U ; RHUU
U+F1ED8 - AFUBES LETTER MUU # UU
U+F1ED9 - AFUBES LETTER ZII # Z
U+F1EDA - AFUBES LETTER PAPA # PÄ
U+F1EDB - AFUBES LETTER PAMAE # PAE
U+F1EDC - AFUBES LETTER PAAMA # PA
U+F1EDD - AFUBES LETTER PAPE # PE
U+F1EDE - AFUBES PUNCTUATION PERIOD ; Locally RHEMRHE
U+F1EDF - AFUBES PUNCTUATION COMMA ; Locally RHEAA
```
