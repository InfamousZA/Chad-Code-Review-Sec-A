# Chad-Code-Review-Sec-A
The purpose of this code is to group an array of strings that are anagrams.
A student submitted this code and after compiling their code, it did not run.
Upon inspection, I noticed a few errors, including syntax and omitting of arguments in functions.
In line 3, there is an indent error. The code in line 2 defines a function, and so the code meant for the function needs to be indented until the end of the function where the indent ends, thus line 2 needs to be indented.
In line 8, a function is used (sorted()), but no argument has been inserted, generatring an error when compiling.
As for presentation of the code, it could be more compact into appropriate segments. For example, theres an empty line after every line of code. These lines could be removed in the for loop, making that loop easier to see. The same can be done for the rest of the groupAnagram function.
