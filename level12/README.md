# Bandit level 11 -> 12 

## The password for the next level is stored in the file data.txt, where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions 

## Approach 
   -- user tr command to break A-Za-z  to N-ZA-Mn-za-m

## Command
  -- cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'

