# Making lab report

## Steps

1. Create login on github.com
1. Verify email
1. Login to github.com
1. Visit [https://github.com/CoE-GNE/LabReportPP](https://github.com/CoE-GNE/LabReportPP)
1. Near top, in line of `CoE-GNE/LabReportPP`, on extreme right, look for three buttons, named `Watch`, `Star` and `Fork`.
1. Click on `Fork`.
1. If you need help on form, visit: [Help on forking](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo)
1. In following, replace `YourGitHubUserID` with your github userID.
1. In directory `public_html` of your account on `Code Server`, issue command: `git clone https://github.com/YourGitHubUserID/LabReportPP.git`
1. Go to directory LabReportPP, by using command `cd LabReportPP`.
1. Using `xmake` create a new project, say `Ex01`.
1. Go to the newly created folder, by following command. Replace `Ex01`, if
you used some different project name.
1. `cd Ex01`
1. Edit `src/main.c`.
1. Create more .c or .h files as per the requirements of the project.
1. Compile with `xmake`.
1. Remove errors / warnings, if you get any.
1. Execute code by `xmake run`.
1. Test you code. When all is Ok, then to generate lab report for this practical, issue command: `labrep`.
1. It will produce `report.md` and `report.html` file in current folder.
1. Edit `report.md` file, to add more content, or to change anything.
1. To update `report.html` from this amended `report.md` file, issue command: `md2html report`
1. Go to parent folder by `cd ..`
1. Edit `lab.md` file.
1. Issue command: `md2html lab`

## To know about how to make good webpages, it is recommended to go through the following.

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/CoE-GNE/LabReportPP/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/CoE-GNE/LabReportPP/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
