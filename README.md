# JupyterCon 2020 Tutorial
A draft of the JupyterBook / The Turing Way tutorial for the JupyterCon 2020

- Website: https://jupytercon.com/
- Location: Online
- Date: 5-9 October 2020

## Authors

*Malvika Sharan, Martina G. Vilas, Sarah Gibson*

## Resources

- will be added

## Title: Creating a Jupyter Book with The Turing Way

- Audience level: Novice
- Prerequisite: previous experience with version control, GitHub
- Target Audience: Anyone with prior knowledge of using GitHub for project 
repositories. Basic experience working with Markdown files and Jupyter notebook 
will be a plus. 

**Summary:**
- Jupyter Book is an open source project for building publication-ready books with 
computational files. The Turing Way is a community-led book project on learning 
computational skills, which is hosted online as a Jupyter Book. In this tutorial, 
you will learn about the collaborative nature of both the projects and create your 
own book using files and chapters from The Turing Way as examples.

## Outline:

This tutorial is organized as follows:

### First part: _Introduction to Jupyter-Book_
We will first introduce you to the basics of Jupyter-Books, and how to build 
them. To complete this section of the tutorial, head over to the [notebooks]
folder.

### Second part: _Online deployment of Jupyter-Book_
In the second part of the tutorial we will show you how create your own GitHub
repository with the contents of your book, locally build it on your computer, 
and host it online using GitHub Pages.

### Third part: _Integrating Jupyter-Book and GitHub Actions_
In the final part of the tutorial we will demonstrate how to build and deploy 
online your Jupyter-Book using GitHub actions.

The session will end with sharing details on how participants can gain further 
support when working with Jupyter Books and The Turing Way

**Proposed Agenda:**

- **[Module 1](./notebooks/1-welcome.ipynb)**, Duration: 5 minutes 
  - Introduction to the workshop
- **[Module 2](./notebooks/2-introduction.ipynb)**, Duration: 20 minutes
  - Introduction to The Turing Way and reproducible research
  - Introduction to Jupyter Book projects
  - Demo of The Turing Way repository and its Jupyter Book
  <!---Show important bits: website folder, _toc file, config file--->
- **[Module 3](./notebooks/3-setup-jupyterbook.ipynb)**, Duration: 15 minutes 
  - Hands-on session on creating the minimal version of a Jupyter Book
  <!---Set up the repository, add a chapter, create a table of content, build the book--->
- **[Module 4](./notebooks/4-config-jupyterbook.ipynb)**, Duration: 15 minutes
  - Jupyter Book configuration, layout and personalisation
   <!---config file--->
- **[Module 5](./notebooks/5-more-jupyterbook.ipynb)**, Duration: 10 minutes
  - Executable files in a Jupyter Book using Jupyter Notebooks
  - Binder-isation of Jupyter Book
- **[Module 6](](./notebooks/6-ci-jupyterbook.ipynb))**, Duration: 15 minutes
  - Continuous Integration (CI) and its role in reproducibility
  - Deploying Jupyter Book using CI tests of GitHub actions
- **[Module 7](./notebooks/7-final-demo.ipynb)**, Duration: 15 minutes
  - Guided demo of Sphinx features in Jupyter Book
  - Wrap up
  <!---for cross-referencing, citation, pdf export, collaborative workflow on GitHub repository to edit a chapter or propose edits on Jupyter Book--->
  
