# Maths Dictionary

As part of an ongoing project on categorical translation, I'm organising an open-source multilingual dictionary of mathematical terminology.
You can see the live website version at https://thosgood.com/maths-dictionary/ .

## Todo

- **here's a nice submission method idea:**
    + checkboxes for "languages you would like to translate from"
    + checkboxes for "languages you would like to translate to"
    + loop through entries that have an entry in one of the "from" languages and no entry (or an empty entry) in one of the "to" languages
    + when you're bored/there are no more, show a recap, and then have a "submit button"
- script to fill in all the missing languages with empty strings
    + **for both nouns and adjectives**
- **a way to inherit adjectives from another entry!**
    + e.g. give a list of hashes of adjectives that "group" should inherit from "ring"
- language .json files should have LTR/RTL information
    + this should be used when displaying adjectives!
    + should also be reflected in `text-align` in the css
- fix errors with the `DE` entries
    + think about how to deal with grammatical case...
- regional variations?
    + especially with `ES`
- add plurals of nouns (and thus adjectives)
- link each entry (incl. adjectives) to a definition? wikipedia page or something...
    + **wikidata**
- get language selectors (in `index.html`) from the language `.json` files
    + should also get endonyms from there too

(<https://www.freeformatter.com/json-escape.html> is useful)

## Contributors

TJF, Elena Badillo Goicoechea, Pedro Tamaroff, Enric Cosme Llópez, Dilan Demirtaş, Thibaut Benjamin, Fatimah Ahmadi, Övge, Samuel Lelièvre, Besnik Nuro
