# Our Framework

````{card} 
**Before we start:**
^^^
Has anyone worked with GitHub, Markdown, or built a website before?
````

Now that you have learned about the advantages of using OER and especially our approach for teaching, let’s take a look at the framework that will help make your teaching more flexible, open, and engaging. Later, you will learn step by step how to create your own course website. But first, here’s a simple overview of the main tools you will work with:

## The course template

We provide a ready-to-use course template that makes it easy for you to create your own course website. You don’t need to start from scratch! You can simply add your own content and customize the pages to fit your teaching.

The template includes:
- a folder structure to help you stay organized,
- example pages you can edit or replace,
- a table of content file,
- a license for your materials,
- an open science statement,
- a statement on equity, diversity, and inclusion,
- and a code of conduct for your course.

You can copy this template to your GitHub account, add your materials, and adjust the structure. The website for your course will then be created automatically.

## GitHub 
As you may remember, we asked you to create a GitHub account in advance. GitHub is an online platform where you can safely store, organize, and manage your project files. A GitHub project is called a _repository_ (or repo), and it works like a folder on your computer where you can save files.

Here is what the repository for the course template looks like:

![Image of the folder structure of the repository of the course template](../static/folder-structure_minimal-template.png)

In the `lecture` folder, you will save all the files related to your course content. This will be the folder you work with the most.

The `README` contains a short explanation of your website or course. All other files are setup files and can mostly be ignored while working on your content.

## Jupyter Book
GitHub is where your files are stored. Jupyter Book is the tool that turns those files into a nice-looking website. You can control how your website looks and works using two main files:

- `_config.yml`: This file stores the main settings for your website.
- `_toc.yml`: This file defines your table of contents (the structure of your website).

Both files are stored in the `lecture` folder:

![Image of the lecture folder structure of the repository of the course template](../static/lecture-folder-structure.png)

In a moment, we will take a closer look at the possibilities Jupyter Book offers.

## GitHub Pages
GitHub Pages lets you host your website directly from your GitHub repository, making it easy to publish course content, documentation, or personal projects.

In the course template, there is a special file called `book.yml` (inside the folder `.github/workflows`). This file tells GitHub how to build and update your website automatically. Later, you will only need to change a few settings in GitHub to make your site visible to others.

Next, I will present to you some key reasons why we use Jupyter Book within our framework.
