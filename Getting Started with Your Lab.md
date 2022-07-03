# Getting Started with your Lab Sandbox

## What tools are already installed in this environment?
- Git
- VSCode Browser Preview
- bootstrap
- jquery
- popper.js
- font-awesome  
- bootstrap-social  
- less  
- node-sass   
- del   
- grunt: grunt-sass, time-grunt, jit-grunt,  
    grunt-contrib-watch, grunt-browser-sync,grunt-contrib-copy,  
    grunt-contrib-clean,grunt-contrib-imagemin, grunt-contrib-concat,   
    grunt-contrib-cssmin, grunt-contrib-htmlmin,   
    grunt-contrib-uglify, grunt-filerev, grunt-usemin  
- gulp: gulp-cli, gulp, gulp-sass, gulp-imagemin, gulp-uglify,    
    gulp-usemin, gulp-rev, gulp-clean-css, gulp-flatmap, gulp-htmlmin  

## Additional Course Specific Notes:

### Managing your Sandbox:
1. After opening the lab for the first time or if you have not  
 used it for a while, it opens to a blank IDE. If this is   
 the case, click on the **Explore** icon on the left column   
 (the one that looks like two sheets of paper stacked together).
 Then, click on the **Open Folder** button. In the list that   
 appears, select **project** and click **OK**

2. Through your coursework, you'll be creating and managing folders 
  called **node_modules** for your web development projects.  
  If your lab has been inactive for 2 weeks, you may notice that your  
  node_modules folder is not present in your sandbox. This is expected in your sandbox, 
  so please do not worry!   

  To regenerate your node_modules folder, you can:  
  1) Open your terminal and navigate (ex: "cd") to the project folder where you'd like the node_modules folder to be stored.   
  Note: Your package.json file should also be stored in this directory.   

  1) Run the command **"npm install"** which will restore node_modules.  
   
  2) If you have lost your package.json file, you can upload   
     <a href="https://drive.google.com/file/d/1i0u4uIicR9ICLAhv9gLaqFqe4sH-ivhw/view?usp=sharing"> this copy</a> to your lab to help restore your files.

## For these sections in your course, the following notes apply.

### Setting up your Development Environment: Git and Node

**Reading: Setting up Your Development Environment:**
Git and Node: Objectives and Outcomes.
Your development environment is already set up for you as follows:

- **Text editor:** Your text editor will be Visual Studio Code.  
- **Browser:** You will be using the VSCode HTML viewer   
extension as your browser. With your HTML file open in the   
editor, right click and select **Open with Live Server**.   
There will be a message in the lower right corner stating that    
the server is started at port 5500. Now, go to the icon tool bar    
on the left side of the screen and select **Browser Preview<**   
(it should be the last icon on the bottom). A mini browser will open,   
in the address bar, type **localhost:5500/[path to your file]**  
(for example: **localhost:5500/git-test/index.html**), then hit enter.   
- **Command line shell:** You will be using the Bash shell     
in VSCode. For instructions on how to use the shell in your   
Lab Sandbox, see the Lab Sandbox Learner Resource Center article.
- **Files required for the exercises:**   
Follow the instructions given in the course. As a reminder,    
only the files in the /home/coder/project subfolder will persist    
between sessions and you should store your working files there.   

**Reading: Exercise (instructions): Setting up Git**. 
- Ignore the section **Downloading and Installing Git**.   
Git has already been installed for you.   
Proceed to some Global Configuration for Git  
- If you skip the **--global** option the name and email   
will persist across sessions for your local repository so you   
don't have to enter it every time.  

**Reading: Exercise (instructions): Basic Git Commands**. 
- As a reminder, please create a the subfolder **git-test**  
under /home/coder/project. You can do this by first clicking on  
an empty area in the explorer pane so that no file or subfolder   
is highlighted. Then click the new folder button (second from left).  

**Reading: Exercise (instructions): Online Git Repositories**  
- Please use github.com for this lab sandbox
- When pushing or cloning, you will initially see a popup message  
**The extension GitHub wants to sign in using GitHub**.   
Be sure to press **CANCEL** to close it. There will be a   
text field on the top of the screen for you to enter the   
user ID (this should be the email address you use to log in to GitHub)  
and then again for your password for your remote repository.   
After entering both, your command should succeed.  

**Reading: Exercise (instructions): Setting up Node.js and NPM** 
- Ignore this entire section, Node.js and npm have already   
been installed for you.  

**Reading: Exercise (instructions): Basics of Node.js and NPM**  
- Ignore the instructions for Installing an NPM Module.   
You will be using the live server in VSCode instead of lite-server.   
Proceed to **Setting up .gitignore**.  

### Introduction to Bootstrap

**Reading: Exercise (instructions): Getting Started with Bootstrap** 
- Download the **Bootstrap4-starter.zip** file and move   
just the **index.html** file into the **Bootstrap4/conFusion subfolder**
- Then, proceed directly to **Next, initialize a Git repository
 in the project folder** (3 bullet points above **Downloading Bootstrap**). 
 Follow the instructions before **Downloading Bootstrap** to 
 initialize a Git repository.  
- Ignore the secion **Downloading Bootstrap**.  
It has been done for you.
- Skip to **Getting Your page Bootstrap ready**.  

### Navigation and Navigation Bar
**Reading: Exercise (instructions): Icon Fonts**. 
- Ignore the instructions for Installing **font-awesome**   
and **bootstrap-social**. They have already been installed for you.   
Proceed directly to **We now need to include the CSS files for  
font awesome and bootstrap-social  ... ...** (4th bullet point).  

### Less is More!: Less and Sass
**Reading: Exercise (instructions): Less**. 
- Ignore the instructions for installing **less**.   
It has already been installed for you.  
- The command in the last part should be     
**npx lessc styles.less styles.css** (note **npx** in front).  

**Reading: Exercise (instructions): Scss**
- Ignore the instructions for installing any node modules.   
They have already been installed for you.  
- The command in the second to last part should be   
**"scss": "npx node-sass -o css/ css/** (note the insertion of **npx**).

### Less is More!: Task Runners: Grunt and Gulp
**Reading: Exercise (instructions): Grunt Part 1**. 
- Ignore the instructions for installing any node modules.   
They have already been installed for you.
- The command in the last part should be **npx grunt css**   
(note **npx** in front).
- The command **grunt css** should be **npx grunt css**.  
(note **npx** in front).
- The command **grunt** should be **npx grunt**   
(note **npx** in front). Note that browswer-sync will not work here.  
However, the web preview is already synced in the sandbox if it is open.

**Reading: Exercise (instructions): Grunt Part 2** 
- Ignore the instructions for installing any node modules.   
They have already been installed for you.</li>
- The command **build** should be **npx grunt build**   
(note **npx** in front).

**Reading: Exercise (instructions): Gulp Part 1** 
- Ignore the instructions for installing any node modules.   
They have already been installed for you.</li>
- The command **gulp** should be **npx gulp** 
(note **npx** in front).   
Note that Node Sass does not support Linux.   
However, you can still go through the steps.  

**Reading: Exercise (instructions): Gulp Part 2** 
- Ignore the instructions for installing any node modules.   
They have already been installed for you.</li>
- The command **gulp build** should be **npx gulp build**   
(note **npx** in front). Note that Node Sass does not   
support Linux. However, you can still go through the steps.