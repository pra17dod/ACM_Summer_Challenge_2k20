You are given a string A consisting of lower case english letters, single backslash(”/”) and double backslash(“//”) which starts with backslash sequence and ends with a backslash sequence.

You want to collect substring of A of english letters between two single backslash and ignore any substring starting or ending with a double backslash.

A substring is a contiguous sequence of characters within a string. For example the list of all substrings of the string "apple" would be "apple", "appl", "pple", "app", "ppl", "ple", "ap", "pp", "pl", "le", "a", "p", "l", "e", "".

You have to answer for  queries.

#### INPUT

First line of input contains Q (number of queries).

The only line of each query will contain string A.

#### OUTPUT

For each query print the number of substrings you collected in the first line.

Next print all the collected substrings each in new line.

#### CONSTRAINTS

1 <= Q <= 10^3  </br>
1 <= |A| <= 10^3  </br>

#### SAMPLE INPUT 
3               </br>
/abc/bcd/       </br>
/abc/bcd//aod/  </br>
//abc/bcd/aod// </br>
#### SAMPLE OUTPUT     
2       </br>
abc     </br>
bcd     </br>
1       </br>
abc     </br>
1       </br>
bcd     </br>
#### Explanation
In first test case both the substrings are valid as none of them starts or ends with double backslash.

In second testcase only "abc" is a valid substring as substrings "bcd" and "aod" ends and starts with a double backslash respectively.

In third testcase only "bcd" is a valid substring as substrings "abc" and "aod" starts and ends with a double backslash respectively.

Time Limit:	1.0 sec(s) for each input file. </br>
Memory Limit:	256 MB </br>
Source Limit:	1024 KB  </br>
