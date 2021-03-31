
### Results produced with PMI and fastText

<b>Distances_FT.txt:</b> Word similarities for the words of interest extracted from the binary fastText results.

<b>EmotionsAndGenre_FT.tsv:</b> Emotion words and ten semantically most similar words (i.e., words with the highest cosine similarities) to each of them according to fastText. The emotion verbs and their derivatives are separated according to the genre of the document in which they appear. The network LoveNumbers_FT has been produced from this data.

<b>emotionsAndGenre_PMI.csv:</b> Emotion words and their closest collocates (i.e., words with the highest PMI scores) according to PMI. The number of collocates depends on their PMI scores, as the collocates with scores below 0.001 are discarded. The emotion verbs and their derivatives are separated according to the genre of the document in which they appear. The network LoveNumbers_PMI has been produced from this data.
