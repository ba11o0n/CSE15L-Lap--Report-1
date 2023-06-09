# Lab Report 1 
Before learning the different tools and techniques as a programmer for this course, let's learn how to set up your accounts and installing the needed source-code editor. 

By the end of this tutorial, you should be able to: 
- [ ] Download and practice using the source-code editor VSCode 
- [ ] Remotely connecting to the server 
- [ ] Try different commands and learn what they do 
- [ ] Create a Github account and practice creating repositories 
- [ ] Learn about the help of markdowns 

We will check off each of these objective as we go! 
     

## **Step 1: Creating Your CSE15L Account**
1. Go into this [link](https://sdacs.ucsd.edu/~icc/index.php) and search up your existing account with your school email and PID. 

   <img src="15p1_1.png" width="600" height="300"/>
   
   
2. Copy the account name that is listed uner the section *Additional Accounts* that begins with cs15l as the first five characters. Then, at the top of the page, a highlighted box in light yellow will tell you to reset your password using the [link](https://sdacs.ucsd.edu/~icc/password.php).  
 
   <img src="15p1_2_1.png" width="700" height="600"/>
   
   
3. There are two links but click on the link that is specifically listed under for "Student, AX, or Course-Specific Student Accounts". 

   <img src="15p1_3.png" width="600" height="300"/>
   
   
4. Scroll down and paste the account info that you have copied from step two before submitting. 

   <img src="15p1_4.png" width="600" height="500"/>
   
   
5. Change your password as instructed on the new page and verify with your email and follow password synchronization [steps](https://blink.ucsd.edu/technology/network/access/ad/post-change-instructions.html#Faculty,-Staff-&-Health-Using-M) towards the end. 


## **Step 2: Using Visual Studio Code**

1. If you do not have Visual Studio Code installed in your computer, follow the instructions to install using their [website](https://code.visualstudio.com/) or click on the image below. 

     [<img alt="Visual Studio Code" width="60px" height="60px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/2048px-Visual_Studio_Code_1.35_icon.svg.png" />](https://code.visualstudio.com/download)


2. After installation, open VSCode.

    <img src="openvsc.png" width="500" height="400"/>


3. Open a new file giving it a name that you like, followed by .java at the end. Then go into the file you just created.

    <img src="vscopenfile.png" width="500" height="300"/>
    
    <img src="vscnewfile.png" width="650" height="250"/>


4. On the left panel, click on the first logo on the right of the file's name you just created to create a new file. You can name it with the name you like but followed with .txt at the end as it should be a text file. Then save it to your computer. 
    
    <img src="vscmaketxt.png" width="300" height="350"/>


5. Write some text in the file (eg. Hello, world!).

    ![Image](vscsometext.png)


### Good job, we were able to: 
- [x] Download and practice using the source-code editor VSCode 


## **Step 3: Remotely Connecting using VSCode**
1. If you are using Mac, git is already installed in your computer. However, you will be required to [install](https://gitforwindows.org) git for windows. You can also click on the image below. 

     [<img alt="Git" width="100px" height="100px" src="https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png" />](https://gitforwindows.org)

2. Open a terminal in VSCode (from the file created in step two) by doing Ctrl or Command + ', or Terminal --> New Terminal. In the terminal, write pwd as your first command line and press enter. 

3. Type in the command shown below in your terminal and replace == with the letters that were assigned to you for your course-specific account from step one part two. NOTE: The *$* in the command signifies the starting point for you to type, so *do not* include it when inputting into terminal. 

`ssh cs15lsp23==@ieng6.ucsd.edu`

4. A message will pop up as you are connecting to the server for the first time. Type in yes and press enter. 

`Are you sure you want to continue connecting (yes/no/[fingerprint])?`

5. Then type in the password that you changed into from step one. NOTE: You might notice the characters you type for your password is invisible, but that is because the password is being hidden! Do not panic and type in the correct password that you changed to and type slowly if needed to assure that it is correct. The output should be somewhat similar below after you enter in your password. Values of cluster status will differ due to different remote connections. 

6. You have successfully connected your terminal to a computer in the computer basement and any commands you run can be run on that computer. 

### Good job, we were able to: 
- [x] Download and practice using the source-code editor VSCode 
- [x] Remotely connecting to the server 


## **Step 4: Running Commands**
There are several different commands that you can try to run in the terminal either on your computer or using the remote computer with ssh. 

`1. cd`

`2. cd ~` 

`3. ls`

`4. ls -a`

`5. ls -lat`

`6. ls <directory>`

`7. cp /home/linux/ieng6/cs15lsp23/public/hello.txt ~/`

`8. cat /home/linux/ieng6/cs15lsp23/public/hello.txt`

*NOTE*: The "hello.txt" at the end in command seven and eight were listed as an example. For your own work, you should have it as your text file that you created from step two part five. 

Try different combination and try to see the different outputs. You can try to see other commands if interested through other documentations online.  

Before you try these commands, you can log out of the remote server in the terminal by doing Ctrl-D OR run exit as the command OR kill the terminal and open a new one in VSCode. 

### Good job, we were able to: 
- [x] Download and practice using the source-code editor VSCode 
- [x] Remotely connecting to the server 
- [x] Try different commands and learn what they do 


## **Step 5: Github, Github pages, and git** 
[Github](https://ucsd-cse15l-s23.github.io/week/week1/github.com) is a web service that helps store and share code. Many utilize Github in order to publish their great work as programmers. [Git](https://git-scm.com/) is a tool within Github that stores and retrieve these codes. In addition to projects, you can create your own professional portfolio website through the help of [Github Pages](https://pages.github.com/)

Let's learn how to use Github so your own projects can be published, reflecting your skills and amazing work.

### Creating your Github Account: 
1. Follow the steps to create your account on [Github](https://www.github.com/)

2. Once created, find the + icon on the navigation tab at the top right and reate a new repository (a folder or directory). 

    <img src="ghrepo.png" width="800" height="300"/>

3. Give the repository a name of `cse15l-lab-reports`, and scroll down to click on "create". 

    <img src="ghnameit.png" width="500" height="600"/>

4. With the new screen of display, find "creating a new file" hyberlinked at the top section and click on it to create a new file named `index.md` and write some texts of your choice before you "commit new file" at the bottom when you scroll. NOTE: You just created a public Github repository (can be changed to private if you like) and the link can be shared. 

5. Find "Settings" at the top of te repository and find "Pages" on the left side of the panel. 

6. Under Branch section, change where you see "none" to "main" as the source for the Github Pages and save. 

7. Your screen will load into a new display, so give it a few minutes or refresh your page. A message in a box will pop up saying "Your site is live at <url>". Click on the link and you would see the result of your work in the file in a new page.
     

    <img src="gh404.png" width="400" height="400"/>
     
*IMPORTANT*: 
If the page displays something similar to "404 File not found" shown in the image above, do not panic. Go back and copy the link that was given to you and paste it into the search engine. Before you press enter, add in the name of your main file that you want to display followed by `.html` (eg. your main file that you want others to see is titled apple.md in your repository, so the url will be something like `https://yourName.github.io/CSE15LReport1/mainFileName.html.

### Good job, we were able to: 
- [x] Download and practice using the source-code editor VSCode 
- [x] Remotely connecting to the server 
- [x] Try different commands and learn what they do 
- [x] Create a Github account and practice creating repositories 


## **Step 5: Make Your Texts Fancier, More Designs** 
The `.md` that you have written at the end of your index file stands for "Markdown" that allows you to add formats to text and writings. There are [common markdown options](https://commonmark.org/help/). Use it to style your texts. 


### Good job, we were able to: 
- [x] Download and practice using the source-code editor VSCode 
- [x] Remotely connecting to the server 
- [x] Try different commands and learn what they do 
- [x] Try different commands and learn what they do 
- [x] Create a Github account and practice creating repositories 
- [x] Learn about the help of markdowns
