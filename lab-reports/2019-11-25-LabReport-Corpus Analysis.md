# Lab Report: Corpus Analysis

#### ADRIANA MESSINA

## Process Description

Load the various libraries we will be using (tidy verse, tidytext, tokenizers)
Working with a large set - 150 of longest scifi books in the Gutenberg project collection
Using computational methods to looks at trends across a lot of items

Sentiment analysis - sentiment dictionary algorithms assign each word a level of emotional valence
It's debated which algorithm best reflects actual language - How you code data determines the results at some level
Numerical scale from most negative to most positive, words are assigned to different emotional categories (irony can get confusing)

Creating a new value of sentiment - classifies the appearance of each word with a certain sentiment, why do certain things belong in their category? How are dictionaries constructed and what assumptions do they make?
Gets rid of stop words

Can filter by sentiments - in our case, anger
What anger words come up most often across the entire corpus (force, death, gun, etc)
Sort books by which ones contain the most angry words (doesn't account for book length

Created a ratio of angry words to other words to list proportion of angry words to total text length (EmoRatio)
Store the 9 angriest books in a new variable

Redid this process with a  different sentiment - I chose "disgust" and used it to find the books that use the most "disgust" words

Topic Modeling - latent dirichlet allocation (LDA), any collection of documents is made up of topics
Finding out what those topics are - words that belong in the same topics often appear next to each other
Algorithm cycles through many times, looking for words that appear together to create a probability analysis that words belong together
Typically works best with smaller chunks of corpus where there might be more semantic meaning
Dividing up our Gutenberg scoff books into chunks

Create a document term matrix (DTM) - lists every document on one axis and every word on the other, filling in the intersections with the count of each term in each document, gives us a way to calculate how likely it is that words will appear together

Took turns running the LDA code
Choosing what we want to explore - specific words, topic comparisons, etc.

How these technologies change the idea of the textual object - text as data that can be analyzed, put into an algorithm, organized and graphed, etc.
Digitized text can become very abstract

## Observations

In the next section of each report, you should in **2-3 paragraphs** move from a literal description of what you did in the lab to a more conceptual set of observations. In brief, you want to home in on those aspects of the lab that raised questions or prompted new insights into the textual technology we investigated in the lab activity. What new ideas occurred to you while working? What surprised, delighted, or frustrated you?

## Analysis

The final section of each report should bring your work in the lab into direct, critical conversation with our readings. In **_3-4 paragraphs_**, you should connect your lab observations to ideas from readings assigned _in the given lab unit_. This prose need not be as formal as a research paper, but it should demonstrate careful thought and preparation. You should integrate the readings explicitly, if possible through direct quotation. Use this writing to experiment with intellectual pairings you think might be generative to your larger thinking and help you prepare for the class’ Unessay projects. Think of your lab reports as an evolving research paper, and take them as seriously as one.