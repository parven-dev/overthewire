# Bandit level 9 > 10

## Problem

The password for the next level is stored in the file data.txt in one of the few human-readable strings, preceded by several ‘=’ characters.


## Aproach 
 -- Strings pull out the text from data.txt file
 -- user grep command to get values

## Command used 

strings data.txt | grep '='

