# Pixiv-Assistant Dictionary

This is the repository for the standard translation dictionary (potentially dictionaries) for the pixiv-assistant greasemonkey user script. The content was originally sourced from Couchy's wonderful Pixiv Translation Plus (PTP) extension. Unlike PTP Pixiv-Assistant updates directly from this github repository so it can remain relevant as the culture shifts without the author's personal attention.

##Contributing

Pull requests are welcome as long as the (minimal) format rules below are obeyed. 

While I am interested in maintaining the user script, I'm not interested in being the arbiter of what goes into the standard translation file. I feel this should be a community-owned piece of the project which is part of why it exists in a separate organization. I won't have the time to maintain the dictionary files myself, if you are interested in coming on as the maintainer of this project please let me know.  

##Format

A dictionary is stored as a single JSON translation file. The Japanese characters are the keys of the JSON Object while the English translations are the values. Pull requests are welcome to add to the common source dictionary, please indent entries with a single tab character. I'm not interested in enforcing alphabetical order for the kanji -- honestly I don't know if such a thing is well defined.

If you are adding entries in bulk, don't list them all but rather explain where they came from if applicable.

*Do Not* automatically translate a tag list and feed that through a PR directly. Machine translation has many faults and poorly translated submissions may be rejected.

##Other languages

Other languages (besides English) may be included if there is enough demand.
