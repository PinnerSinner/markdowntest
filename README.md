# Writing Great Markdown
## Using CodeBlocks
GitHub Flavored Markdown, often shortened as GFM, is the dialect of Markdown that is currently supported for user content on GitHub.com and GitHub Enterprise.
Codeblocks in markdown make it *very easy* for tech people to research and develop their code. A good ___cloud engineer_ uses this all the time, so it's an ___essential skill___


'''
With single quotations (which is incorrect) - (')

With backticks (correct) - (`)
```
even_numbers = []
for num in range(2, 11, 2):
    even_numbers.append(num)

print("Even numbers from 2 to 10:", even_numbers)
```
- In order to make codeblocks, use backticks (`) not to be confused with single quotations (')

- To add a picture, it's exclamation mark !, square braces [], braces ()
![Screenshot 2022-10-02 225537](https://github.com/PinnerSinner/markdowntest/assets/108472081/fa8da73a-1603-46de-b636-43ae87564dcd)
- To write in, it's <img width=".....px" src="......>
- So, ```<img width="180px" src="https://github.com/PinnerSinner/markdowntest/assets/108472081/fa8da73a-1603-46de-b636-43ae87564dcd"/>```
- <img width="180px" src="https://github.com/PinnerSinner/markdowntest/assets/108472081/fa8da73a-1603-46de-b636-43ae87564dcd"/>

### Colours
- When using codeblocks, specify the language used for proper formatting and colour. 
- Good Cloud Engineers use codeblocks for both code and errors that appear in the console.
- Here is an example of using a codeblock for an error that appears in bash

```bash
# Attempting to divide by zero, which raises a ZeroDivisionError
result = 10 / 0
ZeroDivisionError: division by zero
```

