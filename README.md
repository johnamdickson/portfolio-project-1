


# <img src="assets/images/logo-favicon.png"  width="50" height="50"> Learn to Crochet by Little Woolly Snuggles

Learn to Crochet is a website created for Little Woolly Snuggles, a handmade craft business that specialises in crochet and knit products. The site is targeted towards people that are interested in learning crochet by introducting them to the craft and showing them the basics. 

This website is showcasing HTML and CSS design for Project Portfolio 1.

![Responsive Mockup Screenshot](/assets/README-files/am-i-responsive-screenshot.jpg)

## Design
### Colour Scheme
- The colour scheme was selected  to provide a match with the dominant two colours in the logo. At first the colours were sampled using a dropper, with a more purple colour for the header and footer and a darker green for the applicable body elements backgrounds. 
- Feedback from the client led to a revision of the colours towards pink for the header and footer and a pastel green for the main element backgrounds but still retaining a connection to logo dominant colours.
- [Name That Color](https://chir.ag/projects/name-that-color/) website was utilised to name the two colours thereby allowing a more meaninful description with the client once the they were agreed.
#### Jet Stream
![Jet Stream](/assets/README-files/jet-stream-color.jpg)
#### Illusion
![Illusion](/assets/README-files/illusion-color.jpg)
<br><br>

### Typography

All fonts were sourced from Google Fonts:

 - Prompt. A sans-serif font used for h1, h2 and nav elements.
 - Dancing Script. A cursive font used for h3 elements.
 - Maitree. A serif font used for body and input elements.
<br><br>

## Features 

### Existing Features
- __The Title Bar__
  ![Title bar](/assets/README-files/icon-in-title-bar.jpg)
  - The Little Woolly Snuggles logo appears in the title bar as a small icon to help increase user engagement with the website and company brand.
<br><br>

- __Navigation Bar__
  ![Nav Bar](/assets/README-files/nav-bar-normal.jpg)
  - On the LHS there is the company logo along with website title and a reference to Little Woolly Snuggles as an h3 in handwritten font to both distinguish it from the h1 and tie into the associated logo handwriting, which can be viewed in the last image on the home page.
  - There are three hyperlinks on the right of the bar allowing for navigation between the available pages. The hyperlink on the active page has custom styling to distinguish it from the non-active pages.
  - This section is further responsive to 3 different media screen sizes: Normal (>1200px), max screen width 1200px and max screen width 750px.
<br><br>


- __The Footer__ 
![Footer](/assets/README-files/footer.jpg)
  - The footer section includes links to the actual social media sites for Little Woolly Snuggles. The links will open up a new tab to allow easy navigation for the user. 
  - The footer also contains a link to the company's Etsy shop.
  - The footer is fixed to the bottom of the page and is accessible at any time whilst browsing. 
  - The links use fontawesome icons with a colour consistent with the text colour used elsewhere in the website.
<br><br>

- __The Home Page - Hero Image__
![Hero Image](/assets/README-files/hero-image.jpg)

  - The home page hero image is a striking picture of a series of colour coordinated yarn spools arranged on a shelf. 
  - A zoom effect is utilised on the hero image using @keyframes animation to further accentuate the image to the user.
  - This section also includes a sign up circle which when pressed leads the user to the sign up page.
  - The sign up circle is also animated and appears after the hero image animation is completed.
 <br><br>
- __The Home Page - What is Crochet? Section__
![What is Crochet Section](/assets/README-files/what-is-crochet-section.jpg)
  - This section consists of an overview of crochet derived from Wikipedia and located in a styled div floated left. The div background colour is the theme colour Jet Stream.
  - Floated right is a circular close-up picture of persons hands as they crochet, bordered in the theme colour Jet Stream. 
<br><br>

- __THe Home Page - Why Learn to Crochet? Section__
![What is Crochet Section](/assets/README-files/why-learn-to-crochet.jpg)
  - This section highlights benefits to learning crochet in an unordered list along with font awesome icons to further style the text. 
  - There is another circular bordered photo of a person holding items of that have been crafted by crocheting.
  - The float properties of the image and paragraph container are opposite the corresponding elements for the What is Crochet section to create an offset effect and a visually stimulating transition downwards.
  - The section has a blurred background image of yarn again to create contrast and a visual effect. This background attachment is fixed to create a perspective against the background as the user scrolls downwards.
  - The h2 heading font colour change and shadowing properties help it to stand out against the background image.
  <br><br>

- __The Home Page - Why Little Woolly Snuggles? Section__
![What is Crochet Section](/assets/README-files/why-little-woolly-snuggles.jpg)
  - This is the last section on the Home Page and contains a paragraph giving context to what Little Woolly Snuggles is.
  - The circular image in this instance is the company logo along with company name with styled font.
  - The layout of image and paragraph div is the same as What is Crochet? section and creates a further offset agains the Why Learn to Crochet section.
<br><br>

- __The Get Started Page - What You Will Need Section__

  - This is the first section on the page and displays a horizontal series of 4 circular images all bordered in the Jet Stream theme colour, defining pictorally the necessary requirements for crocheting.
  - Beneath each image, is a rounded div containing paragraphs detailing the 4 requirements with a brief description.
  - Each paragraph contains a span which applies bold styling to the first sentence so that the requirement stands out against the description.
<br><br>

- __The Sign Up Page__

![Sign Up Page](/assets/README-files/signup-page.jpg)

  - This page will allow the user to subscribe to the Little Woolly Snuggles newsletter. Note this newsletter does not currently exist and is used as a means to demonstrate a get form element.
  - The page header and footer are the same for the other pages, again to ensure consistency across the site.
  - The background image is the balls of yarn as used behind sections in previous pages. The difference in this page is that the blurred effect is absent which creates context to the previous pages and a continuous thread through all of them. 
  - The sign up form contains required input text fields for first name, last name and e-mail along with a submit button. 
  - Hover psuedo classes were adopted to responsively style the form elements in a manner consistent with the overall website theme.
  A submit button which when pressed directs the user to a hidden page with a thank you message.
<br><br>

- __The Thank You Page__

  ![Thank You Page](/assets/README-files/thank-you-form.jpg)
  - This page can only be accessed through the website when the Sign Up form is filled in completely and submitted. 
  - The navigation menu links are purposely not styled as active for this page to make it clear to the user that this is a supplementary page.
  - There is a form element with styling matching the Sign Up page form whereby the user is thanked for signing up.
  - Another submit button is available at the bottom of the message to return home.
  - To increase engagement with the thank you message, JS code was added to parse first name data from the thank you page URL and add to the thank you message. 
<br><br>


### Features Left to Implement
- Videos of the instructions was considered early on in the strategy plane. However, this was deemed as a trade off during the scoping exercise due to time contraints and the required objectives of the project. 

## Testing 

 - __Nav Bar__
   - The Nav Bar responsiveness was checked across the three widths as described in the features section. Some minor styling adjustments were made to get the font size right and in the end behaviour was as expected.
      - Nav Bar Normal Width
![Nav Bar Normal](/assets/README-files/nav-bar-normal.jpg)
      - Nav Bar Max Width 1200px
![Nav Bar 1200](/assets/README-files/nav-bar-1200px.jpg)
      - Nav Bar Max Width 750px
![Nav Bar 950](/assets/README-files/nav-bar-750px.jpg)
   - The h3 font was changed after consultation with the client to resemble the font in the company logo.
<br><br>

- __Home Page__

  - The GIF below demonstrates both hero image animations as they appear when the page loads.
  ![Hero Image](/assets/README-files/hero-image-animation.gif)
  - The responsive styling of the nav menu items was also verified with the Home li being highlighted.
  - The responsive styling of the body elements for various screen sizes was tested. Adjustments were made during the testing process to change the font size of the info-container paragraphs according to screen size using vmin as using absolute sizes either overflowed the container or were too small.
  - The images and info containers were positioned using the float properties and this worked adequately fot a simple two element section.
  - The GIF below demonstrates the Home Page responsiveness across varying screen sizes.
  ![Home Page Responsiveness](/assets/README-files/home-page-responsiveness-test.gif)
<br><br>
- __Sign-Up Page__

  - Responsive design on the form elements was tested as shown in the GIF below:
  ![Sign Up Responsiveness](/assets/README-files/form-responsive-elements.gif)
<br><br>

- __Thank You Page__

  - Transition from Sign Up page to Thank You page tested by filling out form and then clicking submit.
  - Confirmation that the first name was parsed from URL also checked succesfully. 
  - The active class styling was deselected in the nav menu as expected.
  - The home button worked as expected, returning the user to the home page.
  - See GIF below showing Sign Up transition to Thank You page, presence of first name in thank you message and return to home page.
    ![Transition to Thank You Page](/assets/README-files/transition-to-thank-you-page.gif)
<br><br>

### Validator Testing 

- HTML
  - No errors were returned for each page when passing through the official W3C valifattor 
    - [Home Page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjohnamdickson.github.io%2FPortfolio-Project-1%2Findex.html)
    - [Get Started Page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjohnamdickson.github.io%2FPortfolio-Project-1%2Fget-started.html)
    - [Sign Up Page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjohnamdickson.github.io%2FPortfolio-Project-1%2Fsign-up.html)
    - [Thank You Page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjohnamdickson.github.io%2FPortfolio-Project-1%2Fthank-you.html)
    
    

- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fjohnamdickson.github.io%2FPortfolio-Project-1%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html 


## Credits 

### Content 

- The description of crochet was taken from Wikipedia.
- The benefits of crochet were taken from two crocheting websites and a study referenced in the National Library of Medicine.
- Stack Overflow, W3 Docs, MDN Web Docs and other online resources were a massive help for HTML or CSS code that enabled some of the functionality I was looking for. 
- Slack was an enormous help in resolving common issues that others had faced before me. 
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
- I would finally like to thank my wife Sinéad whose crocheting talents inspired me to build this website for my first project portfolio.

For a full list of references please review this [pdf.](/assets/README-files/reference-list.pdf)

### Media

- Many of the photos used extensively through the site were obtained from [Pexels](https://www.pexels.com/)
- Many of the photos were taken at home with the assistance of my wife.



## Other General Project Advice

Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work! 

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write  a Git Commit Message 
  - Make sure to keep the messages in the imperative mood 

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.
  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept. 

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process! 