There is a string S of the length .

You have to count the sum_{i=0}^{N-1} t<sub>i</sub> (i.e., summation of 
t<sub>i</sub> from i=0 to i= N-1), where t<sub>i</sub> is the number of substrings 
which contain character S<sub>i</sub> when S<sub>i</sub> is a vowel, otherwise t<sub>i</sub> is 0.

#### INPUT

The first line contains one integer TC - total number of test-cases.

For each test-case, the first line contains N - length of string and the second line
contains a string S. The characters may be in upper case or in lower case.

#### OUTPUT
For each test case, you have to print the answer in a new line.

#### CONSTRAINTS
1 <= TC <= 10^2 </br>
1 <= N <= 10^5    </br>

#### SAMPLE INPUT 
1 </br>
6 </br>
coding </br>

#### SAMPLE OUTPUT 
22 </br>

#### Explanation
In this string "coding", character 'o' is present in 10 substrings and character 'i' is present in 12 substrings.

Time Limit:	1.0 sec(s) for each input file. </br>
Memory Limit:	256 MB </br>
Source Limit:	1024 KB </br>
