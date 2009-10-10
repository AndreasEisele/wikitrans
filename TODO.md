Near future
===========
Try getting the articles for JHU in a couple other languages, and running them through the sentence splitter:

Spanish http://es.wikipedia.org/wiki/Universidad_Johns_Hopkins
German  http://de.wikipedia.org/wiki/Johns_Hopkins_University
French  http://fr.wikipedia.org/wiki/Universit�_Johns-Hopkins
Czech   http://cs.wikipedia.org/wiki/Johns_Hopkins_University

The next steps will be:
* Run each sentence through Google's translation API, translating the foreign sentences into English, and the English sentences into the foreign languages.
* Design the simplest interface for editing the machine translated sentences, and incorporating the edited results back into our wikitrans database
* Design a nicer interface for the editing, perhaps similar to Google's "suggest a better translation"
* Have a mechanism for exporting the source documents and the (edited) translations in an XML format similar to the one used for the Urdu data that I sent to you.

Distant future
==============
Audit functions and screens