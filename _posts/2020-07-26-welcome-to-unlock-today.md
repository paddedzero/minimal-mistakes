---
title: "Welcome to Unlocked Today!<br>Building your website with Github Pages"
excerpt_separator: "<!--more-->"
date: 2020-07-26T18:00:05-04:00
categories:
  - blog
tags:
  - Jekyll
  - update
markdown: kramdown
---

I've decided to move my page to **Github Pages**. Have decided to start afresh and not migrate my **Wordpress** content. If this is your first time working with things like <span style="color:grey">**git, github, jekyll, markdown or static file generators**</span> - starting afresh might be a good option.

If all these terms seems new to you, not too late to pick them up no matter what your background is. Lots of tutorial videos on using git and there isn't as much programming to muck around on contrary belief if you are looking to just start with something basic. Plus this is a **FREE** option for hosting your webpages and it's definitely worth it to pick this up.

So welcome to
## **<span style="color:lightblue">"Unlocked.Today"</span>**

Since I decided to setup my pages at **Github Pages**, though it was worth to document some of the journey down here.

### **CONTENTS**

>include content that is diplayed below

**`step 1 - get a github account`**

Register your account at
  www.github.com
![www.github.com](/assets/images/2020-07-26/signup-github.png){: width=150 height=300 style="float:right; padding:16px"}

Github is used as a hosting platform for software development and version control. Commonly used for open-source projects and is **FREE**.

Once you've created your account you will be brought to this page
![www.github.com](/assets/images/2020-07-26/create-a-new-github-repository.png)
Give it a recognizable name to yourself, take note this will be accessible to the world unless you set it to private. However, since we are setting up a website. This will be set to public. Imagine this like your giant folder accessible through the internet.

**`step 2 - setup github pages`**

the fun bit. at this point, you can jump to **STEP 3** and then come back here. Or you could set this up and just copy the Jekyll template into our Github repository here.

click <span style="color:grey">**>settings**</span> in your new repository
![gitsettings1](/assets/images/2020-07-26/github-pages-part1.png)
Fill in your new page name as per above. The username needs to match your profile username. This is how the internet will reach your **Github Pages** (website) at **\<USERNAME\>.github.io**

If you scroll further down the same click <span style="color:grey">**>settings**</span> page you will come across this
![gitsettings2](/assets/images/2020-07-26/github-pages-part2.png)
For now just take note that if you want to use your own customized URL, this is where you need to add it in. This setting also allows you to choose the pre-defined themes created by Github Pages but for the purpose of this exercise we will be using a customize one. So just mark this page for now for future references.

For additional details on how to setup **Github Pages**, you can go here
https://guides.github.com/features/pages/

**`step 3 - fork a theme from a Jekyll theme template`**

So up to this point, what we've done is to create a page but its empty.
So **Github Pages** is powered by **Jekyll** and leverages on **Markdown** to write the text.

To keep it simple, we can use a theme template from one of the many jekyll developers on **Github**. The power of **Github** is this, it allows sharing at the snap of the hand.

For the purpose of this example, I am going to use minimalmistakes which I used as a base template for my website. There are plenty of other options out there, just to list a few here.

- [minimalmistakes](https://github.com/mmistakes)
- [lanyon](https://github.com/poole/lanyon)
- [jekyll now](https://github.com/barryclark/jekyll-now)
- [mojombo](https://github.com/mojombo/mojombo.github.io)

Keep in mind, I am going for the **FREE** and **BASIC** site yet gives you the power of a similar website like Wordpress.

So with that in mind, let's go to github and click on the git link for **minimalmistakes** which brings you to a similar looking page below
![fork1](/assets/images/2020-07-26/fork-part2.png)

What we are trying to do is use this repository as our base. There are a few ways to do it. If you have performed step 1 and 2 then you just need to download and upload back into that page.

Else, I am going to show you another method which is forking.
On the right hand side of the screen you will see the fork button.
![fork2](/assets/images/2020-07-26/fork-part1.png)

You will then have the entire repository of minimalmistakes in your folder.
All you have to do now, is follow **STEP 2** to change this repository name as well as setup your custom domain name if you have one.

**`step 4 - customization of site details`**
At this point, give it around 10 minutes to populate. By now your page should be up at the **\<USERNAME\>.github.io**. You can check it out.

Next you need to customize the file - `_config.yaml` which exists in the main folder of your "forked" repository. To keep it simple, just click the file and it will open up this page.
![editfile-part1](/assets/images/2020-07-26/config-yml-part1.png)

For the most part, you can edit all your files in the similar way.
Next, edit this file. There is an icon for edit on the right hand side of the box.
![editfile-part2](/assets/images/2020-07-26/config-yml-part2.png)

Customize the config.yaml to match your preferred details. For a start, try changing the URL to match your url and also the various descriptions. Change values which are after the **':'** on the right hand side of the code.

Take note that every character, space or a character break means something here.

Check out the **Markdown** site for a guide to commands that you can use.
https://www.markdownguide.org/cheat-sheet

**`step 5 - first steps to writing your posts`**

I propose for a start that you just start writing your first post to get some familiarity with **Markdown** and how **Github Pages** works.

To write your firsts posts. Go to **>_posts** folder in your repository.
There you will see a few samples. Ensure that the new posts follows that naming structure which is **"YYYY-MM-DD-title-no-spaces"**. The file names should not contain any blank spaces, you can use dashes to indicate spacing instead.

Now you have setup your first jekyll site with github pages and have published your first post.

**DONE with setup!**

---
Next is to customize your blogging experience by setting up your writing environment

Recommend getting Visual Studio Code which is free and install extensions such as
ext 1
ext 2

once you setup your visual studio code, here are a few things to learn at a glance

1. setting up git pages access
2. serve local jekyll website for previews
3. commit and push your files to github
4. snippets, what are they

thats it
