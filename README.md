Farsi to Finglish transliterator
===========

**Note:** This project is old and no longer maintained.

Farsi to Finglish converter is a Django based application that uses vowel represenations (in Persian) from Dehkhoda dictionary (www.loghatnaameh.com) and fa.wiktionary.org (currently as backup) and tries to guess better translations using google suggestions.

Static database for already translated words are stored in worddb.xml
After installing this application on your django server, you can see the translation of words from your django url using GET request with word=[word in Persian] which [word in Persian] is the word that you want to translate to Finglish in Farsi.
There's a plugin for chrome in https://chrome.google.com/webstore/detail/farsi2finglish-translator/fjgndmomllkaoodpcclfeiamjbcncbmc which you can use to select words in Persian and look for the Finglish translation in your browser (special thanks to Garret Verstegen).
