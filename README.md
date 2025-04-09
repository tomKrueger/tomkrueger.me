I publish Mobirise project to the /docs folder. This keeps the source separate from what gets published. GithHub pages only allows publishing /root or /doc so I choose /doc (which now is effectively the /dist folder). When publishing, it publishes a project.mobirise file also. Disregard the one in the /docs.

# Manually format all published files

When Mobirise publishes html files to doc they are not formatted the same as what is in GitHub. You need to format each file using Prettier.

Make sure you have Prettier exetension installed.
Save each file in VS Code that has git changes before committing so we can clearly see the differences.

# Format the published html using prettier settings for consistency

`npm run format-html`

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/tomKrueger/Getoutthehouse/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/tomKrueger/Getoutthehouse/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
