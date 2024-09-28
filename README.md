# DSA_Repo
DSA questions with description repository

# 424 . longest-repeating-character-replacementdescription

Step 1: take four variable 
l =0 // left pointer
r = 0 // for right pointer
maxLen = 0 // longest character in the string
maxFrequency // to check which letter contain the max frequency

Step 2. create a HashMap which is  responsible to hold the character and the frequency of the character in the HashMap. 

so first we check that any character is present in the map if not then create a new key=>value pair otherwise get the frequecy present in the list and update it by 1.

then calculate maxFrequency 
maxFrequency = Math.max(maxFrequency, hash.get(character value);
now check if,

(r - l + 1) - maxFrequency

if it is greater then k then take the first element frequency and reduce it by 1. and increment l++;
if not then check 
(r - l + 1) - maxFrequency <= k then 
update the maxLength Value = Math.max(maxLength, r - l + 1);
at the end of the every while loop iteration increment r by 1.

after the while loop end return its value

and return its value.
