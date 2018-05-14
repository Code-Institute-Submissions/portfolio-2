
#### Stream One Project

Stephen Moody

Submittion for Project 1 for Code Institute

Live Project Available [here](https://smoody.herokuapp.com) or at:

https://smoody.herokuapp.com

Git-Hub Available [here](https://github.com/DarilliGames/portfolio) or at:

https://github.com/DarilliGames/portfolio


A simple single paged porfolio project using just the basics of web development, HTML, CSS and JavaScript.  To make the simple project feel more "alive", additional JavaScript is used to display some of the skills learned during Stream One.

#### JavaScript Use

##### Typing

The typing runs Though a number of For-Loops to achieve the desired results.  First, it get a string from an array and then through another For-Loop over each letter in the selected String.  It then appends the first letter and then removes it from the string.  Once the word is complete (the string is empty), it deletes each letter and begins again at the next string in the array.

##### Resizing Images

JavaScript also allows us to resize the images on the website.  The images for examle are resized depending on the Screen Size, to make the website Mobile friendly and responsive when shrunk, CSS is also used to make the images sit from Side-by-Side to Top-top-Bottom

The responsive behaviour is carried out via a script that runs when the webpage is open and through a listener that is called on screen resizing.

    
    window.onresize = setEqualHeight;
    
#### CSS Use

##### Cursor

Part of the typing effect previously mentioned is the "Cursor".  The cursor will blink every second to achieve the "typing effect".

##### Responsive Without Bootstrap

While Bootstrap is a powerful tool - it is just CSS and JavaScript.  The simple design of this website means that such a powerful tool is not required.

#### Difficulties Found

#####  Heroku JavaScript Loading

The JavaScript used on this website is on the HTML Page, this is due to a bug I have experienced with Heroku, where the "Typing" section of the page fails to trigger.  I have found that  this is avoided when the script is on the HTML Page.

#####  Project Reset

Originally the project was going to the based using AngularJS but unfortunatly during development I did have to restart this project.  With Higher marks going for my other projects, I believed that time spent on them would achieve myself a better grade.

For this reason I decieded to make a simple Portfolio Website, something which I had in mind to build for sometime.  My decision to avoid using BootStrap was a combination of the fact that I have used it in my other two projects and to demonstrate that a similar and responsive effect can be made simply.


##### Running On Heroku

Notably, Heroku does not allow single pages to be uploaded.  To counter this, "index.php" is a simple way around this. All that is required to run the page is the following.

    <?php header( 'Location: /index.html' ) ; ?>
    
Unfortunately, this does change the URL a minor defect -
    
[smoody.herokuapp.com](smoody.herokuapp.com) opens as [smoody.herokuapp.com/index.html](smoody.herokuapp.com/index.html)

As of yet, I have not found a way around this.