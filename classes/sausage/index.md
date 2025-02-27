---
layout: class
week: 1
title: Why we’re here, how we approach graphics at The New York Times and making the sausage of the internet
---
After doing basic first-day-type activities and introductions, I'll give a short lecture and then we’ll get right into using Github.

##Lecture
[Sit back and enjoy](lecture.html).
##Lab
Before we do anything super useful or innovative with our soon-to-be-shiny data skills, we need to be able to have a place to write our files so they are public on the internet. This exercise will make sure everyone is properly set up to publish stuff to Github.

Github might at first seem tricky and a little bit of overkill, but it’s the industry standard for sharing code. Nearly every major code library you will encounter these days is hosted on Github.

More relevant for this particular class though, Github offers free hosting of websites. For instance, this entire syllabus is being served from Github for free (as is Kevin’s <a href="http://kpq.github.io/">porfolio site</a>). So it’s pretty handy.

###Signing up for Github
If you’ve never used <a href="http://git-scm.com/">Git</a> or <a href="https://github.com">Github</a> before, don’t worry, it’s not as scary as it may seem at first. It’s basically like <a href="https://www.dropbox.com/">Dropbox</a> for programmers, with enough goofy names and concepts to make it all feel a little more complicated than it really is.
<ol class="steps">
  <li>
    <p>First, go to <a href="https://github.com/">Github</a> and create a username and password, etc.</p>
    <p><a href="https://github.com/"><img src="github-welcome.png"></a></p>
  </li>
  <li>
    <p>Once you are logged in, click on “Create a repository.” You should see this screen:</p>
    <p><img src="create-repo.png"></p>
    <p>Name your repo “dataviz-home”.</p>
    <p>Make sure you check “Initialize this repository with a README”.</p>
    <p>Finally, click the button that says “Create repository.”</p>
  </li>
  <li>
    <p>You’ve just intialized a Git repository! Nice. Now we need to copy it to our computers.</p>
  </li>
</ol>

###Creating a Home For Our Repositories
Some of this might seem kind of fussy, but since we’ll be doing a lot of debugging on everyone’s machines, I want to make sure we’re all working the same way. So, first let’s create a home folder for all our class repositories.

<ol class="steps">
  <li>
    <p>Go to your home directory, it’s the one in your sidebar with a house icon. Mine is called “shan” and the keyboard shortcut to go there is: ⌘⇧H</p>
  </li>
  <li>
    <p>Inside this folder, create a new folder called “dataviz-fall-2013”. This is where we’re going to store all of our repositories.</p>
    <p><img src="starting-folder.png"></p>
  </li>
</ol>


###Installing Github on Your Computer
Now you’ll need the Github application on your computer so you can edit and sync your projects.
<ol class="steps">
  <li>
    <p>Download and install the Github application. <a href="http://mac.github.com/">Mac</a> or <a href="http://windows.github.com/">Windows</a>.</p>
    <p><a href="http:mac.github.com"><img src="github-download.png"></a></p>
  <p>(If you get stuck in the future, there are good help pages for <a href="http://mac.github.com/help.html">Mac</a> and <a href="http://windows.github.com/help.html">Windows</a>.)</p>
  </li>
  <li>
    <p>After installing, when you first launch the application it will ask you to move it to the Applications folder. Say “yes”.</p>
  </li>
  <li>
    <p>When it re-launches, it’ll step you through a setup process. You’ll need to enter your shiny new Github credentials, you’ll want the command-line tools, but you don’t need to “add local repositories”.</p>
  </li>
  <li>
    <p>You should now see a window that lists one repository: “dataviz-home”. Click the button next to it that says “Clone to Computer”.</p>
    <p><img src="list-of-repos.png"></p>
  </li>
  <li>
    <p>A dialog window will popup. Navigate to your “dataviz-fall-2013” folder in your home directory. Click “Clone”.</p>
    <p><img src="save-to-home.png"></p></li>
  <li>
    <p>Click on the little arrow next to your repo name and you now can see the whole edit history for that repo. You should only have one entry, and it’ll be called “Initial Commit”.</p>
    <p><img src="first-commit.png"></p>
  </li>
  <li>
    <p>Now, go back to the Finder and find your home directory. There should be a folder within “dataviz-fall-2013” called “dataviz-home”, with one file inside of it.</p>
    <p><img src="dataviz-home.png"></p>
  </li>
  <li><p>Great, you should be all setup to make your first edit in your new repo, but first we need to take a short detour for a good text editor.</p></li>
