# Do_the_thing 

1.Curls a site and provides credentials.The results of that operation are piped out for review.
2.Use the framework from the curl script to automate data collection 

Helps with reconnaissance and collection of bulk information. 


#New functionality I'd like to add 

Collect cookies from site.

Will use something like this:  

"curl --cookie-jar cnncookies.txt https://www.cnn.com/index.html -O"  

#use exit codes to trigger other actions 

6 - Coulnd't resolve a host 
7 - Failed to connect 

Reference for later: https://shapeshed.com/unix-exit-codes/ 

#pipe non 200s to a different document 
