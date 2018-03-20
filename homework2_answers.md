# WDIplus-West-Coast
---
Title: Github Practice & Resume Page
Type: Homework
Duration: "3:00 - 4:00" 
Creator:
    GA 
    Course: WDIplus-WC
Competencies: Github, command line git commands, HTML, CSS
Prerequisites: Github, HTML, CSS
---
**IMPORTANT!** See the homework submission process: https://git.generalassemb.ly/WDIplus-ATX/Wiki-Page/wiki/Homework-Submission-Guide.
Submit your homework sometime **tonight** between **7 - 10pm CST** so that you can ask questions if you have them.
## Part 1 - Github
1. Create a file inside of the Week_One homework folder called `homework2_answers.md` and answer the questions below. Commit your work at each point when directed.
2. Look at the questions below and answer them as you complete this tutorial: https://try.github.io
#### Answer the following questions
1. What command do you use to setup a git repository inside of your folder?
//git init
2. What command do you use to ask git to start tracking a file?
//git add "filename"
3. What command do you use to ask git to move your file from the staging area to the repository?
//git commit -m "message"
**Commit your work.** 
The commit message should read: 
"Commit 1 - The 1st set of GIT homework answers are complete".
1. What command do you use to pull any changes from the master repository into your local repository?
//git pull
2. What command do you use to unstage a file?
//git reset "filename"
3. What command do you use to change your files back to how they were after a commit?
//git checkout --
4. Why is it important to use `--` when changing files back to a previous state? ensuring that we're resetting a file and not specifying a branch
//tells git to checkout a file, not a folder
5. Why might you want to reset your files back to a previous commit? 
//if your code got messed up somehow
** Commit your work.** 
The commit message should read: 
"Commit 2 - The 2nd set of GIT homework answers are complete".
1. What command do you use to create a branch?
//git branch -b "branchname"
2. What command do you use to use a different branch?
//git checkout "branchname"
3. Why would you want to use a branch other than the default `master`?
//being able to see changes in files, trying out different ways of doing things while still being able to keep all the braches
** Commit your work.** 
The commit message should read: 
"Commit 3 - The 3rd set of GIT homework answers are complete".
1. Give an example for when you would use `git merge` and give an example for when it would be better to submit a pull request to have your branch merged
//git merge for if you have different versions of the same file and you want to keep the information from all the different versions.
//git pull request if you're working alongside other people and want to make sure your files are peer reviewed before getting submitted.
2. What command do you use to send all of the work that you've done locally to your remote repository?
//git push origin master
** Commit your work.** 
The commit message should read: 
"Commit 4 - The 4th set of GIT homework answers are complete".
## Part 2 - HTML Video
Watch this video on HTML: https://www.youtube.com/watch?v=DxhXFpsN5I4&index=1&list=PLdnONIhPScST0Vy4LrIZiYKpFNoxgyH7J.
## Part 3 - Fake Resume Site
#### Setup your folder and files
1. Inside your Week_One homework, create a new folder called `resume_page`.
2. Change directories to `resume_page`. Create two files: `index.html` and `style.css`.
3. Using Atom, open your files and add the HTML boilerplate code.
4. Create a heading level-one tag with your name.
5. Open the `index.html` in your browser to confirm that everything is set up properly.
Reminder: To open your file with your browser, from the command line, type `open index.html`
**Commit your work.** 
The commit message should read: 
"Commit 5 - index.html file is setup".
#### Add some content to your site
1. Insert a professional image of yourself or someone else ('img' tag); it should be placed right after your 'h1' tags
2. Insert an unordered list of your last three positions ('ul' tag)
3. Create links to your (or someone's) LinkedIn and Facebook/Twitter pages ('a' tag)1. Use level-three heading tags to create headings before your positions and before your links
**Commit your work.** 
The commit message should read: 
"Commit 6 -  Added initial content for resume site".
#### Add some style to your site
1. Center your "h1" tag
2. Change the font of your "h1" tag
3. Change the color of the font of your "h3" tag text
4. Add some space on the body of your application to make your site look more appealing.
**Commit your work.** 
The commit message should read: 
"Commit 7 -  Added initial styling for resume site".
#### Add some navigation to your site
1. Create a nav bar with the links to your LinkedIn, Twitter (whichever links you had created earlier); Remove the links section that you had created earlier in the homework.
2. In the nav bar, also create a link to the 'index.html' page (maybe give it a name of `Home Page` in the bar), and a link to a file called "projects.html" (maybe call this `Projects` in the bar) 
3. Create another html file in this folder called 'projects.html'
4. Copy the contents of the nav bar and information from the 'head' tag of your `index.html` file and paste it into your `projects.html` file
5. Inside `projects.html`, create a level-two heading and add the text `Projects`
6. Check to make sure that your links work! When you click on "Projects" in your nav bar, does it open the `projects.html` document?
7. In 'projects.html', add your three most recent projects (or just make some up). To do this simply, you can use an ordered list. If you're up for a little more of a challenge, create three columns: each column should contain the title and a description of your three most recent, successful projects
**Commit your work.** 
The commit message should read: 
"Commit 8 -  Added project.html page and content".
## Part 4 - Loops
#### Stay Fresh! Looping with Javascript
1. In this folder, create a `loops.js` file which you will run execute with node.
2. Inside the loops.js file, create a loop that logs the numbers from 0-99 (ascending)
3. Inside the loops.js file, create a loop that logs the numbers from 99-0 (descending)
4. Inside the loops.js file, create a loop that logs the **EVEN** numbers from 0-98 (ascending)
5. Inside the loops.js file, create a loop that logs the **EVEN** numbers from 98-0 (descending)
6. Inside the loops.js file, create a loop that logs the numbers from 49-72 (ascending)
7. Inside the loops.js file, create a loop that logs the numbers from 81-26 (descending)
8. Inside the loops.js file, create a loop that logs the numbers from 3-90 **that are multiples of 3** (ascending)
**Commit your work.** 
The commit message should read: 
"Commit 9 - Created loops.js file".
## Hungry for more?
- Check out this tutorial (http://gitreal.codeschool.com/?utm_source=github&utm_medium=codeschool_option&utm_campaign=trygit) that includes videos about using git and some challenges for you to tackle.
##### More for your site:
1. Insert a video of your work or your favorite YouTube video ('iframe' tag)
2. Add a level-three heading above your video with a title for the section
3. Insert a table with your contact info (`table` tag)
4. Add a level-three heading above your contact info with a title for the section
5. Give the image a 1px black border
6. Give the body of the page a thicker border than the picture but only on the top and bottom of the page
7. Using HTML, insert a short blurb or biography with "p" tags
8. Using HTML, insert a short description above your "p" tag; use an "h3" tag
9. Make your name uppercase using CSS
10. Insert another image of you, or an image of one of your projects, but make it round
11. Insert a button on both pages that links to opening an email to your email address
12. Style your navigation bar
**Commit your work.** 
The commit message should read: 
"Commit 10 -  Worked on Hungry for More".
## When You're Done
#### Prep for Morning Review
1. Tomorrow's morning exercise will be a review, so come with questions prepared regarding git/github, terminal or anything else covered so far.
#### Submission
1. Inside this folder (Week_One), you should now have a file called `answers.md`, a file called `loops.js`, and a folder called `resume_page` which contains `index.html`, `projects.html`, and `style.css`.
2. You should have been adding and committing along the way, but please type `git status` one last time to make sure that everything is committed. If it's not, please commit.
3. Follow the instructions for submitting homework, found in [the wiki](https://git.generalassemb.ly/WDIplus-ATX/Wiki-Page/wiki/Homework-Submission-Guide).
4. Submit your homework sometime between **7 - 10pm CST** tonight so that you can ask questions if you have them. You can continue to work on the homework and push your solutions, but as part of your homework tonight, you should submit the issue during regular hours.