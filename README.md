# Lyrics_generation
Automatically generates song lyrics of a given genre.

This model used ngrams to model the training corpus of lyrics. It then chooses the next word from a selected few probable words. 

# Description of data
The song data required for this project have been obtained from 'https://www.kaggle.com/gyani95/380000-lyrics-from-metrolyrics/home' and have been cleaned and saved as text files for learning the model

# Parameters to set
 1. Number of words in the ngrams ('n')
 2. Genre of the lyrics you want ('genre')
 3. Number of most probable words you want to sample from ('num_sample')
 4. number of words in the generated lyrics ('num_lyrics')
 5. Seed lyrics used to create the rest of the lyrics. (Should be of length n-1) ('seed')
 
 
