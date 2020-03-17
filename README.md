# newspaper_odia
Odia language and stopwords added to the existing Python newspaper3k library. If anyone wants to further modify 
and enhance the functionality then I can add them to my contributer list.

Add a new language
1. Push up a stopwords file in the format of stopwords-<2-char-language-code>.txt in newspaper/resources/text/.
2. Provide a way of splitting/tokenizing text in that foreign language into words.
3. If sentence separator is other than full stop then replace it with full stop in split_sentences function of nlp.py
4. Finally, add the new language to the list of available languages in the following files:

            README.rst
            docs/index.rst
            docs/user_guide/quickstart.rst
            newspaper/utils.py
