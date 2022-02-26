## Week 8 - Debuggers report

- Link to [my MarkdownParse Repository](https://github.com/CJWAKE998/markdown-parse) <br>
- Link to [other group's MarkdownParse](https://github.com/nakulnandhakumar/markdown-parse) <br>

Test code in my MarkdownParse <br>
![Lab report 4 tests](https://user-images.githubusercontent.com/97641362/155821124-0e3c098c-90e6-4d8d-8c5b-0f3834954c67.png)

Test code in other groups MarkdownParse <br>
![lab report 4 other tests](https://user-images.githubusercontent.com/97641362/155821461-ad14bbcb-f6a5-4870-994e-b20647c98f46.png)


## Snippet 1

Output for Snippet 1 should produce

1. url.com
2. `google.com
3. google.com
4. ucsd.edu

The test did not pass my test file <br>
![lab report 4 snip 1 test](https://user-images.githubusercontent.com/97641362/155821219-15d034e0-d9f8-40cf-9d38-fad80535828c.png)

The test did not pass other test file <br>
![lab report 4 other snip 1](https://user-images.githubusercontent.com/97641362/155821605-d60f525c-8f9f-4d29-a6d5-05bf6485e565.png)

## Snippet 2

Output for Snippet 2 should produce

1. b.com
2. a.com(())
3. example.com

The test did not pass my test file <br>
![lab report 4 snip 2 test](https://user-images.githubusercontent.com/97641362/155821251-41a87ac0-ea48-494b-b7d5-27ae0c6d4a7e.png)

The test did not pass other test file <br>
![lab report 4 other snip 2](https://user-images.githubusercontent.com/97641362/155821651-0b6e830a-ca7e-4245-89c7-744972853433.png)

## Snippet 3

Output for Snippet 3 should produce

1. https://www.twitter.com
2. https://ucsd-cse15l-w22.github.io/
3. github.com
4. https://cse.ucsd.edu/

The test did not pass my test file <br>
![lab report 4 snip 3 test](https://user-images.githubusercontent.com/97641362/155821270-befc519c-9873-4fe6-b60d-cef18a5ee132.png)

The test did not pass other test file <br>
![lab report 4 other snip 3](https://user-images.githubusercontent.com/97641362/155821662-39a5d7ee-07ea-4446-b2d3-69a6574061c4.png)


## Questions
1. Yes I think there is a small change you could make to the code to fix all inline cases. I think all you'd have to
   do is make it so after the program finds the closing bracket, it just then looks for the openParen
   
2. I think this would take quite a bit more code to fix nested parentheses. This is because you'd need a way to detect whether or not a bracket is nested or not.

3. I think this would also take quite a bit more code to fix the issue when the link is on a new line. This is because the program would need to know when to still look for the closing part to a link despite the closing bracket being on a different line.






