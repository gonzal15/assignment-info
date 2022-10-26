# Your resume, online!

## Purpose

The purpose of this ReadMe file is to, above all else, help you host your resume online as a static website. By the end of this tutorial, you should be able to:
- use Markdown with your Markdown editor to create your resume
- use Jekyll to generate a static website
- use GitHub and GitHub Pages to maintain and host your resume online

These goals align with the principles taught in Andrew Etter's book, *Modern Technical Writing*. As you read through the instructions, you will see references to his book and his justifications for why we do the things we do in this tutorial.

## Prerequisites

**Before you start**, you should have the following:

- A GitHub Account
- A Markdown editor, this ReadMe was written using [ghostwriter](https://github.com/KDE/ghostwriter)
- Jekyll, a static site generator. You can [view instructions here](https://jekyllrb.com/docs/installation/) for more information on how to install Jekyll according to your operating system

If you're new to using Markdown, check out the **More Resources** section of this ReadMe to get a link to a tutorial on using Markdown.

## Instructions

#### 1) Create your resume in Markdown

The first step is to open your Markdown editor and start creating your resume. If you have a resume already handy in a .docx or .pdf format, you can copy the information from there into your Markdown editor and make adjustments as needed.

Markdown is a lightweight markup language used to create and format simple text documents. While web pages are displayed to you using HTML (another markup language) writing HTML code can be a bit difficult, especially when starting out. The purpose of a lightweight markup language like Markdown is to make it easier for people to write with and to have a more human-readable piece of code that other can look at. 

This feature is pointed out by Andrew Etter in his book, and using a lightweight markup language as a technical writer is one of his principles. He notes that having something written in Markdown also makes it easier for collaboration. For example, when writing a ReadMe file that is to eventually be modified by different people with diverse skillsets, a lightweight markup language makes it easier for those people to make a meaningful contribution.

#### 2) Create a new website with Jekyll

Now that we have a Markdown-formatted resume, we want to get the files ready for when we eventually host it online. We can get a folder created with all of the relevant files we need using Jekyll.

Start by opening your computer's terminal. Then, enter the following command:  
```
jekyll new [name]
```
Where "name" is the name of the folder you want to create. Depending on the directory that you opened your terminal in, there should now be a folder there with the name you gave in the command. This folder contains all of the necessary files to host your website.

You may have noticed that the size of this folder is pretty small, and Andrew Etter notes this as a strength. Compare to dynamic websites, static websites don't require a lot of resources to create nor to host online. This makes them a quick and efficient option for showing text, which is desirable when the point of your website is only to show text!

#### 3) Create a repository for your website in GitHub

In order to host your website through GitHub Pages, you will need to create a repository for it. The name of your repository should be in the following format:
```
githubUsername.github.io
```

GitHub provides a distributed version control system (DVCS), which helps keep track of what changes were made and by who. This accommodates the collaboration aspect mentioned earlier that Andrew Etter gave, but he also notes that a DVCS is preferred by software developers. As well, using a DVCS to store things such as a ReadMe ensures that the file can stay updated along with the code. By keeping things up-to-date, mistakes and errors can be avoided from both the writer side and the developer side.

#### 4) Update your folder with your resume

Specifically, we're going to update the file titled:
```
index.md
```

In this file, below the content at the top (called the "front matter") separated with its own dashes, you can copy and paste the contents of your Markdown-formatted resume into this space. Save and close the file.