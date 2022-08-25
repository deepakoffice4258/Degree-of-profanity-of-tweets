<h1>Profanity analysis of Twitter tweets using Python</h1>

<h2>A. Short Description</h2>
<p>
Given a file of tweets and a list of abuses/racial slurs, identify the degree of profanity of Twitter tweets.
</p>

<h2>B. Long Description</h2>
<p>
Suppose two files are provided such that one file contains Twitter tweets by various users and the other consists of a list of "profanity words" (abuses and/or racial slurs). 
</p>
<p>
The file containg tweets will be called as the "tweet file". It can have any one of the extensions - "txt/text/xls/xlsx/xlsm" and a following format: A single column containing
the tweets preceeded by the users' Twitter handle. Can be with/without a header.
For example,
  <ul>
    <li>"@User1 tweet"</li>
    <li>"@user2 tweet"</li>
    <li>"@user3 tweet"</li>
  </ul>
</p>
<p>
The other file, called "search_words" file, contains a list of abusive words and/or racial slurs such that each "profinity word" is on a new line. This file must be a text file with extensions "txt/text".  
</p>
<p>
Given these two files fulfilling the aforementioned requiremnets, the Python program identifies the degree of profanity per tweet. The degree of profanity is defined as the <strong>ratio of the number of abusive/racial words in a tweet to the total number of words in the times time 100</strong>.
</p>

<h2>C. Inputs Description</h2>
<p>
  <ol>
    <li>A file containing Twitter handles and their tweets such that each line contains one Twitter handle and tweets. Check any of the example files called "tweets" with extensions "txt/text/csv/xls/xlsx" for the correct format.</li><br />
    <li>A "txt/text" file with one "profanity word" per line. Check the file called "search_words.txt" or "search_words.text" for the correct format.</li>
   </ol>
</p>

<h2>D. Output Description</h2> 
<p>
A CSV file with 4 columns: User handles, original tweets, "profinity words", and degree of profanity - Check "tweets_analysis.csv".
</p>

<h2>E. Program Requirements</h2> 
<p>
The following libraries need to be installed for this program to work:
<ol>
  <li>pandas</li> 
  <li>openpyxl</li>
</ol>
</p>
  
<h2>F. TO DO</h2>
<p>
<ol>
  <li>Generalize the present code:</li>
  <ul>
    <li>Remove restrictions on structures (formats) of input files.</li>
    <li>Use on real Twitter data.</li><br />
  </ul>
  <li>Write a new program:</li>
  <ul>
    <li>Without 3rd party libraries.</li>
    <li>Test on real Twitter data.</li>
  </ul>
</ol>
</p>
