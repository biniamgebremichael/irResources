# Resources for Information Retrieval for Amharic and Tigrinya Languages
1. Stop words
2. Transliteration using soundex algorithm
3. Partial stemmer (prefix and suffix removal)

## Usage: string normalization steps
1. replace "'" with " እ" 
2. remove punctuations and non geez characters ( /[\x{135D}-\x{1368}]+/u/ )
3. remove stop words
4. transliterate to SERAX
5. remove suffix (if remaining length >2 )
6. remove prefix (if remaining length >2 )
