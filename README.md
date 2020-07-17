# auto_curl
Curls a site and provides credentials. The results of that operation are piped out for review.  

Helps with reconnaissance and collection of bulk information. 

# New functionality I'd like to add 

## Create a new directory if needed. Disregard if not 

if the user feeds the script a directory name create a new directory to store all outputs

else 

run in the current directory. 

## Collect cookies from site.

Will use something like this:  

"curl --cookie-jar cnncookies.txt https://www.cnn.com/index.html -O" 

## use exit codes to trigger other actions 

6 - Coulnd't resolve a host 
7 - Failed to connect 

Reference for later: https://shapeshed.com/unix-exit-codes/ 

$? to collect the exit code 

&&  if success 

|| if failure 


Also pipe non 200s to a different output 

## create modular elements so I can reuse them 

https://en.wikibooks.org/wiki/Bourne_Shell_Scripting/Modularization 
