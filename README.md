## Do We Find
That They Rhyme?

A Corpus-Based Approach to Analyzing Phonological Similarity
Using Imperfect Rhymes
This project obtains song lyrics and anazlyes them to find patterns in perfect and imperfect rhyming.  The PDF titled Junior_Paper_Gillian_Rosenberg2 provides an extensive description and analysis of the project.

This repository contains two main components: a lyrics scraper and a rhyme collector. Lyrics_Scraper is a Python script (originally written in R by Kaylin Pavlik and converted to Python using ChatGPT) to obtain song lyrics from websites on the internet and save them in a CSV format. Rhyme_collector is a Python tool that processes the CSV file of song lyrics to identify perfect and imperfect rhymes. It then outputs a list of these types of rhymes along with their counts.

Features:
1. Lyrics_Scraper takes in a range of dates as input and outputs a CSV file with the lyrics of Billboard Hot 100 song lyrics from those years. Original Credit: The scraping functionality is based on a script by Kaylin Pavlik and has been modified to improve performance and compatibility with this project.

3. Rhyme_Collector: takes in a CSV file containing song lyrics and rhyming dictionary as inputs and outputs both perfect (exact matching sounds) and imperfect rhymes (approximate rhymes) and other data points about the rhymes. 

Usage: 
1. Use lyric_scraper.ipynb to fetch song lyrics and save them in a CSV file. Use rhyme_collector.ipynb to analyze the rhymes within the CSV file and generate the rhyme analysis.

Applications:
1. Linguists can use this data to explore theories of phological similarity. 
2. Poets and musicians can study how rhymes are used creatively in different genres.
3. Others can learn about data analysis for language processing.


NOTE: To run Rhyme_Collector, you must upload rhyming_dictionaries.pickle and billboard_lyrics. (rhyiming_dictionaries.pickle was taken from Popescu-Belis, Andrei, et al. "GPoeT: a language model trained for rhyme generation on synthetic data." Proceedings of the 7th Joint SIGHUM Workshop on Computational Linguistics for Cultural Heritage, Social Sciences, Humanities and Literature. Association for Computational Linguistics, 2023
