# Perfect-and-imperfect-rhyme-tracker
This project obtains song lyrics and anazlyes them to find patterns in perfect and imperfect rhyming.  

This repository contains two main components:

Lyrics Scraper: A Python script (originally written in R by Kaylin Pavlik and convert to Python using ChatGPT) to obtain song lyrics from websites on the internet and save them in a CSV format.
Rhyme Analyzer: A Python tool that processes the CSV file of song lyrics to identify perfect and imperfect rhymes. It then outputs a list of these types of rhymes along with their counts.
Features:
1. Lyrics Scraper
Input: Song title and artist name (or other search parameters, depending on source).
Output: CSV file with the lyrics of the specified songs.
Original Credit: The scraping functionality is based on a script by [Author] and has been modified to improve performance and compatibility with this project.
2. Rhyme Analyzer
Input: CSV file containing song lyrics.
Rhyme Identification: Detects both perfect (exact matching sounds) and imperfect rhymes (approximate rhymes).
Rhyme Count: Displays a list of rhymes found and the count of each rhyme type.
Usage:
Scrape Lyrics: Use the lyrics_scraper.py to fetch song lyrics and save them in a CSV file.
Analyze Rhymes: Use the rhyme_analyzer.py to analyze the rhymes within the CSV file and generate the rhyme analysis.
Applications:
Songwriters and lyricists can explore rhyme structures in existing songs.
Poets and musicians can study how rhymes are used creatively in different genres.
Data analysis for language processing in song lyrics.
