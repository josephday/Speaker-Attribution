# Speaker-Attribution
Speaker Attribution using Markov Models -- assignment description can be located here https://www.classes.cs.uchicago.edu/archive/2016/winter/12200-1/pa/pa4/index.html

Using Markov Models generated from text patterns of numerous speeches of known origin from two politicians A and B, identify the most likely origin of the third speech, A or B. 

Hash_Table.py -- defines class Hash_Table to be used in Markov.py

Markov.py -- Using Hash_Table class from Hash_Table.py, define class Markov, a kth order Markov model from string s.
Contains functions for calculating the probability that a third string came from politican A or B using Markov Model's generated from their aggregated speeches.

speeches -- folder containing various training and test speeches
