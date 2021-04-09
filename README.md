# Kumar_Vishwesh

# Cookbook: Online Portfolio Website: A hands-on guide
## 1.	What is online portfolio website
•	A personal website presence is a great way to showcase your work. 
•	It can also be extremely valuable for the data science job search.
•	A portfolio gives you the ability to share a high-level overview of your data science projects. 
•	It takes a deeper dive into your projects than your resume, but is less technical and overwhelming than your github repos. 
•	This is the perfect level for recruiters and data science managers.
## 2.	How shall we create online portfolio?
•	We will use GitHub pages to serve the README of your project as a website. GitHub hosts these websites, so they are free to you. 
•	We will be using markdown to build a portfolio.
•	After we set up our website, we will use one of the existing themes from Jekyll to give it a more aesthetic feel.
•	Result: https://krvishwesh54.github.io/Kumar-Vishwesh/

## 3.	Steps to create online portfolio
### 3.1	Step 1: Create a new GitHub repo
First, we create a new repo and initialize the README.md file.
 
### 3.2	Step 2: Go to settings and scroll down to the GitHub Pages section
Click the repo settings tab at the far right of the list.
 
Scroll down to the bottom where the Github Pages box is located.

 
Switch the source from None to master branch or main
 branch.Step 3: Check that your website is working  
Click the link at the top of the GitHub pages section to go to your new website.
 
 
The web page should show the contents of the README.md of your repo.
Congrats! you already have a working website. If you are getting a 404 error, don’t worry. Sometimes it takes a little bit of time for the server set up (It can take as long as 5 minutes from my experience)
### 3.3	Step 4: Add website content to README.md file
Since the web page is displaying the README, all you have to do is change the it to show what you want on your website. You do this using markdown (cheat sheet: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet; To add emoji: https://gist.github.com/rxaviers/7360908 )
If you already have projects with detailed README files, you can just copy and paste them in.
First click the edit icon in the top right of the README.
 
Next fill this section with the content you want on your website. For mine, I just used project overviews from some of the projects I did previously. I also linked back to the other repos and added a few simple pictures. The markdown guide (above) shows you how to do all of these things.
A sample README.md:
https://raw.githubusercontent.com/krvishwesh54/Kumar-Vishwesh/main/README.md

You can click the preview changes button to see what everything will look like on the web pages.
To add pictures to the website, you need to create a separate images folder. You use the path of the images in that folder to get them to show on the screen.
To create an images folder in github, you click the create new file button over the contents of the repo.

 
In the file destination, type images/README.md
  

after you type the / it will auto turn images to blue like that
Then go to the bottom and click the “commit new file” button. You don’t have to add any content here.
When you go back to your portfolio, you should now see an images folder.

 
Now, click into the images folder and upload the files that you want to show on your website.
To get the image to show on your website, you must use this path format in your markdown: ![](/images/your_image.png)
### 3.4	Step 5: Choose a theme

At this point, you should have a very basic website that looks exactly the same as your github repo README. If you want to add some basic formatting, you can use a theme from Jekyll.
To do this, you click on the repo settings button again and return to the Github Pages setting box.
This time you click the “Change theme” button.

 
At the top, select the theme that you want and click select theme.

 
If you return to your repo, you should now have a _config.yml file. This is what manages the theme. If you delete it, the theme will go away.
Now go to your website, you should have a simple portfolio that uses the theme of your choosing!
### 3.5	Step 5: Create QR code

Generate QR code through URL: https://www.the-qrcode-generator.com/
using your portfolio URL.
