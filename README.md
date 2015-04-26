## Telugu Language Research Project

Gathering data for a widely spoken but low resource language to help the statistical machine translation community

## Writeups
Every subdirectory (as listed below with point total adjacent) contains a file, writeup.md, that answers the questions posed at [http://mt-class.org/penn/language-research.html] for each extension. Each directory also contains a README that specifies it's contents

## File Structure

### Directories
`bilingual_dictionary/` [1pt] contains a script to obtain bilingual information from an online source and save it to files as it goes. Another script then combines the files to make one large dictionary file

`language_identification/` [2pts] contains a script that determines the likelyhood that an input was in telugu.

`monolingual_data/` [1pt] contains directions that describe how to access widely-available Telugu texts

`transliteration/` [1pt] contains a script to transliterate from Telugu script to romanized-Telugu text

`twitter-streamer/` contains the script used to obtain a csv file of tweets written in Telugu

`twitter-data/` [2pts] contains the .csv file of tweets authored from a region that speaks predominantly Telugu. It also contains a .txt file of the metadata associated with those tweets

### Files
`CoreRequirements.md` contains a brief summarization of the morphology and syntactical structure of Telugu

`InitialResearch.md` contains initial research conducted by Luke 'The MT TANK' Carlsson and his Swedish harem

