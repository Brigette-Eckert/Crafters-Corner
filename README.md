
#About

Crafting blog for people who like to make stuff. Built with Drupal 7 as part of self study following Epicodus curriculum. (Based on reciepe blog requirements and used to learn about Deploying to Panethon).  

# Instructions:

1. Download Drupal version 7.51

2. Replace the sites folder with the enclosed sites folder

3. Import the Database Dump

  a. Open phpMyAdmin and click on the "Import" tab.

  b. Leave all the default settings and make sure the character set is "utf-8"

  c. Now click on the "Choose File" button next to "Browse your computer" and select the .sql.zip file we included in our sites/db-backup folder. It's okay to leave it zipped.

  d. Then click the "Go" button on the bottom left.

4. Create the Database User (not needed if using Acquia Dev Desktop)

  a. Lastly, we must recreate the database username/password that Drupal uses to store things in the database. We do this the same way we did when we created the database.

  b. After importing the .sql.zip file, select the "Privileges" tab and click on "Add User".

  c. Use the same username and password from before. (If we have forgotten what that was, we can always find that information in settings.php, or in the PDO Exception error message we saw displayed in the browser.)

  d. After importing the database, if you have any trouble logging in with your Site Maintenance account, clear your browser's cookies by clearing the browser history.



# User Stories

1. As an anoymous user I can view tutorials, tips & tricks and the static pages. 

2. As an authenicated user I can post comments.  

3. As a instructor I can create new tutorials. 


####Surpise Me Module 

1. As an anoymous user I can click on a "surpise me" link on the navagation and be taken to a random tutorial. 

#To Do




#Project Instructions

1. Include the following Static Pages: 

  A. A standard "Contact" form

  B. About Me. 

  C. Page for users to introduce themselves with comments

  D. An FAQ Page 


2. Include the following Content Types: 
  
  A. News (regular blog posts)

  B. Tips and Tricks

  C. Craft Tutorials


# What I learned from this project

1. Learned how to use Panethon to deploy drupal sites


