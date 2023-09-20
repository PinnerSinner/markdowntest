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

## Errors
- When using codeblocks, specify the language used for proper formatting and colour. 
- Good Cloud Engineers use codeblocks for both code and errors that appear in the console.
- Here is an example of using a codeblock for an error that appears in bash

```bash
# Attempting to divide by zero, which raises a ZeroDivisionError
result = 10 / 0
```
> ZeroDivisionError: division by zero

## External Links
If you're referencing something, we need to source it 
- [GitHub Flavoured Markdown Spec](https://github.github.com/gfm/#introduction) [<sup>[1]</sup>](#external-links)
- [Getting started(Github Flavoured Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) [<sup>[2]</sup>](#external-links)
- [Using TaskLists(GitHub Docs)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) [<sup>[3]</sup>](#external-links)
- [Using emojis (cheat cheet)](https://github.com/ikatyang/emoji-cheat-sheet#emoji-cheat-sheet) [<sup>[4]</sup>](#external-links)
- [Using Tables](https://github.github.com/gfm/#table) [<sup>[5]</sup>](#external-links)

## Using Github Flavoured Tasklists
Github extends Markdown to have a list where you can check off items. [<sup>[3]</sup>](#references)
- [x] Finish step 1
- [ ] Finish step 2
- [ ] Finish step 3

## Using GFM emojis <sup>[4]</sup>(#references)

- GitHub Flavoured Markdown supports emoji shortcodes
- Here are some examples using a table

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:clouds:` | :cloud: |
| Lightning Cloud | `:clouds_with_lightning:` | 🌩️ |

## How to create a table <sup>[5]</sup>
- Github extends the functionality of mardkwotn tables to provide more alignment and table cell formatting options 
```markdown
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:clouds:` | :cloud: |
| Lightning Cloud | `:clouds_with_lightning:` | 🌩️ |
```
[Secret Window Hidden Garden](secret-window.md)
