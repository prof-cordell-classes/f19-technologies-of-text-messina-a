# Lab Report: Text as Data

#### ADRIANA MESSINA

## Process Description

-Just tex that we're working with, making a new code box is just three back ticks and a curly bracket. You can do the same things you would with other text, can delete, can copy and paste, etc. 

-Console is where everything happens

-can run individual lines by having the curer on a line and clicking command enter. will run that one line of code. 

-print - command to display the text after, technically called the function, displays it to the console. 
-function, little bundle of code that does a thing 

- in r, to load a package, you 'summon their library'. looking at library)tidy verse)
-Barton is a variable, in r a thing gets attached to a variable with the syntax 'barton<--'
-tibble - makes a table like data structure. the info in (" ") is where the information is coming from. it's putting it into barton (barton<--)
-Barton is an arbitrary name. Barton is not a person. 
-Storing it so I can do something with it. 

- not necessarily bringing something into r studio for us to read it, there are better ones for it. 

- can also use an equals sign instead of the arrow.

- not making permanent changes in this place. Nothing is changing at the source, not making files on our hard drive. Would have to export it to do that. 

- can overwrite this data in Barton if you created a new line of code sending things to Barton.

- ran the command View(barton) to see it 
- $ gets you to one column 

- /r/n/ is return and new line
-gsub - looking for patters, so find this pattern and make it that. Find and replace basically. 

-17780 is the identifying data number for gutenberg's organization system

- meta_fields, pulls in metadata from gutenberg's, the specific ones. 
- every row is an observation 

-token - unit of language. Can be a sound etc. 
- unnest_tokens allows us to separate it out. Could use the same function to separate it out
-Grammar of programming: 
- generally in programming it's less forgiving 
- % > % is about order, order in which to process the commands. it's a pipe
-passes to the next operation 
-basically saying pass to the next operation. 

-stop words list is a list that includes words we don't want in our analysis (probably the, a, to. usually the most common words). Lists are available already that take these words out. Can kind of separate out those most important words. 

-mutate : adds a new column to a data frame, you can define what is in that column

-booktitle "Exploratory data analysis"

- proper names aren't that useful, where an expanded stop words list comes into play

Ngram
-words of a certain length
-bigram would be groups of two 
-"call me Ishmael some years ago never mind" "call me" one bigram. "Ishmael some" one bigram etc.
## Observations

In the next section of each report, you should in **2-3 paragraphs** move from a literal description of what you did in the lab to a more conceptual set of observations. In brief, you want to home in on those aspects of the lab that raised questions or prompted new insights into the textual technology we investigated in the lab activity. What new ideas occurred to you while working? What surprised, delighted, or frustrated you?

## Analysis

The final section of each report should bring your work in the lab into direct, critical conversation with our readings. In **_3-4 paragraphs_**, you should connect your lab observations to ideas from readings assigned _in the given lab unit_. This prose need not be as formal as a research paper, but it should demonstrate careful thought and preparation. You should integrate the readings explicitly, if possible through direct quotation. Use this writing to experiment with intellectual pairings you think might be generative to your larger thinking and help you prepare for the class’ Unessay projects. Think of your lab reports as an evolving research paper, and take them as seriously as one.