</ol>

###Installing Sublime Text
If you already have a text editor you like, feel free to skip this section. If not, then it’s probably best you install <a href="http://www.sublimetext.com/">Sublime Text</a>.
<ol class="steps">
  <li>
    <p>Download and install <a href="http://www.sublimetext.com/">Sublime Text</a>.</p>
    <p><a href="http://www.sublimetext.com/"><img src="sublime-text.png"></a></p>
  </li>
  <li>
    <p>To make the most of Sublime, we’re also going to install a package manager for it (packages are like extensions that add features). Follow the “Manual” directions for the <a href="https://sublime.wbond.net/installation#Manual">Sublime Package Manager</a>.</p>
    <p><a href="https://sublime.wbond.net/installation#Manual"><img src="sublime-package-manager.png"></a></p>
  </li>
  <li>
    <p>Once installed, here are some <a href="https://sublime.wbond.net/docs/usage">instructions</a> for how to install and remove packages.</p>
    <p>The basic pattern is: You open a window in sublime, hit ⌘⇧P, then type “install” and choose “Package Control: Install Package”.</p>
    <p><img src="sublime-install-package.png"></p>
    <p>Next, type in the name of the package and hit return — “Soda” in this instance.</p>
    <p><img src="sublime-soda.png"></p>
  </li>
  <li>
    <p>I recommend not installing too many packages, as it’s best not to gunk up sublime with too many of these, but you can browse them all <a href="https://sublime.wbond.net/">here</a> if you’re curious. Go ahead and install these three: <a href="https://sublime.wbond.net/packages/Theme%20-%20Soda">Theme - Soda</a>, <a href="https://sublime.wbond.net/packages/SideBarEnhancements">SideBarEnhancements</a> and <a href="https://sublime.wbond.net/packages/ColorPicker">ColorPicker</a>; </p>
  </li>
</ol>

###Finally, Making Something
Let’s try to put it all together and actually add something to our repo.
<ol class="steps">
  <li>
    <p>Open up our project folder “dataviz-home” in Sublime Text. You can do this one of two ways: 1. Go to File > Open and choose the “dataviz-home” folder. 2. Drag the “dataviz-home” folder onto the Sublime Text application icon in the dock. Either way you should end up with this:</p>
    <p><img src="dataviz-home-sublime.png"></p>
  </li>
  <li>
    <p>Now, create a new file. The easiest way is to right-click on the folder named “dataviz-home” in the sidebar.</p>
    <p><img src="new-file.png"></p>
    <p>A small text field will open at the bottom of screen. Type in “index.html” and hit return.</p>
    <p><img src="new-file-name.png"></p>
    <p>This is what you should end up with in the end:</p>
    <p><img src="new-file-success.png"></p>
  </li>
  <li>
    <p>Enter in some HTML. To get started, here is the bare minimum:</p>
    <p><img src="html.png"></p>
  </li>
  <li>
    <p>Now we need to save those changes back up to Github servers. First, go to the Github app and click on the changes tab. You should see all your changes listed there.</p>
    <p><img src="github-changes.png"></p>
  </li>
  <li>
    <p>In Git, you bundle changes together into a “commit” which requires a short description. I’ve typed in “Added index page”. We also want to click the button with a plus and rotating arrows to mark that we want to automatically sync with Github servers each time we make a commit. Finally, push the button that says “Commit & Sync” to make your commit and sync it to the Github servers.</p>
    <p><img src="github-commit-sync.png"></p>
  </li>
  <li>
    <p>Now click over to the "History" tab and you should see two commits listed. You can click back and forth on the commits to see what changes were made.</p>
    <p><img src="github-successful-commit.png"></p>
  </li>
  <li>
    <p>Let’s see what it looks like on the Github website. Click on the settings tab, then click the button that says “View on Github”.</p>
    <p><img src="github-settings-tab.png"></p>
  </li>
  <li>
    <p>Now you should see a version of your project live on Github servers. You can even edit your files through this website! For example, let’s add some text our homepage. Click on the “index.html” page.</p>
    <p><img src="github-homescreen.png"></p>
  </li>
  <li>
    <p>Now, click the “Edit” button.</p>
    <p><img src="github-edit.png"></p>
  </li>
  <li>
    <p>Once you’ve added a line or two of text, scroll down to the bottom and click the “Commit Changes” button.</p>
    <p><img src="github-commit-changes.png"></p>
  </li>
  <li>
    <p>Now, we need to sync those changes back to our computer. So let’s go back to the Github app and click on the “History” tab. Click the button on top labeled “Sync Branch”.</p>
    <p><img src="github-sync-branch.png"></p>
    <p>You should see a new entry in your commit history, and if you open the file up in Sublime, you should see the changes you made through the website.</p>
  </li>
