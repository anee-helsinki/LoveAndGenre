## Oracc data used for the analysis of emotion words in Akkadian texts

The corpus was extracted from the JSON files downloaded from the Open Richly Annotated Cuneiform Corpus (http://oracc.museum.upenn.edu) in February 2019. For extracting the words from those files we used a modified version of a script that was originally composed by Niek Veldhuis (https://github.com/niekveldhuis/ORACC-JSON/blob/master/json-corpus.ipynb).

Each file contains a word per line. Each line starts with a document number, line number, and word number on the line. After the word form, different metadata of the word in question is given.

E.g., suhu/Q006206.6.2	form:{GIŠ}TUKUL.MEŠ	lemma:kakku	gw:stick	wclass:N	norm:kakkī	sense:weapon epos:N lang:akk	signs:𒄑𒆪𒈨𒌍

lemma = dictionary form; gw = guide word (translation of the dictionary form); wclass = word class of the dictionary form; norm = normalization (transcription) of the word; sense = translation of the transcription in context; epos = word class of the word in context; lang = language of the word; signs = the transliteration converted to cuneiform signs
