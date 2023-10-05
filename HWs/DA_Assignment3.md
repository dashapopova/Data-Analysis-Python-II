### Assignment 3

Please send an .ipynb file, a .py file or a link to a public github repository with your file to daschapopowa@gmail.com

Due October 12th, 21:00, for max. 8 points

2 bonus points if completed in-class, October 5th, by 21:00

6 points max. for late submission, Oct 19th, by 21:00

#### Task 1: Initial Consonant Clusters \[6 points\]

Your task is to show me how to use pattern matching to investigate the distribution of word-initial consonant clusters in *Alice* ([alice.txt](https://github.com/dashapopova/Data-Analysis-2023/blob/main/week2/alice.txt)). The basic question is how frequent different kinds of initial consonant clusters are. 

An initial consonant cluster is a sequence of consonants (not interrupted by vowels) at the beginning of a word. E.g., *crouton* has an initial consonant cluster *cr*, *flamingo* has an initial consonant cluster *fl*, *mimosa* does not have an initial consonant cluster, it starts with a single consonant. 

A challenge here is that English orthography only indirectly reflects the phonology. First, you must deal with silent letters. These include cases like *know* or *gnostic* where *k* and *g* are silent. Another issue to wrestle with is that sometimes a single consonant is written with several letters, e.g. [θ] as in *thimble* or [ʃ] as in *show*, etc. Finally, there are cases where the same letter (sequence) has multiple pronunciations. For example, *c* is pronounced [s] in *city*, but [k] in *coat*. Similarly, *ch* is pronounced [tʃ] in *church*, but [k] in *chord*. Note that sometimes the difference is predictable, as in the case of *c*, but sometimes it is not, as in the case of *ch*. You should set aside the mapping of orthography to precise phonological forms, except insofar as you need to decide what a cluster is.

You will need to do the following (or something which is analogous to the following):

1. tokenize alice.txt -- 0,5 point;
2. apply the `gutenberg_file_wc` function (from hw2) to alice.txt to get the word counts -- 0,5 point;
3. try to search for (word) initial consonant clusters using regular expression(s) (Don't forget to `import re` at the beginning of your program) -- 3 points;
4. print the counts for all the clusters that you have identified, you should end up with a dictionary like `{'pr': 26, 'sp': 15,...}` -- 1 point; 
5. print the total number of different clusters you've identified, e.g., 10 clusters or 40 clusters -- 0,5 point;
6. print the list of all the clusters in the alphabetical order, ['bl', 'br',...] -- 0,5 point;

#### Task 2: \[2 points\]

a. Take the poem: https://github.com/dashapopova/Data-Analysis-2023/blob/main/week4/Lukomorje.txt 
(If you are not a native speaker of Russian, you can take any poem in English)

b. Change the number of the nouns and do the agreement, e.g, the original 

*У лукоморья дуб зелёный;


Златая цепь на дубе том:

И днём и ночью кот учёный

Всё ходит по цепи кругом;* 

should become 

*У лукоморья дубы зелёные;

Златые цепи на дубах тех:

И днями и ночами коты учёные

Всё ходят по цепям кругом;*.

Do your best, the result won't most likely be perfect, but as long as you use morphological and syntactic parsing and comment on what problems remain and why, you will get the full grade.

