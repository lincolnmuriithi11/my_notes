# My DS Notes

This is a repository for my notes
MAKE A HELLO_WORLD REPOSITORY AND ORIENT YOURSELF
Using the directions above, create a repository on GitHub called Hello_World.

cd ~/codeup-data-science and then clone your repo here.

cd ~/codeup-data-science/Hello_World

Orienting yourself with your new repository and its parent folder

Type git status. What do you see? Does this make sense?

Type ls -l. What do you see? Does this make sense? Why/why not?
Type ls -la. What do you see? Does this make sense? Why/why not?
Type cd .. to navigate to the parent folder
From the parent folder, type pwd. What is your current working directory?
Run ls -la. What do you see?
Run git status. What output do you see? Does this make sense or not?
Return to ~/codeup-data-science/Hello_World (remember the cd command). Type pwd to confirm.

Do work:

Create a file named hello.txt inside of your ~/codeup-data-science/Hello_World repo.

The hello.txt file should have text that says "Hello, World!" on the first line. Save the file.
Now type git status from your terminal. What do you see?
Type ls -la. What do you see here?

Adding files to git

Now it's time to tell Git about your new file. Type git add hello.txt

Run git status. Read the output carefully and think about what changed.

Commiting files

Now it's time to commit your work. Type git commit -m "added hello.txt"

Now, type git status to see what changed.

Push your work to GitHub

Type git push and pay careful attention to the output messages.

Go back to your browser and refresh the page for your repository

Congratulations! You've made a repository, done work, added, commited, and pushed to GitHub!

ADDING TO FILES IN YOUR HELLO_WORLD REPOSITORY
From your Hello_World repository on your laptop, open hello.txt
On the second line, add a new line of text that says "Now I'm adding a second line of content" and save.
From the terminal type git status. What do you see? What changed?
Exploring new additions/changes with git diff
Now that you've added new content, run git diff.
We can run git diff hello.txt or for other specific filenames
We can also run git diff to see all differences in any changed files.
Back in your editor, add a 3rd line of text to hello.txt that says "Adding a 3rd line of text"
Return to your terminal and type git diff, reviewing the feedback.
Add, commit, and push your work:
Add your new work with git add hello.txt
Commit with git commit -m "added 2 example lines of text"
Now push to GitHub with git push
Review the changes on your Hello_World repo page on GitHub.
