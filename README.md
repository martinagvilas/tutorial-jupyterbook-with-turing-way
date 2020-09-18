# JupyterCon 2020

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
- Target Audience: Anyone with prior knowledge of using GitHub for project repositories. Basic experience working with Markdown files and Jupyter notebook will be a plus. 

**Summary:**
- Jupyter Book is an open source project for building publication-ready books with computational files. The Turing Way is a community-led book project on learning computational skills, which is hosted online as a Jupyter Book. In this tutorial, you will learn about the collaborative nature of both the projects and create your own book using files and chapters from The Turing Way as examples.

**Outline:**
List of topics and activities:
- The workshop will start by introducing the importance of reproducibility in research.
- The session leads will then present The Turing Way as a community-developed book project that teaches best practices in data science for research reproducibility, project design, communication, collaboration and ethics.
- The project's workflow of creating Jupyter Book will be introduced as an example of the reproducible way for hosting online books
- A demo of The Turing Way's GitHub repository will explain how a Jupyter book is created and how they are hosted online
- A longer hands-on session will be carried out to create Jupyter Book on GitHub, using The Turing Way chapters and files if your interest as examples
- We will further show how to deploy JupyterBook with continuous integration tests using github actions
- We will show the collaborative workflow to collaborate on GitHub and propose edits on Jupyter Book
- The session will end with sharing details on how participants can gain further support when working with Jupyter Books and The Turing Way

**Proposed Agenda:**

- **[Module 1](./notebooks/1-welcome.ipynb)**, Duration: 5 minutes 
  - Introduction to the workshop
- **[Module 2](./notebooks/2-introduction.ipynb)**, Duration: 20 minutes
  - Introduction to The Turing Way and reproducible research
  - Introduction to Jupyter Book projects
  - Demo of The Turing Way repository and its JupyterBook
  <!---Show important bits: website folder, _toc file, config file--->
- **[Module 3](./notebooks/3-setup-jupyterbook.ipynb)**, Duration: 15 minutes 
  - Hands-on session on creating the minimal version of the Jupyter
  <!---Set up the repository, add a chapter, create a table of content, build the book--->
- **[Module 4](./notebooks/4-config-jupyterbook.ipynb)**, Duration: 15 minutes
  - Book configuration, layout and personalisation
   <!---config file--->
- **[Module 5](./notebooks/5-more-jupyterbook.ipynb)**, Duration: 10 minutes
  - Executable files in a book using Jupyter Notebooks
   <!---Create a new JupyterNotebook from scratch--->   
- **[Module 6](./notebooks/6-binder-jupyterbook.ipynb)**, Duration: 15 minutes
  - Introduction to Binder and BinderHuB
  - Binder-isation to jupyterBook
- **[Module 7](](./notebooks/7-ci-jupyterbook.ipynb))**, Duration: 15 minutes
  - Continuous Integration (CI) and its role in reproducibility
  - Deploying Jupyter Book using CI tests of GitHub actions
- **[Module 8](./notebooks/8-final-demo.ipynb)**, Duration: 15 minutes
  - Guided demo of Sphinx features in Jupyter Book
  - Wrap up
  <!---for cross-referencing, citation, pdf export, collaborative workflow on GitHub repository to edit a chapter or propose edits on Jupyter Book--->
