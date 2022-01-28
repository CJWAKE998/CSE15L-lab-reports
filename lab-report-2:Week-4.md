# Lab Report 2

## First change made to code
Link to commit: [https://github.com/CJWAKE998/markdown-parse/commit/6843713c1973ce980f87b705b2c6407a968c9fcc](url)
![CODE CHANGE 1](https://user-images.githubusercontent.com/97641362/151629212-6b3ae171-1699-45b4-ae77-18ff9bc9994d.png)

This was the first file I made that was giving me errors, as you can see I was getting a heap space error <br>
Link to first test file: [https://github.com/CJWAKE998/markdown-parse/commit/560166b54512a30efeeba5eafe2d2d1ab4046e3c#diff-c1ee2d48f5f64b4463a98907818b5846f49cc9dd67f88882a8b551106ec320fb](url) <br>

This was the output originally: <br>
![error file 1](https://user-images.githubusercontent.com/97641362/151629780-ebaa1fa6-fb79-44d5-a7ad-d6e97deda09a.png)
We can see that the bug caused by the failure-inducing input was due to the bracket being missing for one of the links. This resulted in the program to continously search for another link but could not find the final closing bracket, which caused the heap space error.

Link to second and third test files: [https://github.com/CJWAKE998/markdown-parse/commit/43fcaeb7b8071284e0adf3bf247a7564b784fa7f#diff-72d0164ca2d60c8d0fdc3b1a93d3e1a746eb8532639f111eda62faf046aa6f92](url) <br>

As we can see, the changes I made to MarkdownParse ended up fixing all the test files. This is because it reaches the if statement each time, and if anything is out of bounds it just jumps out of the loop, preventing an error. I hope this is sufficient, if I need to make any changes I will after recieving feedback.


