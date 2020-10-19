#### STORYLINE
During the beginning of the Fourth Great Ninja War, Naruto was hidden in Kumogakure(The Village hidden in the Clouds) with Killer B. To unlock his inner potential, Killer B asked Naruto to look within himself and find his real self.

He gave him a long, pretty long message of N characters. Naruto can only find himself and unlock his real powers if he is somehow able to know how many palindromic substrings are there in this given message.

As another established Jonin ranked Ninja, you are called upon to help him.

 

#### INPUT
The first line contains T - the number of test cases.

For each test case from total T test cases, you are given 2 lines:

The first line contains N, the number of characters in the message

The second line contains the message of N characters that consist of characters only from (a-z) (26 possible characters)

 

#### OUTPUT
For each test case, output a single integer - that denotes the answer to the question as described in the storyline

 

#### CONSTRAINTS


The sum of N over all T test cases does not exceed 

#### SAMPLE INPUT 

4         </br>
6         </br>
abaaba    </br>
13        </br>
abcbabcbabcba   </br>
1         </br>
a         </br>
2         </br>
bb        </br>

#### SAMPLE OUTPUT 
11  </br>
31  </br>
1   </br>
3   </br>

#### Explanation

As seen in the first test, 'abaaba', the total number of palindromic substrings are 11 which are as follows:

a [0,0]   b[1,1]  a[2,2]  a[3,3]  b[4,4]  a[5,5]

aa[2,3]

aba[0,2] aba[3,5]

baab[1,4]

abaaba[0,5]

Similary, the results are valid for other given tests.

Note that a single character is also a palindromic substring.

Time Limit:	1.0 sec(s) for each input file.     </br>
Memory Limit:	256 MB                            </br>
Source Limit:	1024 KB                           </br>
