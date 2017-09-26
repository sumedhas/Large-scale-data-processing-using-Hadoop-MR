DIC Lab 4


Part 1: What’s trending?: Wordcount on tweets

Process:
1) Collected tweets using R and cleaned them.
2) Processed tweets.txt file in Hadoop
3) Saved output from MapReduce
4) Created a WordCloud online using output from MapReducer.

Contents: WordCount.java, class files, Output file, jar file, WordCloud.jpeg file, Part1.ipynb file(R code).

Part 2: Word co-occurrence on tweets

Process: 

I) Pairs:
1) Wrote a program to implement Pairs in java.
2) Run this program for tweets collected from Part 1.
3) Output saved into Pairs folder.

Contents: Pairs.java, class files, Output file, jar file.

II) Stripes:
1) Wrote a program to implement Stripes in java.
2) Run this program for tweets collected from Part 1.
3) Output saved into Stripes folder.

Contents: Stripes.java, class files, Output file, jar file.


Part 3: Featured Activity 1: Wordcount on Classical Latin text

Process:
1) Wrote a MapReduce program in java for using the Lemma file.
2) Created a HashMap for Lemmas
3) Wrote a Mapper class to emit Word, Location Pairs with count
4) Wrote a reducer class to compare word with lemmas and emit Lemmas, Location Pairs with count as well.

Output Format: 
<Word> <Locations> count:x
<Lemma1> <Locations> count:x
<Lemma2> <Locations> count:x
<Lemma3> <Locations> count:x

Contents: Lemma.java, class files, Output file(Contains output for various number of input files), jar file, Time.txt file showing execution time for different number of inputs.

Part 4: Featured Activity 2: Word co-occurrence among multiple documents.

Process:
I) For n = 2(Bigrams):
 
1) Created a HashMap for Lemmas
2) Wrote a Mapper class to emit WordPair(2 words), Location Pairs with count
3) Wrote a reducer class to compare WordPair with lemmas and emit Lemmas, Location Pairs with count as well.

Contents: word_co.java, class files, Output file, jar file.

II) For n = 3(Trigrams):
1) Created a HashMap for Lemmas
2) Wrote a Mapper class to emit WordPair(3 words), Location Pairs with counti

Contents: word_co_tri.java, class files, Output file, jar file.
