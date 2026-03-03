1. Not many of the problems gave me too much trouble
We also have done some of them already in class, but I did try
to go through the process of creating the 

I did put one extra, which was a combination of conditions 10 and 13. Maybe should've done an "AND" one since NFAs do really well 
with handling "OR" conditions
...wonder if we'll get "COND1 AND COND2 OR COND3" type question in the future for a NFA? Maybe looking a bit too ahead

2. The only one that had me was the combination of conditions 10 and 13, but that was mostly since I was using the wrong annotation for multiple cases
Should we use JFLAP more I should keep in mind not to use 
commas since that will be treated as a "0,1" input

3. I was wondering about a NFA that would recognize the language of strings that had an equal amount of 0's and 1's, but it didn't seem to be reasonable
with an NFA and what we know so far

I'd assume this was because we need a unique state for each possible real number that the number of 0's and 1's in the string has read so far, unlike
the questions involving checking for a multiple of an integer "n", that isn't 1

Thinking about it, this problem could work as long as its bounded by "nk", in which n is an integer that is greater than 1, so
that we can use modulo to treat the 0's and 1's as a state the infinite shares

So in that case, we can just say "oh, this string isn't recognized since there isn't a multiple of 0's or 1's for it to match
But I do wonder how an automa can handle it? Since wouldn't there be an infinite amount of states?
Would that make it an _infinite_ automa? If that's so, I guess it can't be an NFA then

Small note, "1013" is just an extra I did as 10 OR 13 NFA
