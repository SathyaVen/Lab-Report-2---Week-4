## Code Change #1
![Image](https://www.linkpicture.com/q/Screen-Shot-2022-04-23-at-3.36.13-PM.png)
* [Link to test file](https://github.com/SathyaVen/markdown-parser/blob/main/test.md)
* The Symptom: ![Image](https://www.linkpicture.com/q/Screen-Shot-2022-04-23-at-3.36.46-PM.png)
* There is an index out of bounds error because initally the program assumes there is a link present in the file. This cause an error when trying to add to the toReturn Array list as it cannot add a substring of the file. 

## Code Change #2
![Image](https://www.linkpicture.com/q/Screen-Shot-2022-04-23-at-4.26.55-PM.png)
* [Link to test file](https://github.com/SathyaVen/markdown-parser/blob/main/test2.md)
* The Symptom: ![Image](https://www.linkpicture.com/q/Screen-Shot-2022-04-23-at-4.22.59-PM.png)
* The program runs succesfully, However, it erronously adds the word "hi" to the list as it is in the format of how a list would be in the markdown launguage. The program assumes that a link will always be followed after the parenthesis.

## Code Change #3
![Image](https://www.linkpicture.com/q/Screen-Shot-2022-04-23-at-4.44.39-PM.png)
* [Link to test file](https://github.com/SathyaVen/markdown-parser/blob/main/test3.md)
* The Symptom: ![Image](https://www.linkpicture.com/q/Screen-Shot-2022-04-23-at-4.40.51-PM.png)
* There is a infinite loop when there is an empty line at the end of the test file. This is beacuse initally the program will be stuck in the while loop even if the index was not found.


