# Maths Dictionary

As part of an ongoing project on categorical translation, I'm organising an open-source multilingual dictionary of mathematical terminology.
You can see the live website version at https://thosgood.com/maths-dictionary/ .


## Contributors

This dictionary is only as good as its entries, and for this there are many people to thank. Below is a list (in chronological order) of people who have contributed towards this project.

> TJF, Elena Badillo Goicoechea, Pedro Tamaroff, Enric Cosme Llópez, Dilan Demirtaş, Thibaut Benjamin, Fatimah Ahmadi, Övge, Samuel Lelièvre, Besnik Nuro, Natasha Crepeau, Caio Oliveira, Nowras Ali, Maciek Ogrodnik, Matteo Capucci, Jone Uria Albizuri, Ralph Sarkis, Clément Spaier, Jordan Emme, Phil Pützstück, Lucas Viana, Louis Loiseau, Daniele Palombi, Bartosz Milewski, Dariush Moshiri, Hamid reza Khajoei, 李昊达, Özgür Esentepe, Shota, Sven-Ole Behrend, Lukas Graf, Byeongsu Yu, Manuel Hinz, Markus, Zhixuan Yang, Ísabel Pirsic, ruth, Cihan Bahran, ならずもの, Heiko Braun, Yiqi Xu.


## To-do

### Dictionary

***maybe...* there shouldn't be any adjectives; everything should be its own entry; "adjectives" could link back to their "root"**

- should be a way to indicate that there is no space between a noun and its adjective (e.g. Modellkategorie in DE)
    + **use the `"join": Bool` key for adjectives** (e.g. `0ebe035f/06440212`)
- support for multiple atoms
    + e.g. regional variations, or just synonyms
- a way to inherit adjectives from another entry!
    + e.g. give a list of hashes of adjectives that "group" should inherit from "ring"
    + **but** should also have "general" fallback, e.g. if I want to write "differentiable stack", then I can modify "stack" (or literally anything!) by "function.differentiable", i.e. coercion
        * this would give a "hm we can't guarantee anything" warning
- add plurals of nouns (and thus adjectives)
    + will also need cases... (for e.g. `DE`)
- think about verbs...


### Website

- make language header row sticky at top
- **search should also search through adjectives**
- "expand all nouns" button


## Existing dictionary resources

(<https://www.freeformatter.com/json-escape.html> is useful)

- [http://diposit.ub.edu/dspace/bitstream/2445/9703/6/matematiques2.pdf](http://diposit.ub.edu/dspace/bitstream/2445/9703/6/matematiques2.pdf)
- [https://www.cocentaina.es/upload/files/serveis-municipals/aviva/archivo1927.pdf](https://www.cocentaina.es/upload/files/serveis-municipals/aviva/archivo1927.pdf)
- [https://en.wikipedia.org/wiki/Glossary_of_algebraic_geometry](https://en.wikipedia.org/wiki/Glossary_of_algebraic_geometry)
- [https://www.lambdabetaeta.eu/ctgr.html](https://www.lambdabetaeta.eu/ctgr.html)
- [https://www.euskaltzaindia.eus/dok/iker_jagon_tegiak/Matematika_Oinarrizko_Lexikoa.pdf](https://www.euskaltzaindia.eus/dok/iker_jagon_tegiak/Matematika_Oinarrizko_Lexikoa.pdf)
- [http://math.huji.ac.il/~amit/hebrew_geometric_dictionary_2.pdf](http://math.huji.ac.il/~amit/hebrew_geometric_dictionary_2.pdf)
- [https://ru.wikipedia.org/wiki/Глоссарий_алгебраической_геометрии](https://ru.wikipedia.org/wiki/%D0%93%D0%BB%D0%BE%D1%81%D1%81%D0%B0%D1%80%D0%B8%D0%B9_%D0%B0%D0%BB%D0%B3%D0%B5%D0%B1%D1%80%D0%B0%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%BE%D0%B9_%D0%B3%D0%B5%D0%BE%D0%BC%D0%B5%D1%82%D1%80%D0%B8%D0%B8)
- [https://es.wikipedia.org/wiki/Anexo:Glosario_de_teoría_de_anillos](https://es.wikipedia.org/wiki/Anexo:Glosario_de_teor%C3%ADa_de_anillos)
- [https://arxiv.org/pdf/math/0609472.pdf](https://arxiv.org/pdf/math/0609472.pdf)
- [https://www.emaths.co.uk/index.php/teacher-resources/other-resources/english-as-an-additional-language-eal/category/russian](https://www.emaths.co.uk/index.php/teacher-resources/other-resources/english-as-an-additional-language-eal/category/russian)
- [https://dict.tu-chemnitz.de/de-en/lists/math.html](https://dict.tu-chemnitz.de/de-en/lists/math.html)
- [https://courses.dcs.wisc.edu/wp/readinggerman/](https://courses.dcs.wisc.edu/wp/readinggerman/)
- [http://euclid.mas.ucy.ac.cy/~georgios/bookfiles/dict1.pdf](http://euclid.mas.ucy.ac.cy/~georgios/bookfiles/dict1.pdf)
