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
* A computer with an internet connection
* Markdown Editor: [Atom](https://atom.io/)
* A [GitHub](https://github.com/) account
* A resume formatted in Markdown
----
## Instructions

- [Prepare your resume in GitHub flavored Markdown](#1-Prepare-your-resume-in-GitHub-flavored-Markdown)
- [Upload your resume to GitHub](#2-Upload-your-resume-to-GitHub)
- [Host your GitHub Pages with a default Jekyll theme](#3-Host-your-GitHub-Pages-with-a-default-Jekyll-theme)
- [Customize the default Jekyll theme](#4-Customize-the-default-Jekyll-theme)
- [More Resources](#More-Resources)

### 1. Prepare your resume in GitHub flavored Markdown
Use the tutorial I provided in [more resources](#more-resources) to format your resume in GitHub flavored Markdown.

* **Etter's principle:** There are many flavours of Markdown. The reason why I choose GitHub flavored Markdown is its popularity. Just like Andrew Etter said in ["Modern Technical Writing"](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS).

Caution! To ensure your GitHub Pages will show your resume properly, your resume has to be saved as **index.md**.

----
### 2. Upload your resume to GitHub

#### **a. Create a new repository**
![create](https://github.com/ZhijieZheng-UM/ZhijieZheng-UM.github.io/blob/main/create.jpeg)

>1. Sign in to [GitHub](https://github.com/).
>
>2. Click `repositories` to go to your repository page. There should be empty if you haven't set up a repository.
>
>3. Click the green book icon on the right-hand side of the page to create a new repository.
>
>4. Name your repository `(your user name).github.io`.
>
>5. Make sure you select `public`. It will allow others to see your repository.
>
>6. Click `Create repository` button.

* **Etter's principle:** A GitHub repository is a kind of distributed version control system (DVCS). DVCS has a lot of advantages. According to [Andrew Etter's book](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS), It allows us for offline work and concurrent work on the same file.
<br />

#### **b. Upload your resume to your new repository**
![upload](https://github.com/ZhijieZheng-UM/ZhijieZheng-UM.github.io/blob/main/upload.gif)

>1. Click the `Add file` button, then select `Upload files`.
>
>2. Click `Choose your files`.
>
>3. Select the file `index.md` in your local location.
>
>4. Click `Commit changes` green button.

Now your resume is uploaded to your new repository.

----

### 3. Host your GitHub Pages with a default Jekyll theme
![gif](https://github.com/ZhijieZheng-UM/ZhijieZheng-UM.github.io/blob/main/gif.gif)

>1. Go to your new created repository.
>
>2. Click `Settings` above the green code button.
>
>3. Click `Pages` on the left-hand sidebar.
>
>4. Select `main` branch under the `source` section.
>
>5. Select `/root` from the drop-down menu next to `main`.
>
>6. Click `save` button.
>
>7. Click `Choose a theme` button.
>
>8. Find a theme you like and select it.
>
>9. Click `Select theme` button.

Your resume is hosted on GitHub Pages now. You can visit it on (your user name).github.io.

Be patient, it takes a few minutes to update your changes on your GitHub Pages. Since Jekyll is a static site generator and GitHub uses Jekyll to format the information in your GitHub Pages, you cannot see your changes in real-time.

* **Etter's principle:** In this step, you follow [Etter's protocol](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) which is you provide a static site generator (Jekyll) with content (Markdown) and a theme, and then it processes all the content into a static website. The reason why I use a static website to host my documentation is because of its speed, simplicity, portability, and security.

### 4. Customize the default Jekyll theme
* **Etter's principle:** Customization in your theme is the chance to differentiate your content from the thousands of disorganized sites. It is important to customize your theme.

In this step, I will only show you how to change the title on your GitHub Pages. For more instructions, you can find it under "[More Resources](#More-Resources)".
>1. Enter the repository that is hosting your resume.
>
>2. Click `_config.yml` file. It is the format file of your theme.
>
>3. Click the `pen` icon to edit your file.
>
>4. Add a new line and type `title: Resume`. You can change "Resume" with any words you like.
>
>5. Click `Commit changes` button to save your changes.


### More Resources
* GitHub flavored Markdown tutorial: https://guides.github.com/features/mastering-markdown/
* "Modern Technical Writing" by Andrew Etter: https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS
* Mike Dane's Jekyll Static Site Generator Tutorial: https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB
* Jekyll template guide: https://jekyllrb.com/

----
## Authors and Acknowledgements
* **Author:**

	This documentation was written by Zhijie Zheng, using Andrew Etter's book "Modern Technical Writing" as a reference.

* **Acknowledgements:**

	The template I based on this readme was made by Danny Guo and can be found [here](https://www.makeareadme.com/).

	Thanks to Haseeb Paracha, Akshay Sharma, Farhan Rahman, Kien Mai for giving me suggestions about this documentation.

----
## FAQs
**Q:** Why is my resume not showing up?

**A:** Make sure your repository is public and the resume is named `index.md`.

<br />

**Q:**  Why is Markdown better than a word processor?

**A:** A word processor like "Microsoft word" is good to create attractive PDFs that can be discarded. It cannot support version control like Markdown. What's more, A word processor like "Microsoft word" costs money, but Markdown is free.
