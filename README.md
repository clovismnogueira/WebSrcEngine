# WebSrcEngine
This application is built using JAVA (JSoup + JSon) , JS, BootStrap and JQuery.
The Application consists of below functionalities:
1. Web Crawler - which is gathering the string tokens from a URL recursively.
   Currently we have limit the scope of URL crawling to be 10,000 . But can easily be changed.
2. Inverted Index - We have used the inverted Index to store the Data Dictonary from Web Crawler Output.
   This is implemented using Trie(for Data Dictonary) and HashMap(Occurences of Strings in an URL).
3. Ranking of Webpages : QuickSelect Algorithm is used to rank the top 5 web pages for the searched String.
4. Autocompletion of words using Trie.
5. Correct Word recommendation using EDIT Distance Algorithm. 
   Currently we are recommending the words from Data Dictonary which are 1 edit distance away from the
   User's Searched word.
