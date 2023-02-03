# The Gym

[View the live project here.](#)

This is the main website for 'The Gym'. It is designed to be responsive and accessible on a range of devices, making it easy to navigate for potential customers.

## User Experience (UX)

-   ### User stories

    -   #### First-Time Visitor Goals

        1. As a First Time Visitor, I want to be met with a simple clean home page that highlights that it is a website for a gym.
        2. As a First Time Visitor, I want the most important pages to be visible upon first glance when looking at the navigation bar. I want to be able to easily navigate throughout the website to find information.
        3. As a First Time Visitor, I want to be able to find the contact information easily to solve any queries that I might have, or has not been answered on the site.

    -   #### Returning Visitor Goals

        1. As a Returning Visitor, I want to find information about the pricing, opening hours and classes.
        2. As a Returning Visitor, I want to find the location of the gym.

    -   #### Frequent User Goals
        1. As a Frequent User, I want to check to see if there are any discounts or new plans/pricing.
        2. As a Frequent User, I want to check to see if there are any new classes.           

-   ### Design
    -   #### Colour Scheme
        -   The two main colours used are #1791b1 - a shade of blue, and white. Originally I thought of having 3 main colours including a shade of pink or dark blue but decided against it as it would be overwhelming and too busy.
    -   #### Typography
        -   The Robot font is the main font used throughout the whole website with Sans Serif as the fallback font in case the choice of font doesn't get imported into the site correctly. Roboto is a clean font that I have seen being used throughout my course hence why I chose it.
    -   #### Imagery
        -   Imagery is important. The large, background hero image is designed to  catch the user's attention and set the tone for the page. It shows a clean and modern looking gym, conincing customers to join.

*   ### Wireframes

- Balsamiq expired at the end of 2022 and wouldn't let me use it. I ended up just following the layout of the love running and bootstrap whiskey drop project. In the future I would definitely use a wireframe or at least draw it out.

## Features

-   Responsive on all device sizes

-   Hover effects when hovering over the links in the navbar, 'join now' button, 'strength & conditioning', 'pilates' and 'cycle' text box, the images of the trainers, the 'basic', 'plus' and 'vip' pricing boxes and 'contact us now' button.

-   Social media icons in the footer link to Instagram, Facebook and Twitter. I didn't link them to a specific account since this is a fake website and there is no account but I tried to show that if there was an account for the company then it would link to their social pages.

-   Icons from Font Awesome

-   A map with the fake location in the Contact us page.

-   A form on the contact us now page where queries can be sent.


## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries & Programs Used

1. [Bootstrap 4.4.1:](https://getbootstrap.com/docs/4.4/getting-started/introduction/)
    - Bootstrap was used to assist with the responsiveness and styling of the website.
1. [Google Fonts:](https://fonts.google.com/)
    - Google fonts was used to import the 'Roboto' font into the style.css file which is used on all pages throughout the project.
1. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
1. [jQuery:](https://jquery.com/)
    - jQuery came with Bootstrap to make the navbar responsive but was also used for the smooth scroll function in JavaScript.
1. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project, a few errors in the HTML parts and none in the CSS.

-   [W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) 
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) 

### Testing User Stories from User Experience (UX) Section

-   #### First Time Visitor Goals

    1. As a First Time Visitor, I want to be met with a simple clean home page which highlights that it is a website for a gym.

        1. Upon entering the site, users are automatically greeted with a clean and easily readable navigation bar to go to the page of their choice. Underneath there is a Hero Image with Text that highlights that the gym is open 24/7 and a "Join Now" Call to action button that leads to the contact us now page.
        2. The user has two options, click the call to action button or scroll down to learn more about the gym.

    2.   As a First Time Visitor, I want the most important pages to be visible upon first glance when looking at the navigation bar. I want to be able to easily navigate throughout the website to find information.

        1. At the top of each page there is a navigation bar, each link simply describes the page they will end up at.
        2. The prices and other information can be accessed on the home page by scrolling.

    3.  As a First Time visitor, I want to be able to find the contact information easily to solve any queries that I might have, or has not been answered on the site.

        1. The contact us page link can be seen clearly in the navigation bar on each page 
        2. A from conatining a message box can be used for queries on the contact us page.
        3. At the bottom of the page there are social media icons which direct to the companies social pages where they can also be contacted.
        

-   #### Returning Visitor Goals

    1. As a Returning Visitor, I want to find information about the pricing, opening hours and classes.

        1. The pricing can be found through scrolling down on the home page and is under the clear heading 'Pricing'.
        2. Information on the classes can be found by scrolling down on the home page under the heading 'classes' where a little insight is given. More information on the classes can be found on the classes page which is in the navbar. 
        3. Opening hours are 24/7 which can be seen first thing on the home page on the hero image. If this were to be missed by the user they can contact the company through various means on the contact us page. 
    
    2. As a Returning Visitor, I want to find the location of the gym.

        1. On the contact us page, there is a reasonably sized map with the address of the gym and a little pinpoint on the map which also shows the location.


-   #### Frequent User Goals    

    1.  As a Frequent User, I want to check to see if there are any discounts or new plans/pricing.

        1. This can be checked easily by scrolling down on the home page. In hindsight, I will be looking to add an alert banner or a newsletter option to make it easier for customers to be notified of discounts.

    
     2. As a Frequent User, I want to check to see if there are any new classes.
        
        1. New classes can be checked in the classes page that can be found in the navbar. I do think a newsletter would be more convenient and will probably be something that I do after the end of the course when I have more time.

### Further Testing

- Lighthouse test was run, performace - 82, accessibilty - 86, best practices - 75, seo - 90.
- Was also tested on Google chrome, internet explorer and different device sizes through devtools.
- I have had my family test the site and they found it easy to use.


### Known Bugs

- A tiny white gap on the right hand side was found when opened in internet explorer on iphone xr.
- The navigation bar on smaller screen sizes. I really struggled to make a responsive navigation menu for small screen sizes using code from the bootstrap library that I has used in a previous project below 
 <!-- <button class="navbar-toggler ml-auto" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" 
                aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span></button>-->
- I was unable to get the menu styled the way I wanted to and it wouldn't display on all devices. This was one of my biggest struggles. I tried code from W3schools for the nav menu on smaller screen sizes and couldn't get the menu to open and close. 
- I then referred to Easy Tutorials on Youtube and used code from there instead which I have put below and in the credits section. I then had trouble styling the nav again and getting it to open and close and it took me almost until the end of the project to realise tht i used .nav instead of nav in the css.
<!--    <i class="fa fa-times" onclick="hideMenu()"></i>
        <ul class="menu">
        <i class="fa fa-bars" onclick="showMenu()"></i>

        <script>
        var navLinks = document.getElementById("navLinks");

        function showMenu() {
            navLinks.style.left = "0"
        }

        function hideMenu() {
            navLinks.style.left = "-200px"
        }
    </script> -->
- After submitting a message on the contact us now page form an error shows up because I haven't linked it to where the forms are meant to be sent.    



## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps;

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/Taneemkibria/The-Gym)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
3. Scroll down the Settings page until you locate the "Pages" Section on the left hand side.
4. Under "Source", click the dropdown called "None" and select "Main".
5. The page will automatically refresh.
6. Scroll up to the page to locate the now published site [link](https://taneemkibria.github.io/The-Gym/) in the "GitHub Pages" section.

## Credits

### Code
- <i class="fa fa-times" onclick="hideMenu()"></i>
        <ul class="menu">
        <i class="fa fa-bars" onclick="showMenu()"></i>
        
        <script>
        var navLinks = document.getElementById("navLinks");

        function showMenu() {
            navLinks.style.left = "0"
        }

        function hideMenu() {
            navLinks.style.left = "-200px"
        }
    </script> 
      .nav-links {
        position: absolute;
        height: 100vh;
        width: 200px;
        top: 0;
        right: -200px;
        text-align: left;
        z-index: 2;
    }
- The code above is credited to Easy Tutorials on Youtube (https://youtu.be/oYRda7UtuhA)




### Media

- All Images were downloaded from Pexels.com
- Photo by Leon Ardho from Pexels: https://www.pexels.com/photo/man-and-woman-holding-battle-ropes-1552242/
- Photo by Max Vakhtbovych from Pexels: https://www.pexels.com/photo/various-fitness-machines-in-modern-spacious-gym-7031706/
- Photo by Victor Freitas from Pexels: https://www.pexels.com/photo/person-holding-barbell-841130/
- Photo by Pixabay from Pexels: https://www.pexels.com/photo/woman-doing-exercise-414029/
- Photo by Leon Ardho from Pexels: https://www.pexels.com/photo/woman-lifting-barbell-1552249/
- Photo by Jonathan Borba from Pexels: https://www.pexels.com/photo/woman-kneeling-with-barbel-on-shoulders-3076514/
- Photo by Tima Miroshnichenko from Pexels: https://www.pexels.com/photo/a-woman-in-black-tank-top-sitting-on-an-air-bike-6389499/
- Photo by Nicholas Fu from Pexels: https://www.pexels.com/photo/fitness-instructor-assisting-woman-doing-pilates-9288101/
- Photo by Pikx By Panther from Pexels: https://www.pexels.com/photo/photo-of-man-with-muscular-body-1547248/
- Photo by cottonbro studio from Pexels: https://www.pexels.com/photo/woman-in-black-sportswear-lifting-a-barbell-7674493/
- Photo by cottonbro studio from Pexels: https://www.pexels.com/photo/woman-in-red-sports-bra-and-green-shorts-sitting-on-purple-carpet-4325484/
- Photo by Sahil Khaliq from Pexels: https://www.pexels.com/photo/a-topless-man-showing-his-physique-10929340/
- Photo by Anastasia  Shuraeva from Pexels: https://www.pexels.com/photo/photo-of-a-woman-lifting-a-kettlebell-4945521/
- Photo by Sabel Blanco from Pexels: https://www.pexels.com/photo/photo-woman-bodybuilder-using-cable-and-pulley-machine-while-facing-mirror-1480520/
- All icons from  Font awesome (fontawesome.com)


### Acknowledgements

- A huge shoutout to Easy Tutorials on Youtube for helping me fix the problem with my nav bar on smaller screen sizes!


    


