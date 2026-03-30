# Bandit level 8 -> 9

## problem

The password for the next level is stored in the file data.txt and is the only line of text that occurs only once


## Aproach 
 - Sort the file
 - use uniq command to find unique line

## Command Used

sort data.txt | uniq -u


