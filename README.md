
#About

Crafting blog for people who like to make stuff. Built with Drupal 7 as part of self study following Epicodus curriculum. (Based on recipe blog requirements and used to learn about Deploying to Panethon).  


# User Stories

1. As an anonymous user I can view tutorials, tips & tricks and the static pages.

2. As an apprentice I can post comments, edit and delete my own comments, review tutorials and skip comment approval.  

3. As a artisan I can create new tutorials.

4. As an authenticated user I can add social media links, including raverly and pintrest to my user page



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

4.  Create a simplified contact module.

  A. Hide the subject line and the send yourself a copy checkbox, on the contact form.

  B. Set default values for the two hidden fields. The default subject should be "Feedback" and the send yourself a copy checkbox should be set to a default value of 1 (checked.)

5. Alter the Follow Module

  A. Alter the follow module to include relevant sites


6. Make a simplified content type module to do the following:

  A. Hide all of the extra menu tabs on each of your custom content types that you don't want Jamie to use.

  B. Make your custom support module set the default value for comments to be off.


7. Include views for content

8. Create Entity Reference Fields

    A. Allow artisans and tutorials to have many to many relationships
    
    B. Create view of all artisians that link to tutorials 
    
   C. Include links to view of all tutorials by artisian on profile


9. Make a module called surprise me

  A. Create a custom module which creates a "Surprise Me!" link in the Navigation menu. When clicked, it should redirect the user to a random node of the content of a random craft tutorial.


#To Do

Hide non relevant social media links in follow alter module

Fix follow so only shows up on user page that opts in and isn't the same for everyone

Alter entity reference module to only display on user profile if user has role of artisian

Hide simple contact module if logged in as admin

Link tutorials on user page and artisians on tutorials refrence eninity to adding one with auto populate the other

Index site with Cron and add search view



# What I learned from this project

1. Learned how to use Panethon to deploy drupal sites

2. Learned how to alter existing modules using the alter hook

3. Learned about using DB queries with DB_Select in modules

4. Learned about the Reference Entity Module

5. Practiced using more complex views 

