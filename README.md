# offline_Viterbi
co-author : YING AN HONG

## Explanation
We use three different ways to implement offline Viterbi, aiming for score following. Meanwhile, we use Pygame to demonstrate how our code works in different cases.

**1. Original Viterbi**
reference : https://web.mit.edu/music21/doc/index.html

**2. Improve the original Viterbi by taking into account the sudden change in slope that occurs when an error occurs in our scoring process.**

**3. Instead of doing backtracking in Viterbi, we use forward tracking to fix the error for "playing from the head error" in our testing data.**

The red arrow in following videos shows how our different algorithm track the score : 
* How tracking will do under normal circumstances (with no error in the playing) : https://youtu.be/KHZuHf9Cq74
* With the playing error back to start, how our version 1 algorithm works : https://youtu.be/mPNwGmaRhPg
* With the playing error back to start, how our version 2 algorithm works : https://youtu.be/23cD8_Jdr7c
* With the playing error back to start, how our version 3 algorithm works : https://youtu.be/7hDLmIMIS3w
* With random playing error imitates what may happen in real performance, how our version 3 algorithm works : https://youtu.be/mhTiX4ViKbk

