# How to Host a Resume on GitHub Pages

This README tutorial goes over the steps on how to create a [resume written in the Markdown markup language, and hosting it on GitHub pages](https://pandorasjuicebox.github.io/pandoras-resume/). Throughout this document, the general principles of Andrew Etter's book "Modern Technical Writing" is demonstrated and later explained. No prior experience in Markdown or GitHub is needed to start this tutorial.

---
## Contents
* [Prerequisites](#Prerequisites)
   * [Getting Started](#Getting-Started)
      * [Choosing a Markdown Editor](#Choosing-a-Markdown-Editor)
      * [Signing up for GitHub](#Signing-up-for-GitHub)
* [Instructions](#Instructions)
   * [Create a Repository](#Create-a-Repository)
   * [Setting Up GitHub Pages](#Setting-Up-GitHub-Pages)
   * [Choosing a Jekyll Theme For Your GitHub Page](#Choosing-a-Jekyll-Theme-For-Your-GitHub-Page)
   * [Hosting Your Resume on GitHub Pages](#Hosting-Your-Resume-on-GitHub-Pages)
   * [Viewing your GitHub Page](#Viewing-your-GitHub-Page)
      * [Viewing Your GitHub Page By URL](#Viewing-Your-GitHub-Page-By-URL)
      * [Viewing Your GitHub Page Through the Repository](#Viewing-Your-GitHub-Page-Through-the-Repository)
* [Principles of Technical Writing](#Principles-of-Technical-Writing)
    * [Defining the Audience](#Defining-the-Audience)
    * [Basic Functional Documentation (BFD)](#Basic-Functional-Documentation)
    * [Style](#Style)
* [More Resources](#More-Resources)
* [Authors and Acknowledgements](#Authors-and-Acknowledgements)
* [FAQs](#FAQs)

--- 

## Prerequisites

### Getting Started 
By the end of this section, you have:

* Downloaded a Markdown editor.
    * Developed a grasp on the markdown markup language, if you never used it before.
* Created a GitHub account.

#### **Choosing a Markdown Editor**
* Popular choices include [Atom](https://atom.io) and [Sublime Text](https://www.sublimetext.com). There are also [other options](https://www.shopify.com/partners/blog/10-of-the-best-markdown-editors).
* If not familiar with Markdown, [an easy-to-follow tutorial resource is available](#More-Resources). 

#### **Signing up for GitHub**
* Sign up for GitHub [here](https://github.com/join).
* You only need a [personal user account](https://docs.GitHub.com/en/free-pro-team@latest/GitHub/getting-started-with-GitHub/types-of-GitHub-accounts#personal-user-accounts). 


---
## Instructions


### Create a Repository 
By the end of this section, you have:

* Created a new repository on GitHub.

#### **Creating the Repository**

1. Log into your [GitHub](https://GitHub.com) account.
2. At the top right corner of the website, click on the '**+**' symbol and select "**New Repository**".

    ![A GIF showing the step 2](https://media.giphy.com/media/qQZa1Vx4aorKPBrQPK/giphy.gif)

3. Give your repository a name. Do note that GitHub Pages use the repository name as part of the shareable link.

    ![A GIF showing a repo name being typed](https://media.giphy.com/media/2Y6FzEnjSPx7WD24bf/giphy.gif)

4. Choose "**Public**" visibility for your repository. 
5. Initialise the repository with a README file. It is in this README file where we describe the purpose of the repository.

    ![A GIF selecting the checkbox to initialise repo with a README](https://media.giphy.com/media/cw1uwSqkh0UrBSHuUM/giphy.gif)

6. Finally, click on "**Create Repository**" to finish.

---

### Setting Up GitHub Pages
By the end of this section, you have:
* Enabled the creation of GitHub Pages for your repository.

#### **Enabling GitHub Pages**
1. At the main page of your repository, click on "**Settings**". This is located on the toolbar under the repository's name. 

    ![A GIF clicking on "Settings"](https://media.giphy.com/media/1GsvbtjwWk8WHO1TB7/giphy.gif)

2. Scroll down until you see the section called "**GitHub Pages**".
3. GitHub Pages is disabled by default. To enable, click on the dropdown menu under "**Source**" and choose the "**main**" branch.

    ![A GIF showing how to select a branch to enable GitHub Pages with](https://media.giphy.com/media/7KaHx9nkQphxX3AX8H/giphy.gif)

4. Click on "**Save**" to finalise changes. GitHub Pages is now enabled. 

---

### Choosing a Jekyll Theme for Your GitHub Page

*NOTE: This section only covers the easiest way to choose a Jekyll theme, which is using the theme chooser which is directly available but provides a limited selection. [Being able to use other themes is possible](https://GitHub.blog/2017-11-29-use-any-theme-with-GitHub-pages/), but may require further reading.*

By the end of this section, you have:

* Chosen a Jekyll theme for your GitHub Page.

#### **Finding and Selecting a Jekyll Theme**
1. Ensure that GitHub Pages [is enabled](#Setting-Up-GitHub-Pages). 
2. In the GitHub Pages section of your repository settings, click on "**Theme Chooser**".

    ![A GIF that shows where Theme Chooser is located in the GitHub Pages section](https://media.giphy.com/media/Urr9PIHgDGK81D1qks/giphy.gif)

3. This redirects you to a page where you select and preview a handful of themes. Choose the one that you like best. 

    ![A GIF showcasing a few Jekyll themes from Theme Chooser](https://media.giphy.com/media/4MWzACwGc0QR8kwNQi/giphy.gif)

4. When you have decided on a theme, click on "**Select Theme**" to use it as a theme for your GitHub Page. You can change this at any time.

---

### Hosting Your Resume on GitHub Pages

By the end of this section, you have:

* Created or re-created a resume in Markdown.
* Uploaded the resume to the repository.
* Successfully hosted your resume on GitHub Pages.

#### **Uploading Your Resume on GitHub**
1. If you need still need to set up your Markdown environment, refer to the [setup guide](#Getting-Started).
    * If you are yet to be familiar with Markdown, [an easy-to-follow tutorial](#More-Resources) is available.
    * A [Markdown cheat sheet](#More-Resources) is also available for reference. 

2. Open your text editor and create a new Markdown file called ```index.md```. 

3. Create or re-create and format your resume in this Markdown file.
4. When that is done, head over to GitHub and navigate to the main page of your repository. 
5. Above the file table where the contents of your repository are stored, click on "**Add file**" then select "**Upload files**". It will redirect you to an upload page. 

    ![A GIF showing how to upload files from the repository](https://media.giphy.com/media/gL6NYRPMIXzR4wdGxQ/giphy.gif)

6. Drag or choose ```index.md``` from the directory it is from to the page to upload the file. In this tutorial, the drag function will be used.

    ![A GIF dragging to upload index.md to GitHub's uploader](https://media.giphy.com/media/yPxRQOsRXkFgjvmsaK/giphy.gif)
7. To finalise or commit these changes, navigate down to the **Commit Changes** section. Adding a description is optional. Click on "**Commit Changes**" to upload ```index.md``` to the repository. 

    ![A GIF showing how to commit changes and upload index.md to the repo](https://media.giphy.com/media/pNg5Omih4NqWT8ZP08/giphy.gif)


---

### Viewing your GitHub Page

By the end of this section, you have:
* Successfully viewed your resume on your GitHub Page through at least one of two methods

#### **Viewing Your GitHub Page By URL**
1. Your main GitHub page is ```https://<Your GitHub Username>.github.io/```. 
    * Should you have named this repository with your username, visiting the URL above will let you view your GitHub Page and see your resume. 
2. To view your resume, type ```https://<Your GitHub Username>.github.io/``` then add the name of the repository at the end. In the case of this tutorial, it would be ```https://pandorasjuicebox.github.io/pandoras-resume/```.

    ![A GIF showing the address being typed into a browser toolbar](https://media.giphy.com/media/x4DlV7Ix9MqO6QB9sK/giphy.gif)

3. You should be able to see your resume, which is now on GitHub Pages!
    ![A GIF showing the resume being viewed](https://media.giphy.com/media/tBy2tFiyVmMwWz4vK5/giphy.gif)

#### **Viewing Your GitHub Page Through the Repository**

1. Navigate to the main page of your repository.
2. On the lower section of the right sidebar under **Environments**, click "**github-pages**". The site will redirect you to the Deployments page.

    ![A GIF showing the "Environments" section on the side bar](https://media.giphy.com/media/SIsLoNZf5S5mjRrgfg/giphy.gif)

3. Multiple deployments may be present. We only care about the latest deployment, which is it at the very top. Click on "**View deployment**" to visit your GitHub Page. 

    ![A GIF clicking to view deployment to see the GitHub Page](https://media.giphy.com/media/4Ksm5Hq6xN2ms4TxUk/giphy.gif)

4. You should be able to see your resume, which is now on GitHub Pages!
![A GIF showing how it redirects to the GitHub Page, and the resume can be seen](https://media.giphy.com/media/ew8ksjUUt53evHZoHX/giphy.gif)

---
## Principles of Technical Writing

#### Using Static Websites

#### Using a Lightweight Markup Language with a Static Site Generator

#### Why Use a Distributed File Sharing System

---
## More Resources
* [Easy Markdown Tutorial](https://www.markdowntutorial.com)
* [GitHub Flavoured Markdown Reference Sheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)
* ["Modern Technical Writing" by Andrew Etter](https://www.amazon.com/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

---
## Authors and Acknowledgements 
#### **Author**
* [Charina Duenas](https://github.com/pandorasjuicebox)  
#### **Group Members**
* [Emily Nguyen](https://github.com/emily0906) 
* Rajinder Singh 
#### **GitHub Page Theme**
* [Steve Smith](https://github.com/orderedlist) 
---
## FAQs
**Why is Markdown better than a word processor?**
* It works with any platform. All you have to do is to download a Markdown editor on your platform of choice -- whether that's a laptop computer, tablet, phone, etc. -- and start writing. 
* Unlike with a word processor where you are limited to the capabilities of the program, there are many Markdown editors to choose from that may suit your needs.
* Markdown has inline styles, but is still plain text. So it can be read by any program, including the ones you make.

**Why is my resume not showing up?**
* Make sure GitHub Pages is [enabled](#Setting-Up-GitHub-Pages). 
* Your resume must named ```index.md```, or it will not be recognised by GitHub Pages. 
* Ensure that ```index.md``` is not empty.
