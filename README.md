# Purpose
This readme will explain how to host a website on GitHub Pages for the purpose of technical documentation so you can build a website like this:
![][https://github.com/TechComUser/TechComUser.github.io/blob/main/2024-03-07-21-31-59.gif?raw=true]
All in just a few minutes! GitHub Pages allows you to host a lightweight website, for free. All it takes is a GitHub account and just a little bit of knowledge. Setting up a website usually takes a lot of effort and technical know-how; GitHub Pages sites can be up in a matter of minutes.
# Prerequisites
- A free [GitHub](https://github.com/) account
- Content, like a resume, formatted in Markdown. For more information, see [Markdown Tutorial](https://www.markdowntutorial.com/) for more detail 
# Instructions
## 1. Create a repository on Github
We will begin by creating a repository for our website. This is where we will place the content and code for our new site.

1. Navigate to your [GitHub home page](https://github.com) and create a new repository by clicking the green "New" button on the left-hand page. If you have just created a new account, then the button should read "Create Repository". 
2. Click "Create Repository". You will be taken to a new page. 

3. Give your repository a name. It should be named "\[username].github.io". For instance, if you had the account "test", you would name it "test.github.io". 

4. Ensure "public" is checked, and give it a description if you want to, but it isn't needed. 
5. Make sure "Add a README file" is unchecked, as it will create an unneeded file for this purpose.
6. Set your repository to public. This is needed for your site to be visible. Your page should look like this.

![[Pasted image 20240307234550.png]]

5. Click "Create repository" at the bottom of the page. You will be taken to a new page. This is where the code for our site will live. This is the value of using GitHub: it gives us a place to store our files outside of our machine. Using a site like GitHub allows us to utilize *distributed version control*. Etter recommends using services like GitHub for technical documentation because they perform well, allow you to work on files without internet access, and allow multiple people to work on the same file. For our purposes, GitHub allows us to work on our website without needing to install any additional software.

## Step 2. Create your index.md
We will now create our website's home page.

1. On your repo's landing page, click on the link "creating a new file" within the blue section labeled "Quick setup". Your page should look like this:
![[Pasted image 20240307234700.png]]
2. Name your file. At the top of the page, enter "index.md". This will become the first page of our new website. It is very important that you name it correctly, as otherwise your site will not have a first page.
3. Create your content! Your site will be written based on Markdown, which a lightweight markup language. Etter recommends using such a language because they are human-readable - anyone without technical experience can read and understand a Markdown file just fine. For more documentation, check out the link in "More Resources". These instructions assume you already have a resume or similar content formatted in Markdown. In any case, your page should look somewhat like this:
![[Pasted image 20240307235058.png]]
5. Commit your changes. "Commit" in this context is similar to the word "Save" in Word. It is called a commit because we are working with a distributed version control system, which basically means we enter information about this change or even roll it back in the future if we wish. 
6. Click "Commit changes..." at the top-right of the page.
7. Enter a short description of your changes in the "Commit message" textbox, or optionally, a longer one. It should look like this:
![[Pasted image 20240307235330.png]]

## Step 3. Push to GitHub and enable Pages
We will now need to publish our site and make it available for public view.

1. Click on "Settings" on the top banner.
2. Go to "Pages", located in the sidebar of the Settings page, under the heading "Code and automation". You will be taken to this screen:
![[Pasted image 20240308001248.png]]
3. Click the button labeled "None" under the "Branch" heading. A dropdown should appear. 
![[Pasted image 20240308001411.png]]
4. Click "main".
5. Click "Save". At the top, it will say "GitHub Pages source saved." Your website is now being deployed. 
6. Wait on this screen as it may take up to a minute.
7. Refresh the page. At this point, you are done. You will see a link to your site at the top of your page. Congratulations! You just made your first website! As you have seen, GitHub Pages is best-suited for very small websites, such as a personal website or a small blog. It runs off of **Jekyll**, which is a *static site generator*. Andrew Etter recommends using static site generators for technical documentation because they are very quick to set up, have little technical overhead, and are well-suited for very small applications like this.
# More Resources
- [Jekyll](https://jekyllrb.com/)
- [Markdown Tutorial](https://www.markdowntutorial.com/)
- [GitHub documentation](https://docs.github.com/en/get-started/start-your-journey/hello-world)
- [Wikipedia on version control](https://en.wikipedia.org/wiki/Version_control)

# FAQ

## Why should I use Markdown over a traditional word processor?
In Word, Google Docs, or other word processors, you need to format your text as you write it. You have a lot of options for font size, colour, layout and so on. This might be great if you're just making a pamphlet or a one-page document, but it becomes really excessive depending on the amount of material you need to go through.

Markdown allows you to focus first on the *content* of what you're producing, rather than making it look good right away. You can let your automated tools handle that for you.

## Why is my website not showing up?
It may due to a few reasons. Here are a few ways of troubleshooting your site.
- Wait for your website to publish. It may take a while, so be patient.
- Ensure your index file is named correctly. It should be named `index.md`, otherwise you may get an error from GitHub.
- Make sure the formatting in your file is correct.
# Credits
I would like acknowledge my groupmates Ethan Ducharme and Ben Clark for proofreading and valuable input. I thank Andrew Etter for writing *Modern Technical Writing*, which has been a valuable resource through the course. I also thank [Matt Graham](https://github.com/mattgraham/) for authoring the Midnight Jekyll theme, which I used to theme my resume.
