## Lab Report 5

After my group fixed parts of our bash script in which fixed some of the commonmark errors, I used `vimdiff lab9/markdown-parse/results.txt  markdown-parse/results.txt` to compare my results to the results from the given implementation, and found differences on files 194.md and 201.md. I found these by running the bash script and writing down the name of the file every time the debugger got stuck in an infinite loop. We then altered the code to be able to run all the commonmark files without the a infinite loop occuring. Then when we ran the diff for our implementation compared to the given implementation, we found that the given implementation was giving errors at these two files. My thought is the given implementation is also not accounting for an infinite loop scenario, that's why the resaults we were getting were different, because we were accounting for infinite loops.

When running `vimdiff lab9/markdown-parse/results.txt  markdown-parse/results.txt`
![Lab report 5 vimdiff screenshot](https://user-images.githubusercontent.com/97641362/158958476-31904625-a73b-4411-96bb-41614c7761ab.png)
- As you can see, this screenshot contains both files and you can see that I was expecting the output of `[]` for both, but since they were causing an
infinite loop I changed the file name which removed the output so that way the infinite loop won't trigger again. Changing the name essentially caused the program to skip over this file, based on the configuration of the program.

