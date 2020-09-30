<!-- 
    1. No returning visitor or frequent visitor
    2. User Stories, work back from each section on site to define them
    3. Test -> involve each link (Navbar example)
    4. "integrity crossorigin" meta tag part remove
    5. Tidy up code and remove unecessary comments
    6. Add comments to seperate sections html and css
    7. Rename to milestone_project_1 
-->

<h1 align="center">Milestone Project 1 - HYKR</h1>

[View the live project here.](https://iainmchugh.github.io/ms1/)

HYKR is a mock homepage for a hiking clothing brand. It also acts as a simple e-Commerce shop for the clothing brand, which users have immediate access to via the homepage. The site aims to create a modern and high quality feel for the clothing brand through use of dynamic content and responsive layouts. 

![Cover Photo](https://github.com/IainMcHugh/ms1/blob/master/assets/images/readme-cover-img.PNG?raw=true)

## User Experience (UX)

-   ### User stories

    -   #### Site Visitor Goals

        1. As a site Visitor, I want to understand the purpose and nature of this particular brand via their website.
        2. As a site Visitor, I want to get an idea of what sort of products are available on this website.
        3. As a site Visitor, I want a seemless experience that keeps my attention throughout the entirety of the website via appropriate visual cues and clearly divided sections.
        4. As a site Visitor, I want to easily navigate to the section of the site I am interested in returning to.
        5. As a site Visitor, I want a clear and concise contact section, that provides all of the necessary information for me to contact the site owners.

-   ### Design
    -   #### Colour Scheme
        -   The two main colours used are #ED8FEF and #8DD6FF. I chose these colours in particular as I find with a linear gradient they capture an early morning sky, something that avid hikers are familiar with as arduous hiking will often involve starting very early in the morning. I also came across <a href="https://en.wikipedia.org/wiki/Electric_blue_(color)">Electric Blue</a> after noticing a similar shade of striking blue on various sites, and have used that as a reference for some of the other blue shades incoroprated into the site.
    -   #### Typography
        -   The Poppins font is the main font used throughout the whole website with Sans Serif as the fallback font in case for any reason the font isn't being imported into the site correctly. Poppins is both an easily readable font as well as bubbly font that I find very effective at drawing the users eye. It also gives a high quality feel to the overall site.
        <a href="https://fonts.google.com/specimen/Poppins">Poppins</a> - Google Fonts
    -   #### Imagery
        -   Imagery on the site is broken into two groups. There are cartoon images used in both the home and overview section. In the shop section, there are sample product images. I felt that cartoon images helped to keep a seemless feeling to the site, as well as ultamitely give a pop to the actual shop items when the user scrolls to this section. I also designed a simple logo in photoshop in keeping with the colour scheme and overall design of the site. Lastly, I have implemented css clip-paths to transform section breaks into visual imagery, as these slight slants tie in with the theme of hiking while not being too dramatic as to solidify there primary purpose as visual section breaks.
    -   ### Animation
        - There are three seperate animations within the site. On initial page load there is a css animation for the mountain jutting out of the homepage. I think this rising effect fits well within the theme of the site and also provides dynamics to the site, making the user feel they are dealing with a high quality product. There is also a very slow cloud moving horizontally behind the mountain. Again this adds to the dynamic feel of the site, while also being sufficiently opaque and slow as to not unnecessarily distract the user.

*   ### Wireframes

    -   Figma Wireframe - [View](https://www.figma.com/file/QnfsdsjYig0fVDAhb79AH5/HYKR?node-id=0%3A1)
    -   Note: The Wireframe was something I used primarly as a method to get my initial concept ideas down as well as general page layouts and colour schemes. Originally my aim was to create a sample Hiking blog site however throughout development I felt the idea would pan out better as a mock clothing brand site. I did create mockups for each section of the altered design on a whiteboard:

    ![Cover Photo](https://github.com/IainMcHugh/ms1/blob/master/assets/images/readme-cover-img.PNG?raw=true)

    ![Cover Photo](https://github.com/IainMcHugh/ms1/blob/master/assets/images/readme-cover-img.PNG?raw=true)

    ![Cover Photo](https://github.com/IainMcHugh/ms1/blob/master/assets/images/readme-cover-img.PNG?raw=true)

    ![Cover Photo](https://github.com/IainMcHugh/ms1/blob/master/assets/images/readme-cover-img.PNG?raw=true)

## Features

-   Responsive on all device sizes

-   Interactive elements

## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries & Programs Used

1. [Bootstrap 4.4.1:](https://getbootstrap.com/docs/4.4/getting-started/introduction/)
    - Bootstrap was used to assist with the responsiveness and styling of the website.
2. [Hover.css:](https://ianlunn.github.io/Hover/)
    - Hover.css was used on the Social Media icons in the footer to add the float transition while being hovered over.
3. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Titillium Web' font into the style.css file which is used on all pages throughout the project.
4. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
5. [jQuery:](https://jquery.com/)
    - jQuery came with Bootstrap to make the navbar responsive but was also used for the smooth scroll function in JavaScript.
6. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.
7. [Photoshop:](https://www.adobe.com/ie/products/photoshop.html)
    - Photoshop was used to create the logo, resizing images and editing photos for the website.
8. [Figma:](https://figma.com/)
    - Figma was used to create the [wireframes](https://github.com/) during the design process.
9. [Visual Studio Code:](https://visualstudio.com/)
    -  VSCode was the IDE I used to create, update, and maintain this project. 

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

-   [W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results](https://github.com/)
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results](https://github.com/)

### Testing User Stories from User Experience (UX) Section

-   #### First Time Visitor Goals

    1. As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the organisation.

        1. Upon entering the site, users are automatically greeted with a clean and easily readable navigation bar to go to the page of their choice. Underneath there is a Hero Image with Text and a "Learn More" Call to action button.
        2. The main points are made immediately with the hero image
        3. The user has two options, click the call to action buttons or scroll down, both of which will lead to the same place, to learn more about the organisation.

    2. As a First Time Visitor, I want to be able to easily be able to navigate throughout the site to find content.

        1. The site has been designed to be fluid and never to entrap the user. At the top of each page there is a clean navigation bar, each link describes what the page they will end up at clearly.
        2. At the bottom of the first 3 pages there is a redirection call to action to ensure the user always has somewhere to go and doesn't feel trapped as they get to the bottom of the page.
        3. On the Contact Us Page, after a form response is submitted, the page refreshes and the user is brought to the top of the page where the navigation bar is.

    3. As a First Time Visitor, I want to look for testimonials to understand what their users think of them and see if they are trusted. I also want to locate their social media links to see their following on social media to determine how trusted and known they are.
        1. Once the new visitor has read the About Us and What We Do text, they will notice the Why We are Loved So Much section.
        2. The user can also scroll to the bottom of any page on the site to locate social media links in the footer.
        3. At the bottom of the Contact Us page, the user is told underneath the form, that alternatively they can contact the organisation on social media which highlights the links to them.

### Further Testing

-   The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge and Safari browsers.
-   The website was viewed on a variety of devices such as Desktop, Laptop, iPhone7, iPhone 8 & iPhoneX.
-   A large amount of testing was done to ensure that all pages were linking correctly.
-   Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

### Known Bugs

-   Form size, white bar above footer

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
    - Alternatively Click [Here](https://raw.githubusercontent.com/) for a GIF demonstrating the process starting from Step 2.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://github.com) in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.

## Credits

### Code

-   The full-screen hero image code came from this [StackOverflow post](https://stackoverflow.com)

-   [Bootstrap4](https://getbootstrap.com/docs/4.4/getting-started/introduction/): Bootstrap Library used throughout the project mainly to make site responsive using the Bootstrap Grid System.

-   [MDN Web Docs](https://developer.mozilla.org/) : For Pattern Validation code. Code was modified to better fit my needs and to match an Irish phone number layout to ensure correct validation. Tutorial Found [Here](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/tel#Pattern_validation)

### Content

-   All content was written by the developer.

-   Psychological properties of colours text in the README.md was found [here](http://www.colour-affects.co.uk/psychological-properties-of-colours)

### Media

-   All Images were created by the developer or sourced from image websites where Creative Commons license is active.

## Credits.

Bootstrap documentation:

https://getbootstrap.com/docs/4.0/getting-started/introduction/

Images (via google search):

https://pixabay.com/illustrations/hiking-mountain-couple-flat-design-4866373/

CSS-Tricks (in particular this great page on box-shadow):

https://css-tricks.com/almanac/properties/b/box-shadow/

Font Awesome (Icons):

https://fontawesome.com/

Adding correct href types for contact info:

https://www.elegantthemes.com/blog/wordpress/call-link-html-phone-number#:~:text=%E2%80%9CTel%3A%20123%2D456%2D,call%20to%20action%20you%20want.

Stock photo use:

https://www.pexels.com/photo/portrait-photo-of-smiling-man-with-his-arms-crossed-standing-in-front-of-white-wall-2379004/

https://www.pexels.com/photo/women-s-white-and-black-button-up-collared-shirt-774909/


### Acknowledgements

-   My Mentor for continuous helpful feedback.

-   Tutor support at Code Institute for their support.