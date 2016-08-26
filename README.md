# Pixiv-Assistant Dictionary

This is the repository for the standard translation dictionary for the pixiv-assistant chrome extension. The extension updates directly from this github repository so it can remain relevant as the culture shifts and contributions grow without the author's personal attention.

##Contributing

Pull requests are welcome as long as the (minimal) format rules below are obeyed. 

##Format

A dictionary is stored as a single JSON translation file. The Japanese characters are the keys of the JSON Object while the English translations are the values. Pull requests are welcome to add to the common source dictionary, please indent entries with a single tab character. The dictionary is lexigraphically sorted by the english translation. The javascript  that loads the file won't care, this is for the sake of human readability.

Commit comments are appreciated but not strictly necessary. If you have a source for your translations, please do provide that information.

*Do Not* automatically translate a tag list and feed that through a PR directly. Machine translation has many faults and poorly translated submissions may be rejected.

Translations may be contested by in the Issues section of the project.

##Other languages

Other languages (besides English) may be included if there is enough demand.
