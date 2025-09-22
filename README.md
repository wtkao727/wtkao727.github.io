# Minimal Light Academic Theme

[![LICENSE](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](https://github.com/harryrichman/minimal-light-academic/blob/main/LICENSE)

This is an academic website template, based off of Yaoyao Liu's [minimal-light](https://github.com/yaoyao-liu/minimal-light) theme.
\[[Demo the theme](https://harryrichman.github.io/minimal-light-academic/)\]  
 

## Step-by-step instructions

### 1. Make a copy of this repository in your github account

Known as "forking" the repository.

See instructions from GitHub [here](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo#forking-a-repository).
Just follow steps 1.-7. there.
You can ignore everything from "Cloning your forked repository" and afterwards.

Then, do the following steps to the files in *your* version of the repository.

### 1.1. Make your copy viewable online

The easiest way is to publish it as your GitHub Pages website.

See [instructions here](https://docs.github.com/en/pages/quickstart).

There are additional options if you have purchased your own domain name, or have access to a domain name through your school / department / institution.

Once you have finished this step, your website is *publically* viewable by *anyone on the internet*!
Great! 
Also, this means you need to finish the rest of these steps ASAP to make the website accurate and presentable.

### 2. Edit the `_config.yml` file

This contains basic data such as your name, institution, and some contact info.

Add a photo to the `assets/img/` directory.

### 3. Edit the `index.md` file

This contains the main content of your website, other than the publications and notes.
These are handled separately by a "fancier" process (by default).

Decide which sections you want to keep, which you want to delete, and which you want to reorder.
You can add new sections too, if desired.

Optionally, you could choose to write everything in the `index.md` file, but the tradeoff is you lose some built-in features.

### 4. Edit the `publications.yml` file

This contains the data of your publications.
Replace this with your own publication data, following the examples.

Some data may require you to add files to the `assets/files/` directory.
If you want to include thumbnails next to your publications, include these in the `assets/img/` directory.

### 5. Edit the `notes.yml` file

This contains the data of your expository notes, presentation slides, posters, etc.

Some data may require you to add files to the `assets/files/` directory.

### 6. Decide on other optional configuration parameters

See below

To modify the appearance of the website, edit `_layouts/homepage.html` and / or `_sass/minimal-light.scss`.

To modify the appearance of the publications and notes, edit the `_includes/publications.html` and `_includes/notes.html` files, respectively.


## Optional customization 



## Advanced options

If you know a bit how to use git, then you can edit and test your website locally rather than making every change directly on Github.

- **Using locally with Jekyll.** You may install Jekyll on your own computer and generate static web pages (i.e., HTML files) with this template. After that, you may upload the HTML files to your server.

The detailed instructions are available below.


### Using with the GitHub Pages Service

There are two ways to use this template on GitHub:

#### Fork this repository
- Fork this repository (or [use this repository as a template](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template)) and change the name to `your-username.github.io`.

- Enable the GitHub pages for that repository following the steps [here](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site#creating-your-site).

#### Using this repository as a remote theme
???

### Using Locally with Jekyll

First, install [Ruby](https://www.ruby-lang.org/en/) and [Jekyll](https://jekyllrb.com/). The install instructions can be found here: <https://jekyllrb.com/docs/installation/#guides>

Then, clone this repository:

```bash
git clone https://github.com/harryrichman/minimal-light-academic.git
cd minimal-light-academic
```
Install and run:

```bash
bundle install
bundle exec jekyll server
```
View the live page using `localhost`:
<http://localhost:4000>. You can get the HTML files in `_site` folder.






## Acknowledgements

Our project uses the source code from the following repositories:

* [yaoyao-liu/minimal-light](https://github.com/yaoyao-liu/minimal-light)
  * [Xiao-chenguang/minimal-light](https://github.com/Xiao-Chenguang/minimal-light)
  * [pages-themes/minimal](https://github.com/pages-themes/minimal)

  * [orderedlist/minimal](https://github.com/orderedlist/minimal)

  * [al-folio](https://github.com/alshedivat/al-folio)

