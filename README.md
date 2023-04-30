# How to Use GitHub to Host Static Content
#### by Eric Fadden 
#### first posted April 30, 2023
___
## SYNOPSIS
GitHub has become the de facto standard for software change management around the world. As a platform, however, it is capable of so much more. This document describes how to use Markdown and GitHub repositories to host static site content.

## INTRODUCTION
One of the first things that confused me when I started looking into getting into technical writing was how much content was posted to GitHub. For me, 'content' and 'GitHub' really didn't belong in the same sentence. I'd always thought of GitHub as the place my developer colleagues would go to manage their bases of code. Then I saw that people were hosting entire *sites* on GitHub (not just using it to manage the content) and I was starting to discover just how much I didn't know. 

As it turns out, using GitHub to host content is easy. It just takes an understanding of the structure. It's also free, and incredibly powerful.

## COMMITS, and REPOS and READMEs, OH MY!
The first thing we need to do is break down the basics of how GitHub is structured. 

#### Username
It is important to understand that everything you do that's publicly accessible on GitHub is based on your username. Chose a username that you're comfortable with distributing to people who you'd like to take you seriously. Your username can be changed, but doing so after you've already created a bunch of repositories (or 'repos') can break the things that are linked to those repos. It's better to start out with something you're comfortable with and not have to worry about the impression it will make six months down the road.

#### Repos
Think of repos as directories. They're individual containers that can be created to hold content specific to the thing you're currently working on. This document is in its own repo. A subsequent document will be in *its* own repo. The repo name creates the rest of the url after your username as the web address (`https://github.com/<yourusername>/<the-name-you-gave-the-repo>`).

#### README.md
If you're familiar with web development in any way, then all you need to do is think of README.md as the GitHub equivalent of index.html. It's the file that serves up the document you've written for that particular repo. The .md indicates that the file is written in Markdown rather than HTML. Markdown is a formatting language that uses various text symbols to format the content in the file. You can use Markdown to format text, create links, link images and other sites, and even use emoji :astonished:. Markdown is very well documented across the internet. A basic look at Markdown syntax can be found [here](https://www.markdownguide.org/basic-syntax/).

#### Commits
In its most basic sense, committing is the same thing as saving. Committing a change to a file in a repo sends those changes to the file. GitHub can be used to store those changes in a version of the file that won't change what's available publicly until it has been reviewed and confirmed to be accurate. However, that's a bit out of scope for the purposes of this document. For our purposes in *this* framework, assume that anything you commit will be pushed to your *live*, public repo. 

## HOSTING AND POSTING
GitHub can be used to host your content in one of two ways. This document covers posting individual documents as their own repository and uses the URL structure detailed above. Documents posted are listed as repos on your GitHub profile page and a reader must either know the URL of the document they'd like to read or go to your profile, view your repos, and then click the one that interests them. 

A second function known as GitHub Pages can be used to create an actual blog structure. Configuring and using GitHub Pages will be covered in a separate document. 

## PRESENTING YOUR CONTENT IN A PLEASANT WAY
A GitHub profile page (`https://github.com/<yourusername>`) is a powerful presentation tool unto itself, but it doesn't start out that way. Thankfully, taking control of your profile page and using it to display your own custom content is easy. 

After you've configured the options available in the Profile menu, it's time to create your first repo.

1. Click Repositories
2. Click New
3. Give the repo the *exact* same name as your username
4. Enter a description if you'd like
5. Make the repo Public
6. Check the box for 'Add a README file'
7. Click 'Create repository'

That's it. The structure now exists for you to take full control of the information presented on your GitHub profile page. The README.md file that was created during the creation of the repo functions as the source of the content for the page, and you can now write a document in Markdown from right within GitHub that will display on your profile page along with any customizations you made in your profile, such as your photo.

Additionally, you've now created a base page from which to display your additional repos (documents). Repos that you choose to pin or highlight can be displayed on your profile page. A visitor can also click on your repositories to see a full list of all the repos you've created. So long as a README file exists in those repos, they'll see what you've written upon clicking the repo name. 

## EDITING README.md
While you are free to use whatever connectivity and text editing methods you choose, it is worth noting that GitHub comes with its own text editor out of the box and is perfectly suitable for those who are just starting out. The process for using it is very simple:
- Locate the file
- Edit the file
- Commit the changes

#### Locate the file
From your profile, click into your \<username> repo. Then click the README.md file.

#### Edit the file
![edit button](/s1.png)
Use the edit button in the inline toolbar to enter edit mode. Edit your Markdown as you see fit.

#### Commit the changes
![commit changes](/s2.png)
Now it's time to commit the changes. Committing gets back to GitHub's change management roots and while the options might look scary, they're really quite simple, especially for our purposes. While using these entry fields isn't absolutely necessary, it's good to get in the habit of using them should you eventually find yourself working on a team that uses GitHub. They're also helpful in that they keep *you* organized as your document library grows. 

Use the first line to just say what you did. That could be 'created readme file and added a couple lines'. It could be 'added an image file'. It could be 'fixed a typo.' The next line is used for when additional information is necessary. In 99% of cases when you're using GitHub for publishing your own content this step won't be necessary.

Leave it set to 'Commit directly to the `main` branch and click 'Commit changes.' The edits will be saved to the README file in the repo and your changes should be reflected on GitHub. Note that changes are generally reflected quite quickly but can, at times, take up to a minute or two to show up.

## CREATING ADDITIONAL CONTENT
So you have a GitHub profile, you've added some base content to your profile page and committed the changes, and now you want to start posting additional information and documents. All you need to do is start creating repos and making sure they have README.md files in them. 

Let's say you want to create a post on the delicate (and potentially dangerous) procedure for giving a cat a bath (note/cat dad PSA: don't bathe cats unless its absolutely necessary. In most circumstances, a cat will keep itself clean and bathing them can actually be detrimental to their health). The procedure is largely the same as the one we just went through.

From your profile:
1. Click Repositories
2. Click New
3. Name the repo something that makes sense (how-to-bathe-cat)
4. Make the repo Public
5. Check the box for 'Add a README file'
6. Click 'Create repository'

Since we're treating README.md files the same as we'd treat an index.html file, all we need to do is edit the README in Markdown to create our post. Once published (or committed), a link to `https://github.com/<yourusername>/how-to-bathe-cat` will take us directly to the README file in the `how-to-bathe-cat` repo in your GitHub profile.

## CONCLUSION
In this document we learned about the power of GitHub, not only as a change management system but as a publishing platform for static content. We took control of our personal GitHub profile and added custom content. We also learned how to use repos to create additional content and posts that can be displayed from our personal profile page. Finally, the document demonstrates the ability use text and document formatting, unordered lists, ordered lists, and images using Markdown.
