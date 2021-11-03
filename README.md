# Host your resume on GitHub Pages

<img src="https://github.com/ZhijieZheng-UM/ZhijieZheng-UM.github.io/blob/main/image.png" alt="page"
	title="page" width="500" height="250" />

![resume](https://github.com/ZhijieZheng-UM/ZhijieZheng-UM.github.io/blob/main/resume.gif)

## Purpose
Hosting a resume on your GitHub Pages is a great way to introduce yourself to others. In addition, using a resume link to share your resume is a more efficient way rather than sharing the PDF file. In this instruction, I will show you the steps to host a resume on GitHub pages.

----
## Overview
- [Prerequisites](#Prerequisites)
- [Instructions](#Instructions)
- [Authors and Acknowledgements](#Authors-and-Acknowledgements)
- [FAQs](#FAQs)
-----
## Prerequisites
* A computer with internet connection
* Markdown Editor: [Atom](https://atom.io/)
* A [GitHub](https://github.com/) account
* A resume formatted in Markdown
----
## Instructions

- [Prepare your resume in GitHub flavored Markdown](#Prepare-your-resume-in-GitHub-flavored-Markdown)
- [Upload your resume to GitHub](#Upload-your-resume-to-GitHub)
- [Select a default Jekyll theme for your GitHub Pages](#Select-a-default-Jekyll-theme-for-your-GitHub-Pages)
- [More Resources](#More-Resources)

### Prepare your resume in GitHub flavored Markdown
Use the tutorial I provided in [more resources](#more-resources) to format your resume in GitHub flavored Markdown. There are many flavours of Markdown. The reason why I choose GitHub flavored Markdown is popularity. Just like Andrew Etter said in ["Modern Technical Writing"](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS).

Caution! To ensure your GitHub Pages will show your resume properly, your resume has to be saved as **index.md**.

----
### 1. Upload your resume to GitHub

#### **a. Create a new repository**
![create](https://github.com/ZhijieZheng-UM/ZhijieZheng-UM.github.io/blob/main/create.jpeg)

>1. Sign in to [GitHub](https://github.com/).
>
>2. Click "repositories" to go to your repository page. There should be empty if you haven't set up a repository.
>
>3. Click the green book icon on the right-hand side of the page to create a new repository.
>
>4. Name your repository (your user name).github.io.
>
>5. Make sure you select public. It will allow others to see your repository.
>
>6. Click "Create repository" button

A GitHub repository is a kind of distributed version control system (DVCS). DVCS has a lot of advantages. According to [Andrew Etter's book](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS), It allows us for offline work and concurrent work on the same file.


#### **b. Upload your resume to your new repository**
![upload](https://github.com/ZhijieZheng-UM/ZhijieZheng-UM.github.io/blob/main/upload.gif)

>1. Click the "Add file" button, then select "Upload files".
>
>2. Click "Choose your files".
>
>3. Select the file "index.md" in your local location.
>
>4. Click "Commit changes" green button

Now your resume is upload to your new repository.

----
### 2. Select a default Jekyll theme for your GitHub Pages
![gif](https://github.com/ZhijieZheng-UM/ZhijieZheng-UM.github.io/blob/main/gif.gif)

>1. Go to your new created repository.
>
>2. Click "Settings" above the green code button
>
>3. Click "Pages" on the left-hand side bar
>
>4. Select main branch on the source
>
>5. Click "Choose a theme" button
>
>6. Find a theme you like and select it.
>
>7. Click "Select theme" button

Your resume is hosted on GitHub Pages now. You can visit it on (your user name).github.io.

Be patient, it takes few minutes to update your changes on your GitHub Pages. Since Jekyll is a static site generator and GitHub uses Jekyll to format the information in your GitHub Pages, you cannot see your changes in real-time.

### More Resources
* GitHub flavored Markdown tutorial: https://guides.github.com/features/mastering-markdown/
* "Modern Technical Writing" by Andrew Etter: https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS
* Mike Dane's Jekyll Static Site Generator Tutorial: https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB

----
## Authors and Acknowledgements

Thanks to **Haseeb Paracha, Akshay Sharma, Farhan Rahman, Kien Mai** for giving me suggestions about this readme.

----
## FAQs
**Q:** Why is my resume not showing up?

**A:** Make sure your repository is public and the resume is named index.md.

**Q:** Where can I find my GitHub Pages's address?

**A:** Click the gear icon on the right side of green code button in your repository. It will show up your GitHub Pages's website address.
