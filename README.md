## pinky
### The (reverse) PHP mini RAT

A reverse shell works by the remote computer sending its shell to a specific user, rather than binding it to a port, which would be unreachable in many circumstances. This allows run commands over the remote server.

**pinky** is a minimal php implementantion of a reverse remote administration tool.

### Why?

Truth is there are a lot of implementations out there in other programming languages, but not a good one written in PHP. Most of the code makes use of the **shell_exec** function to execute commands and this is very limited. **pynky** use **proc_open** to pass  input and catch the output to send it through a socket connection.

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/davidtavarez/pinky/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
