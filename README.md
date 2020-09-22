# Natural Language Processing
In this particular project, we are going to work on the inaugural corpora from the nltk in Python. We will be looking at the following speeches of the Presidents of the United States of America

President Franklin D. Roosevelt in 1941
President John F. Kennedy in 1961
President Richard Nixon in 1973

1. Find the number of characters, words and sentences for the mentioned documents.
2. Remove all the stopwords from all the three speeches.
3. Which word occurs the most number of times in his inaugural address for each president? Mention the top three words. (after removing the stopwords)
4. Plot the word cloud of each of the speeches of the variable. (after removing the stopwords)
5. Code Snippet to extract the three speeches:

"
import nltk
nltk.download('inaugural')
from nltk.corpus import inaugural
inaugural.fileids()
inaugural.raw('1941-Roosevelt.txt')
inaugural.raw('1961-Kennedy.txt')
inaugural.raw('1973-Nixon.txt')
"
