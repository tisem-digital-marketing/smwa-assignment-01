# Group Assignment 1

[![Template Lifecycle](https://img.shields.io/badge/lifecycle-maturing-blue.svg)](https://www.tidyverse.org/lifecycle/#maturing)
[![Template Version](https://img.shields.io/badge/version-2021-green.svg)]()

**The group assignment is grade relevant.**
Check the [course syllabus](https://tisem-digital-marketing.github.io/2021-smwa/assets/syllabus.pdf) for more details.

## Meta-Information 

* Group Name: GROUP_NAME
* Group Members: LIST GROUP MEMBERS
* GitHub Handles: LIST GITHUB USERNAMES OF ALL GROUP MEMBERS
* Group Leader: YOUR_NAME (YOUR_GH_USERNAME), i.e. "Lachlan Deer (@lachlandeer)"

## Instructions for Students

1. The "Group Leader" needs to accept the assignment invitation on GitHub. The link to do this is on the course website.
2. The "Group Leader" adds their group members to the repository on GitHub.
  * Click Settings, then go to the Manage Access tab.
  * Click "Invite Teams or people"
  * 
3. Clone the repository to your machine.
4. Update the meta-information above.
5. Install the `wordcountaddin` package by entering the following into your RStudio console:
```{r}
devtools::install_github("benmarwick/wordcountaddin", type = "source", dependencies = TRUE)
```
This package will count the number of word in your proposal, and we use this number to verify you meet the assignment length constraints
5. Complete the your project proposal using `proposal.Rmd`
  * Use the template "as-is", do not modify headings, fonts, font-sizes etc.
  * The word limit is **500 words**. This is an upper bound, you can do it in less and are encouraged to.
6. Complete the `data/download_data.R` script to download the data that your final project will use.

## Grading Information

* Due Date: **May 14, 2021 at 23:59 pm**

Submission is via GitHub Classroom.
Your most recent commit that is on the `main` branch before the due date will be graded.

**You must include a html file "assignment_answers.html" in the repository by the submission deadline**

## Template Meta-Information

*   Template Maintainer: Lachlan Deer (`@lachlandeer`)
*   Course: [Social Media and Web Analytics](https://github.com/tisem-social-media)
*   Institute: [Dept of Marketing, TiSEM](https://www.tilburguniversity.edu/about/schools/economics-and-management/organization/departments/marketing)
*   Template Link: [click here](https://github.com/tisem-digital-marketing/project-milestone-01)
*   Current Version: [Spring 2021](https://tisem-digital-marketing.github.io/2021-smwa/)

### Suggested Citation

```
Lachlan Deer, 2021, Group Assignment 1 Template, Social Media and Web Analytics, TiSEM
```

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />

This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.