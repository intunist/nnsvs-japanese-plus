# nnsvs-custom-japanese
Custom HED and Table for DYVAUX Japanese

These are based on the HED files included with NNSVS.
All this does is add support for DYNVAUX's own selection of ENUNU flags along with a few extra phonemes.

These HED files should be compatible with any dataset that is compatible with the ENUNU-Training-Kit HED files.

Additional Phonemes compared to standard NNSVS HED:

| Phoneme     | Purpose                                                     |
|-------------|-------------------------------------------------------------|
| Edge        | Vocal Fry (ETK Compatibility)                               |
| GlottalStop | Glottal Stop (ETK Compatibility)                            |
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
| B    | bright_resonance      |
| D    | dark_resonance        |
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
