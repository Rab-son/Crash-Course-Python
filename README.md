# Crash-Course-Python
-> Be advised that the code has been tested in jupiter notebooks 

Word Cloud
-> Word Cloud is a data visualization technique used for representing text data in which the size of each word indicates its frequency or importance. Significant textual data points can be highlighted using a word cloud.

Problem Statement
    Create a "word cloud" from a text by procssing the text and return a dictionary that outputs the frequency of each words.

Criteria To Follow
  Input
    1. Processing the text
    2. Remove punctuation
    3. Ignore case and words that do not contain all alphabets
    4. Count the frequencies
    5. Ignore uninteresting or irrelevant words
    
  Output
    A dictionary is the output of the calculate_frequencies function. The wordcloud module will then generate the image from your         
    dictionary.
    
  approach
    1. Browse and upload a text to be processed
    2. Remove puntuations and normalize the letters
    3. Create a set to store the uninteresting words
    4. Create a dictionary that uses a word as a key and frequencies of the word as a value
    5. Use WordCloud framework to generate a image of world cloud
