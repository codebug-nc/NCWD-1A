## DREAM VACATION WEBSITE!

## Your mission is create a webpage for your dream vacation, but first...
1. Find a spot where you would like to vacation 
1. Open the `NCWD-1A` in Sublime, and look inside the `index.html` file.
1. Add the base HTML to your empty `index.html` file:
        
          <!DOCTYPE html>     
          <html>
             <head>
               <title></title>
             </head>
             <body>
               <!-- write your HTML code here -->
             </body>
          </html>
        
1. Add the same base HTML code to the `application.html` file.

### Now let's add some HTML elements

#### `index.html`
* Add a heading with the name of your destination. This heading will be the most important set of words on your page so it would make sense to use an `<h1>` heading.
* Save your `index.html` file in Sublime
* In the terminal from `NCWD-1A` type `open index.html` to open this file in Chrome and see your heading!
* Add a paragraph explaining some attraction and/or fun facts about your destination. 
* Add a picture of the destination - or many pictures if you'd like! 
    * Are your images the wrong size? You can change the height and width of your `<img>` tag! Check out this [link](https://www.w3schools.com/tags/att_img_width.asp)
* Add an unordered list of some sort (local attractions, animals in the area...).
* Add an ordered list (best restaurants, best hotels, best beaches).
* Add some links to 3 similar destinations to suggest to your visitors. *HINT: you'll be using an `<a>` tag check out this [link](https://www.w3schools.com/html/html_links.asp)

#### `application.html`
* Now in the `application.html` file we are going to create an application for your friend(s) to "apply" to go on this trip with you!
* Open `application.html` in Sublime.
* Add a heading to your `application.html` that says something like "Apply to vacation with me!"
* Save your `application.html` file in Sublime.
* Open `application.html` in Chrome to make sure your header worked!
* Now let's add a "Link to Apply" that links to this `application.html` from your home page (`index.html`). You will need to use an `<a>` tag on the `index.html` page. It will look something like this: 
                `<a href="application.html">Apply!</a>`
* In `application.html`add a couple more HTML elements:
    * Add a paragraph tag that explains the purpose of this application.
    * Create a form like the one below with a "date" input type: 

                <form>
                  <input type="date"><br>
                </form>
                
    * Refresh your page in Chrome and see what a "date" input type does. If you're wondering what the `<br>` tag does, it just creates a line break so all of your form inputs are on different lines. If you want them on the same line, remove the `<br>`!
    * Explore the different `<input>` types that can be used in a form. Here's a [good list of the different input types](https://www.w3schools.com/html/html_form_input_types.asp).
    * Add at least 4 different input types to your application form. Get creative! What qualities are you looking for in a travel buddy?

 
#### EXTENSION

* Use an `<iframe>` to add a video to your site. Here's a [great link](https://www.w3schools.com/html/html_youtube.asp) with some added features for YouTube videos.
* Add a `<table>` of expenses summarizing how much this trip would cost. (You can make these up if you would like to! A luxurious trip to Paris for $5.00 :)) 
> *Check out this image if you need inspiration* ![table](/table-image.png) 
* Begin styling your website!
    * Note: You'll need to create a `style.css` page for your CSS styling.
    * Once you've created `style.css` you need to link your CSS file to our HTML file. If you've forgotten how to do that, check out this [link](https://teamtreehouse.com/community/htmlcss-linking).



