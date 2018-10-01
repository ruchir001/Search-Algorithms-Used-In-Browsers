# Search-Algorithms-Used-In-Browser

THIS PROJECT DEPICTS THE ALGORITHMS USED BY BROWSERS AND MS WORD TO FIND A WORD IN A LARGE TEXT INPUT DATA. 
THE INPUT DATA USED IS A NOVEL NAMED “THE KITE RUNNER” BY KHALED HOSSEINI. THERE ARE MANY TYPE OF ALGORITHMS AND DATA STRUCTURE USED FOR THIS PURPOSE ONLY. THIS PROJECT IMPLEMENTS INVERTED INDEX DATA STRUCTURE, BOYER MOORE SEARCH ALGORITHM AND RABIN-KARP SEARCH ALGORITHM.
<pre>
<b>BOYER MOORE ALGORITHM</b>
Boyer-Moore is an algorithm that improves the performance of pattern searching into a text by considering some observations. First of all this algorithm starts comparing the pattern from the leftmost part of text and moves it to the right.
Unlike other string searching algorithms though, Boyer-Moore compares the pattern against a possible match from right to left as shown below.
The main idea of Boyer-Moore in order to improve the performance are some observations of the pattern. In the terminology of this algorithm they are called good-suffix and bad-character shifts.

TIME COMPLEXITY-
     Complexity is O(n). The execution time can actually be sub-linear: it doesn't need to actually check every character of the string          to be searched but rather skips over some of them (check right-most character of the block of m first, if not found in pattern can        skip entire rest of block).
     Best-case performance is O(n/m). In the best case, only one in m characters needs to be checked.
     Worst case complexity is O(m+n)
    

<b>RABIN-KARP ALGORITHM</b>
</pre>
