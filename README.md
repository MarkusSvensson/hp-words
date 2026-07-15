# Ord från högskoleprovet
Swedish Hogskoleprovet ORD word dataset in CSV format. 

Not full dataset. More might be added later.
Most of the data is gathered and compiled with help from AI. There might be errors. Please help by reporting if you find any problems in the data.

Svenska: Dataset med ordkunskapsdelen av högskoleprovet. Historisk data. 
Sökord: ord, hp, ord, gamla högskoleprov, facit, databas, år

## Files

- `hp_words.csv`: Main dataset.

## Format

The CSV file uses semicolon-separated values with the following columns:

- Year (the year of the test that included this word)
- Occasion (first or second test that year)
- Word (the word to which you should find the synonym)
- Option1 (options the testee can choose from)
- Option2
- Option3
- Option4
- Option5
- CorrectAnswer (one of the options that is the right answer)

Example:
1983;2;dogm;upprop;lärosats;utmärkelse;befallning;utmaning;lärosats
