# Pixiv-Assistant Dictionary

This is the repository for the standard translation dictionary for the pixiv-assistant chrome extension. The extension updates directly from this github repository so it can remain relevant as the culture shifts and contributions grow without the author's personal attention.

##Contributing

Pull requests are welcome as long as the (minimal) format rules below are obeyed. 

###Format

A dictionary is stored as a single JSON translation file. The Japanese characters are the keys of the JSON Object while the English translations are the values. Pull requests are welcome to add to the common source dictionary, please indent entries with a single tab character. The dictionary is lexigraphically sorted by the english translation. The javascript  that loads the file won't care, this is for the sake of human readability.

###Commits
Commit comments are appreciated but not strictly necessary. If you have a source for your translations, please do provide that information.

###Human Translation Only
*Do Not* automatically translate a tag list and feed that through a PR directly. Machine translation has many faults and poorly translated submissions may be rejected. However, you are more than welcome to use machine translation to arrive at an understanding of the most appropriate translation especially as a non-native speaker. 

###Contesting a translation
Translations may be contested by in the Issues section of the project. Explain why you feel the translation is not accurate and try to suggest an alternative. 

##Other languages

Other languages (besides English) may be included if there is enough demand.
