### Networks and figures produced during the research

### Figure1.gephi

Contains the following graphs:

<b>PMI_translated and FT_translated</b>

- Lexical networks of Akkadian words created using PMI scores / cosine similarities from fastText as edge weights. The data derives from Jauhiainen et al. (2021), Lexicographical Portal—The Dataset, http://doi.org/10.5281/zenodo.4646662. Nodes are labelled according to the English translations of the Akkadian words.
- Also available as gexf files

<b>matu_PMI and matu_FT</b>

- Ego networks of the word mâtu, "to die," at a depth of 1
- Node size (25-50) corresponds to the weighted degree of the nodes. 
- The layout of the nodes was created with the ForceAtlas2 algorithm.

<b>matu_PMI_filtered and matu_FT_filtered</b>

- Matu_PMI_filtered includes the target word mâtu and six words with the highest PMI scores (labû and šatānu have the same score) and matu_FT_filtered five words with the highest cosine similarities. The word qātīšu has been excluded from matu_PMI_filtered because its occurrence is a result of a lemmatization mistake in Oracc (the lemma should be qātu).
- The final location of the nodes has been manually adjusted. 

<b>Figure 1</b>

Examples of linguistic networks created using PMI scores (A) and cosine similarities from fastText (B) as edge weights. 

- Matu_PMI_filtered and matu_FT_filtered shown side by side
- While PMI scores and cosine similarities were used as edge weights in the analysis of the graph, all edges have a thickness of 2 in the printed figure and the pdf file for the sake of clarity.
- Also available as a pdf file


### EmotionsAndGenre.gephi

Contains the following graphs:

<b>LoveNumbers_PMI and LoveNumbers_FT</b>

- LoveNumbers_PMI is created using PMI scores as edge weights and LoveNumbers_FT is created using cosine similarities from fastText as edge weights
- Each emotion word is connected to the ten best PMI collocates (the highest PMI scores) or the ten most similar words according fastText (the highest cosine similarities)
- Râmu and its derivatives are colored according to the genre, all other nodes are gray
- Node size: weighted degree 25-50
- The thickness of an edge indicates its weight
- ForceAtlas2 layout: scaling 1.0, gravity 1.0, LinLog mode on, prevent overlap on, edge weight influence 1.0
- Label adjust layout
- Also available as gexf files

<b>Figures 2-7</b>

Ego networks of râmu and its derivatives in different genres, created using PMI scores and cosine similarities from fastText as edge weights.

- These ego networks are extracted from the graphs LoveNumbers_PMI and LoveNumbers_FT.
- The ego networks are created at a depth of 1, including emotion words at a depth of 2. In the Gephi project, the nodes belonging to the ego networks of depth 1 are indicated with "1" in the attribute "Ego network depth 1."
- The distances between nodes have been adjusted for clarity and readability.
- In the printed figures and pdf files, all edges have a thickness of 1 for the sake of clarity. The original edge weights are retained in the Gephi project.
- In the printed figures and pdf files, the target words (râmu and its derivatives) are in bold and the indirectly connected emotion words are in italics.
- Also available as pdf files

<b>Figure 8</b>

Network showing the clustering of emotion words according to the genre in which they appear, created using cosine similarities from fastText as edge weights.

- The network was produced from LoveNumbers_FT. In the figure, only the emotion words are displayed, and they are labelled according to the genre in which they appear (2 astrological/astronomical; 3 grant/decree/gift; 4 legal transaction; 5 letter; 7 literary; 8 miscellaneous; 9 omen/divination; 10 prayer/ritual/incantation; 11 royal inscription; 12 scholarly).
- In the printed figure and pdf file, the word râmu and its derivatives are underlined. 
- Also available as a pdf file
