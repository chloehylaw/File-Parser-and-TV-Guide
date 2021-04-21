COMP 249 Assignment 4

 Chloe Hei Yu Law
 COMP 249 Assignment #4
 Due Date: April 20, 2021
 
Part 1: ArrayList & File I/O
In this part, you are required to write a program that will accept any text file, as input, and creates a file parser
that processes all the words found in that input file based on the below mentioned rules. The input file may have
zero or more words, as well as a specific limited set of other characters /punctuation that are used in a specific
and predetermined manner. In particular, the text file may contain any characters from the ASCII character set.
You should use replaceAll("[^a-zA-Z0-9]", "") to remove all non alphanumeric characters from the text.
You are required to implement a program that will take any such text file as input and create three files which will
contain the output from the file parser based on the below mentioned three criteria. All three files must have the
total word count available on the very first line.
1. First file, to be named “vowel_verbiage.txt”, would contain all the words from the input file which have
more than three vowels in them. For example, the word “volunteer” has 4 vowels: o, u e, e.
2. Second file, to be named “obsessive_o.txt”, would contain all the words from the input file which start
with an “o”.
3. Third file, to be named “distinct_data.txt”, would contain all the distinct words from the input file. For
instance, if “the” appears 50 times, it would appear only once in the file. 

Part 2: Linked Lists
In this assignment, you will design and implement a TVGuide which will determine if a user can watch a specific
show based on shows he/she is currently watching. You are given two files, namely, TVGuide.txt containing
information about various TV shows, and Interests.txt which contains information about the shows a user is
interested in. You will parse these files to extract TV shows information and will produce an outcome for each of
the show a user wants to watch. The outcome for each show could be one of the below mentioned options where
X represents showID, S represents start time and E represents end time.
a) User can watch show X as he/she is not watching anything else during that time.
b) User can’t watch show X as he/she is not finished with a show he/she is watching.
c) User can’t watch show X as he/she will begin another show at the same time. 

 
 
