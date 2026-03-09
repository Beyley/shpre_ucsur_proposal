# Hekenic Shpre (F1E00 - F1EFF)

## Nahnya

The Neptunian syllabary, known locally as "Nahnya" (lit. Syllabary) is a mostly-pure syllabary, mapping almost 1:1 with the spoken sounds of the language, aside from syllable-final characters which are written separately. The character shapes are directly derived from an ancient logography, so there's not a pattern to derive the shapes of most characters.

To form lone consonants for syllable-final sounds, a "Shortener" mark is placed after the `-H` form of the consonant. For example, to write `P` on it's own, you'd write that as `NAHNYA SYLLABLE PH, PAHNYA SIGN VIRAMA`.

Nahnya has three levels of punctuation, Short, Medium, and Long. These are roughly equivalent to a comma, full stop, and end of paragrah in English.

Traditionally, Nahnya is written without spaces, however doing so is more common as of 2106 due to influence from nearby languages and from English.

The syllables are encoded in the traditional ordering of the characters, so to sort two characters, you only have to compare the numeric values of the codepoints earlier codepoints go earlier when sorting.

### Exepctions

As an exception to that, the `R` onset syllables are formed by adding a "silencer mark" to the respective `D` onset syllables. The position of the silencer mark is different per character, and linguistically it makes more sense to analyze these as separate characters. The silencer mark is the same as a "short" punctuation.

The pairs `P/B`, `F/V`, `K/G`, and (syllabic `H`) `H/AH` are considered allophonic to each-other, so no distinction is made in the writing system. Some sounds are written the same as other characters, since dedicated glyphs do not exist, the glyphs in question are listed below.

- The syllable KYH is written as `NAHNYA SYLLABLE K, NAHNYA SYLLABLE YH` due to a lack of a character existing for that sound. This syllable is seen in words like `nwgyahk`.
- `KI` is written `NGI`.
- `YI` and `YW` are written `YE`.

There are also a couple exceptions in the spelling, caused by language sound changes. Some of these syllable-final characters have other ways to be written, which is also considered valid in these cases, but these exceptions are seen as more correct as of 2106.

- In syllable-final position, `T` after syllabic `H` may be written as `N`. This is the only place /t/ appears in the language.
- In syllable-final position, `K` after syllabic `H` may be written as `NG`. Normally, this would be written as `NAHNYA SYLLABLE KH, NAHNYA SIGN VIRAMA`.
- In syllable-final position, `P` after syllabic `H` may be written as `M`. Normally, this would be written as `NAHNYA SYLLABLE PH, NAHNYA SIGN VIRAMA`.

Some glyphs are also very similar to each-other, often written identically in handwriting, those pairs are listed here:

- `FRAI` and `MYAI`.
- `FRE` and `MYH`.

Since some consonants do not have `-H` forms, so to write them on their own, other forms are used instead.

- `H` is written as `NAHNYA SYLLABLE HW, NAHNYA SIGN VIRAMA`
- `NG` is written as `NAHNYA SYLLABLE NGW, NAHNYA SIGN VIRAMA`

### Proposed encoding

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
U+F1E70 - NAHNYA PUNCTUATION SHORT
U+F1E71 - NAHNYA PUNCTUATION MEDIUM
U+F1E72 - NAHNYA PUNCTUATION LONG
```

## Nävein

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

### Base consonant forms

Codepoints are named after their local names, but due to spelling still reflecting the historical pronunciations of words, it makes more sense when *spelling* words to analyze them as the sound in the comment, rather than the name of the consonant in modern Solar.

```
U+F1EA0 - NUNYE CONSONANT PA # P
U+F1EA1 - NUNYE CONSONANT MA # M
U+F1EA2 - NUNYE CONSONANT NA # N
U+F1EA3 - NUNYE CONSONANT TA # T
U+F1EA4 - NUNYE CONSONANT KA # K
U+F1EA5 - NUNYE CONSONANT A  # NG
U+F1EA6 - NUNYE CONSONANT HA # H
U+F1EA7 - NUNYE CONSONANT FA # F
U+F1EA8 - NUNYE CONSONANT DA # R
U+F1EA9 - NUNYE CONSONANT YA # Y
```

### Vowel Signs

Attached to consonants.

Codepoints are named after local names, but due to historical spellings, when spelling words it makes more sense to analyze them as the sound in the comment, rather than the sound they make in modern Solar.

```
U+F1EAA - NUNYE VOWEL SIGN MI  # I
U+F1EAB - NUNYE VOWEL SIGN MW  # W
U+F1EAC - NUNYE VOWEL SIGN PA  # Ä
U+F1EAD - NUNYE VOWEL SIGN AMA # A
U+F1EAE - NUNYE VOWEL SIGN PU  # E
U+F1EAF - NUNYE VOWEL SIGN PE  # EI
U+F1EB0 - NUNYE VOWEL SIGN MAE # AI
```

### Descenders

Attached to consonants, but placed before vowels, these change the sound of the final syllable in unpredictable ways, but when analyizing the historical "spellings", breaks down to two being "spelled" as R (ex. frai) and Y (ex. nyai)

```
U+F1EB1 - NUNYE COMBINING DESCENDER R
U+F1EB2 - NUNYE COMBINING DESCENDER Y
```

### Punctuation

```
U+F1EB3 - NUNYE PUNCTUATION SHORT # Similar in function to a comma, representing a short pause in a sentence
U+F1EB4 - NUNYE PUNCTUATION MEDIUM # Similar in function to a period, representing a medium length pause, for breaking up sentences
U+F1EB5 - NUNYE PUNCTUATION LONG # Similar in function to a newline, representing a long pause, for breaking up paragraphs
```

## Äfubes

```
U+F1EC0 - AFUBES LETTER A
U+F1EC1 - AFUBES LETTER AE
U+F1EC2 - AFUBES LETTER Ä
U+F1EC3 - AFUBES LETTER ÄÄ
U+F1EC4 - AFUBES LETTER B
U+F1EC5 - AFUBES LETTER CH
U+F1EC6 - AFUBES LETTER D
U+F1EC7 - AFUBES LETTER E
U+F1EC8 - AFUBES LETTER EI
U+F1EC9 - AFUBES LETTER F / U
U+F1ECA - AFUBES LETTER G
U+F1ECB - AFUBES LETTER H
U+F1ECC - AFUBES LETTER I
U+F1ECD - AFUBES LETTER II
U+F1ECE - AFUBES LETTER J
U+F1ECF - AFUBES LETTER K
U+F1ED0 - AFUBES LETTER M
U+F1ED1 - AFUBES LETTER N
U+F1ED2 - AFUBES LETTER NG
U+F1ED3 - AFUBES LETTER P
U+F1ED4 - AFUBES LETTER RH
U+F1ED5 - AFUBES LETTER S
U+F1ED6 - AFUBES LETTER T
U+F1ED7 - AFUBES LETTER U
U+F1ED8 - AFUBES LETTER UU
U+F1ED9 - AFUBES LETTER Z
U+F1EDA - AFUBES LETTER PÄ
U+F1EDB - AFUBES LETTER PAE
U+F1EDC - AFUBES LETTER PA
U+F1EDD - AFUBES LETTER PE
U+F1EDE - AFUBES PUNCTUATION PERIOD
U+F1EDF - AFUBES PUNCTUATION COMMA
```
