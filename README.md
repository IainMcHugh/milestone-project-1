<!-- 
    1. User Stories, work back from each section on site to define them
    2. Test -> involve each link (Navbar example)
-->

<h1 align="center">Milestone Project 1 - HYKR</h1>

[View the live project here.](https://iainmchugh.github.io/milestone-project-1/)

HYKR is a mock homepage for a hiking clothing brand. It also acts as a simple e-Commerce shop for the clothing brand, which users have immediate access to via the homepage. The site aims to create a modern and high quality feel for the clothing brand through use of dynamic content and responsive layouts. 

![Cover Photo](https://github.com/IainMcHugh/ms1/blob/master/assets/images/readme-cover.PNG?raw=true)

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
        -   The two main colours used are ![#8DD6FF](https://via.placeholder.com/15/8DD6FF/000000?text=+) `#8DD6FF` and ![#f03c15](https://via.placeholder.com/15/ed8fef/000000?text=+) `#ED8FEF`. I chose these colours in particular as I find with a linear gradient they capture an early morning sky, something that avid hikers are familiar with as arduous hiking will often involve starting very early in the morning. I also came across <a href="https://en.wikipedia.org/wiki/Electric_blue_(color)">Electric Blue</a> after noticing a similar shade of striking blue on various sites, and have used that as a reference for some of the other blue shades incoroprated into the site.
    -   #### Typography
        -   The Poppins font is the main font used throughout the whole website with Sans Serif as the fallback font in case for any reason the font isn't being imported into the site correctly. Poppins is both an easily readable font as well as bubbly font that I find very effective at drawing the users eye. It also gives a high quality feel to the overall site.
        <a href="https://fonts.google.com/specimen/Poppins">Poppins</a> - Google Fonts
    -   #### Imagery
        -   Imagery on the site is broken into two groups. There are cartoon images used in both the home and overview section. In the shop section, there are sample product images. I felt that cartoon images helped to keep a seemless feeling to the site, as well as ultamitely give a pop to the actual shop items when the user scrolls to this section. I also designed a simple logo in photoshop in keeping with the colour scheme and overall design of the site. Lastly, I have implemented css clip-paths to transform section breaks into visual imagery, as these slight slants tie in with the theme of hiking while not being too dramatic as to solidify there primary purpose as visual section breaks.
    -   ### Animation
        - There are three seperate animations within the site. On initial page load there is a css animation for the mountain jutting out of the homepage. I think this rising effect fits well within the theme of the site and also provides dynamics to the site, making the user feel they are dealing with a high quality product. There is also a very slow cloud moving horizontally behind the mountain. Again this adds to the dynamic feel of the site, while also being sufficiently opaque and slow as to not unnecessarily distract the user.

*   ### Wireframes

    -   Figma Wireframe - [View](https://www.figma.com/file/QnfsdsjYig0fVDAhb79AH5/HYKR?node-id=0%3A1)
    -   Note: The Wireframe was something I used primarly as a method to get my initial concept ideas down as well as general page layouts and colour schemes. Originally my aim was to create a sample Hiking blog site however throughout development I felt the idea would pan out better as a mock clothing brand site. I did create mockups for each section of the altered design on a whiteboard, which can be viewed <a href="https://github.com/IainMcHugh/ms1/tree/master/assets/mockup">here</a>

## Features

-   Responsive across all device sizes

-   Interactive elements with seamless animations

-   Comprehensive navigation

-   Smooth scrolling

-   Carousel implementation for Shop section

-   Linear-gradient colouring with clip-paths

-   Contact form with input placeholders for purpose

## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries & Programs Used

1. [Bootstrap 4.0.0:](https://getbootstrap.com/docs/4.4/getting-started/introduction/)
    - Bootstrap was used to assist with the responsiveness and styling of the website.
3. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Poppins' font into the style.css file which is used on all pages throughout the project.
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

-   [W3C Markup Validator](https://validator.w3.org/) - [Results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fiainmchugh.github.io%2Fmilestone-project-1%2F)
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results](http://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fiainmchugh.github.io%2Fmilestone-project-1%2Fassets%2Fcss%2Fstyles.css&profile=css3svg&usermedium=all&warning=1&vextwarning=)

(Note: Validators were only used for html and css page(s) created specifically for this project. All css library files that ship with bootstrap were excluded from validation)

### Testing User Stories from User Experience (UX) Section

-   #### Site Visitor Goals

    1. As a site Visitor, I want to understand the purpose and nature of this particular brand via their website.

        1. Upon entering the site, the visitor is met with a "call to action" banner text explicitly outlining the purpose of the site.
        2. As the user scrolls, they are met with an overview section that details the purpose of the site, with accompanying imagery.

    2. As a site Visitor, I want to get an idea of what sort of products are available on this website.
        1. A fixed Navigation bar is clearly visible along the top of the site, that clearly indicates to the user a "Shop" section.
        2. Each section of the site is clearly divided for the user, with striking colour changes for section changes.
        3. There is a large "Order today" heading outlining the Shop section.
        4. Each item available in the shop section is clearly distinct as it's own card, with appropriate spacing between item image, name and description, and item option buttons.
        5. All item images have had their backgrounds removed to help stand the item out for the user to see.
        6. The two actionable buttons "Purchase" and "Info" on each card are contrasting colours making the options available to the user clear.
        7. A hover effect for items on larger screens makes it clear to site visitors that shop items are actionable on.

    3. As a site Visitor, I want a seemless experience that keeps my attention throughout the entirety of the website via appropriate visual cues and clearly divided sections.

        1. All section anchor links have smooth scrolling, which creates a nice visual effect and also makes clear to the site visitor where they have navigated from and to on the site.
        2. Through the use of clip-paths, slanted horizontal lines have been used to divide certain sections so as to guide the site visitors eyes downwards through the site.
        3. Contrasting colours make it clear to the user when they traverse from one section to another.

    4. As a site Visitor, I want to easily navigate to the section of the site I am interested in returning to.

        1. A full width Navigation bar is fixed to the top of the site, so the site visitor can easily navigate to any section they want with a single click.
        2. The site is broken up into only four sections, so the page is not too busy and it is clear to the visitor at all times where they are on the site.

    5. As a site Visitor, I want a clear and concise contact section, that provides all of the necessary information for me to contact the site owners.

        1. A fixed Navigation bar is clearly visible along the top of the site, that clearly indicates to the user a "Contact" section.
        2. The contact section has a clear heading, and is clearly divided into two distinct sections.
        3. The top contact section provides site visitors with a column of various contact methods for the brand, with icons to further illustrate that contact method (phone, email, geolocation)
        4. The bottom contact section provides a form for the user to directly contact the site owners. It is both in keeping with the overall modern style of the site, while also clearly indicating the intent of each form input for the user via placeholders.
        5. The user can submit the form through the use of a submit button which is represented with an arrow icon.
        6. When the site visitor focuses on an input, feedback is provided via a slight change in background colour of that input.

### Further Testing

-   The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge and Safari browsers.
-   The website was viewed on a variety of devices such as Desktop, Laptop, iPhone7, iPhone 8 & iPhoneX.
-   A large amount of testing was done to ensure that all pages were linking correctly.
-   Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

### Known Bugs

-   Mountain anim causes white padding on bottom, Form size, white bar above footer

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
    - Alternatively Click [Here](https://raw.githubusercontent.com/) for a GIF demonstrating the process starting from Step 2.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://iainmchugh.github.io/milestone-project-1/) in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/IainMcHugh/milestone-project-1/)
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

-   [Bootstrap Documentation](https://getbootstrap.com/docs/4.0/getting-started/introduction/): Bootstrap Library used throughout the project, for overall section layouts as well as implementing a hamburger navigation bar and carousel shopping section for smaller screens

-   [CSS-Tricks](https://css-tricks.com/almanac/properties/b/box-shadow/): CSS-Tricks website for providing great code snippets as well as accompanying imagery for how the code will look. In particular this great page on box-shadow provides css samples for really authentic shadowing.

### Content

-   All content was written by Iain McHugh.

-   [Multi-mockup](https://techsini.com/multi-mockup/): A great resource for generating mockup displays for the site on various different screens and devices. Used for the cover photo of this readme file.

-   [Electric Blue](https://en.wikipedia.org/wiki/Electric_blue_(color)): A colour value that I used as an initial starting place for the overall colour theme of the site.

### Media

-   All images were created/edited by the developer or sourced from image websites where Creative Commons license is active.

-   [Site for cartoon images](https://pixabay.com/illustrations/)
-   [Site for Portrait photos](https://www.pexels.com/)

### Acknowledgements

-   I would like to thank my mentor, Oluwafemi. You really helped give me a direction and plan for how to approach this milestone project. You also provided me with various resources to help me implement features on the site, and I learned a lot from your design input on the site, in particular how to step back from the code and try to view the site as a new visitor. 

-   I also want to thank Code Institute in providing me with information and guides on how to structure my project. I feel I have a good grasp on web development fundamentals as well as a proficiency in Bootstrap due to the modules provided by Code Insitute.

-   Lastly I would like to thank the Slack community associated with Code Institute. In particular the "Tutors and Mentors Live Q&A" and "MS1 Planning" call. (Maria, Claire, Tim, and Jim). These call sessions gave me great insight and direction with regards to my milestone project.