# Brief TODO list

*P* = pending; *W* = working no it; *D* = done; *B* = blocked (needs
discussion, etc.); *X* = not implementing.

- *D* Basic table loading & parsing
- *D* Table inheritance
- *D* Multiple recursive inheritance
  - *D* Inherit map
  - *D* Inherit ignore
  - *D* Inherit double cap configuration
  - *X* Inherit hooks
- *D* Ignore list (R2S)
- *D* Basic transliteration in both directions
- *D* Basic REST API
- *D* Basic UI
- *D* Life cycle hooks for plugins
- *X* Regular expressions in ignore lists
- *D* Word boundaries
  - *D* Define word boundary characters per config
  - *D* Mark end-of-word and beginning-of-word characters
- *D* Optimize token lookup
  - *D* Break loop early based on alphabetical order
  - *X* Ignore word break characters
- *D* Capitalization
  - *X* Separate capitalization function
  - *D* Capitalize ligated letters (e.g. Cyrillic T͡͡S)
  - *D* Option for capitalizing first word, all words, unchanged
- *D* API documentation
- *D* Config file documentation
- *D* Hooks documentation
- *D* Rebranding (ScriptShifter)
- *D* Tests
  - *D* Config parsing
  - *D* Transliteration
  - *D* REST API
- *W* Complete conversion of existing tables to YAML
  - *X* Arabic
  - *P* Armenian
  - *D* Asian Cyrillic
  - *D* Azerbajani
  - *D* Belarusian
  - *D* Bulgarian
  - *D* Chinese
  - *D* Ethiopic
  - *D* Georgian
  - *W* Greek
  - *P* Hebrew and Yiddish
  - *W* Hindi
  - *X* Japanese
  - *D* Kazakh
  - *P* Korean
  - *D* Kyrgyz
  - *D* Mongolian
  - *P* Persian
  - *P* Pushto
  - *D* Russian
  - *D* Serbian + Macedonic
  - *D* Slavonic
  - *D* Tajik
  - *D* Tatar
  - *P* Thaana
  - *D* Turkmen
  - *D* Ukrainian
  - *P* Urdu
  - *D* Uzbek
- *P* Additional languages not in legacy tables, but in other software
  - *D* Arabic S2R (ArabicTransliterator)
  - *B* Japanese (?)
  - *B* Korean (K-romanizer)