</ol>

<h3 id="gh-pages-publish">Now, Let’s Publish</h3>
When we started we promised that we’d be able to publish something to the internet for free. Well, when we viewed the “index.html” file on Github, it didn’t exactly look like how it would if you were sharing a link with someone. We’ll fix that now.
<ol class="steps">
  <li>
    <p>The last major concept in Git we need to cover is “Branches”. Click on the “Braches” tab for your “dataviz-home” repo.</p>
    <p><img src="github-branches.png"></p>
  </li>
  <li>
    <p>Click the plus button to create a new branch based on the existing branch and name it “gh-pages”.</p>
    <p><img src="github-branches-add.png"></p>
  </li>
  <li>
    <p>Then click “Publish” to create it on the Github servers.</p>
    <p><img src="github-branches-publish.png"></p>
  </li>
  <li>
    <p>This branch has a special name “gh-pages” which is short for for “GitHub Pages” and tells github that this branch is meant to be served as webpages and not code. The URLs for these Github pages follow a formula: <a href="http://[your-user-name].github.io/[your-repo-name]">http://[your-user-name].github.io/[your-repo-name]</a>. For instance, mine is available at: <a href="http://shancarter.github.io/dataviz-home/">http://shancarter.github.io/dataviz-home/</a>. Go to your URL and see if it shows up. It can sometimes take a few minutes to be live. Read up more on <a href="http://pages.github.com/">Github Pages</a>.</p>
  </li>
  <li>
    <p>Let’s make an edit to our page and publish the changes.</p>
  </li>
  <li>
    <p>Then, go back to the Github app, the “Changes” tab and commit and sync that change.</p>
  </li>
  <li>
    <p>Refresh your <a href="http://shancarter.github.io/dataviz-home/">http://shancarter.github.io/dataviz-home/</a> url and see if it shows up.</p>
  </li>
  <li>
    <p>Now that we have it all setup, that is the cycle for publishing changes to your project: Edit files, then “Commit & Sync”. That’s it, all those edits will then be live on your page.</p>
  </li>
  <li>
    <p>We have one last small thing to do, and that’s to set “gh-pages” to be our default branch so we don’t get confused. Unfortunately we can only do this through the Github website. The setting is located in your repos “Settings” screen.</p>
    <p><img src="github-settings-page.png"></p>
    <p>Set the default branch from “master” to “gh-pages”.</p>
    <p><img src="github-default-branch.png"></p>
  </li>
  <li>
    <p>And finally, if you ever need to get back to the original screen where it lists all your repos, click the top bar where it says “Repositories >”.</p>
    <p><img src="github-back-to-home.png"></p>

  </li>
  <li>
    <p>So far this has just scratched the surface of Git and Github. If you want to go deep, here’s a <a href="http://git-scm.com/book">very detailed overview</a>.</p>
  </li>

</ol>

###Installing R Studio
<ol class="steps">
  <li><p>Download and install <a href="http://cran.us.r-project.org/">R</a>.</p></li>
  <li><p>Download and install <a href="http://www.rstudio.com/">RStudio</a>.</p></li>
  <li>
    <p>Open RStudio and type into the console:</p>
    <p><code>demo(graphics)</code></p>
    <p><img src="rstudio.png"></p>
  </li>
  <li><p>Congratulations, you just earned a Master’s in statistics!</p></li>
</ol>

