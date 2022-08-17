# nnsvs-custom-japanese
Custom HED and Table for UPT3 Japanese, also known as "Japanese+".

These are based on the HED files included in the r9y9/nnsvs repo.
All this does is add support for UTP3's own selection of ENUNU flags, a few extra phonemes, and romaji support in the table.

These HED files should be compatible with any dataset that is compatible with the ENUNU-Training-Kit HED files.

Additional Phonemes compared to standard NNSVS HED:

| Phoneme     | Purpose                                                     |
|-------------|-------------------------------------------------------------|
| ~~Edge~~ vf        |Vocal Fry ~~(ETK Compatibility)~~                               |
| ~~GlottalStop~~ gs | Glottal Stop ~~(ETK Compatibility)~~                            |
| trash       | junk phoneme                                                |
| exh         | devoiced exhale (either on it's own or as part of syllable) |
| axh         | voiced exhale (as part of syllable)                         |

The additional flags (for ENUNU) added to this hed:

| Flag | Purpose               |
|------|-----------------------|
| F    | falsetto              |
| H    | head voice            |
| SF   | soft                  |
| ST   | strong                |
| OPN  | open_wide_vowel       |
| CLS  | closed_narrow_vowel   |
| W    | whisper_devoiced      |
| S    | false_cord_fry_scream |
| G    | guttural_scream_growl |
| BR   | bright_resonance      |
| DR   | dark_resonance        |
| Y    | young_higher_formant  |
| O    | older_lower_formant   |
| T    | thin                  |
| R    | fry_rattle            |
| N    | nasal                 |
| HPY  | happy                 |
| SAD  | sad                   |
| MAD  | mad                   |
| 1    | additional_1          |
| 2    | additional_2          |
| 3    | additional_3          |

The table makes the `Edge` and `GlottalStop` phonemes more accessible.
Instead of typing "`・あ`" for "GlottalStop a" you can now type "`-あ`".
And for a vocal fry (`Edge`) you can type "`+あ`" or "`あ+`" instead of "`’あ`" or "`あ’`"
The table also adds full romaji support for an easier experience for non-native and non-speaking users.
