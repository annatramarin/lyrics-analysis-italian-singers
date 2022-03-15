# lyrics_analysis_italian_singers
Lyrics analysis and comparison of three Italian singers - Fabrizio De André, Giorgio Gaber and Francesco Guccini.

STEP 1 - Web-scraping and frequency distributions

- Scraped the web to obtain the lyrics of three Italian singer-songwriters, in order to create one corpus per songwriter
- Created a frequency distribution to see which words are most frequent in their lyrics production

STEP 2 - Spearman correlation

- Compared the rankings to see the correlation between the corpora
- Removed stopwords from the corpora
- Recalculated the correlation
- Found common words among the three singers
- Recalculated the correlation between common word frequencies (with and without stopwords)

STEP 3 - Weirdness Index: how "typical" is a word in a songwriter's lyrics production?

- Calculated the weirdness index by taking into account the obtained corpora and a more generic corpus from Wikipedia
