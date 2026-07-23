# Top100IMDB
An end-to-end data analysis project: taking a deliberately corrupted IMDB dataset from raw, unusable text to a validated, analysis-ready table, then using it to answer eight analytical questions about what drives a film's rating, revenue, and reputation.

The source file, `messy_IMDB_dataset.csv`, contains 100 highly-rated films
spanning **1937 – 2020**, with fields for title, release date, genre,
runtime, country, content rating, director, box-office income, vote count,
and IMDB score. It arrived in a badly damaged state — inconsistent
encodings, multiple date formats, and numeric columns riddled with
formatting garbage — none of which could be analysed as delivered.

The project has two halves. The first is a **rigorous cleaning pipeline**
that repairs every column while documenting each judgment call. The second
is an **exploratory analysis** that treats the cleaned data as trustworthy
and investigates the relationships between a film's characteristics and its
success.

A guiding caveat runs through the entire analysis: **this is a curated list
of already-acclaimed films, not a random sample of cinema.** Every finding
below describes patterns *among top films*, and cannot be generalised to
movies as a whole.
