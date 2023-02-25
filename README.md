


# <img src="assets/images/logo-favicon.png"  width="50" height="50"> Learn to Crochet by Little Woolly Snuggles

Learn to Crochet is a website created for Little Woolly Snuggles, a handmade craft business that specialises in crochet and knit products. The site is targeted towards people that are interested in learning crochet by introducting them to the craft and showing them the basics. 

This website is showcasing HTML and CSS design for Project Portfolio 1.

![Responsive Mockup Screenshot](/assets/README-files/am-i-responsive-screenshot.jpg)

## Features 

### Existing Features
- __The Title Bar__
  - The Little Woolly Snuggles logo appears in the title bar as a small icon to help increase user engagement with the website and company brand.
  ![Title bar](/assets/README-files/icon-in-title-bar.jpg)

- __Navigation Bar__

  - On the LHS there is the company logo along with website title and a reference to Little Woolly Snuggles as an h3 in handwritten font to both distinguish it from the h1 and tie into the associated logo handwriting, which can be viewed in the last image on the home page.
  - There are three hyperlinks on the right of the bar allowing for navigation between the available pages. The hyperlink on the active page has custom styling to distinguish it from the non-active pages.
  - This section is further responsive to 3 different media screen sizes: Normal (>1200px), max screen width 1200px and max screen width 750px.

##### Nav Bar Normal Width
![Nav Bar Normal](/assets/README-files/nav-bar-normal.jpg)

##### Nav Bar Max Width 1200px
![Nav Bar Normal](/assets/README-files/nav-bar-1200px.jpg)

##### Nav Bar Max Width 750px
![Nav Bar Normal](/assets/README-files/nav-bar-750px.jpg)


- __The Home Page Hero Image__

  - The home page hero image is a striking picture of a series of colour coordinated yarn spools arranged on a shelf. 
  - A zoom effect is utilised on the hero image using @keyframes animation to further accentuate the image to the user.
  - This section also includes a sign up circle which when pressed leads the user to the sign up page.
  - The sign up circle is also animated and appears after the hero image animation is completed.
  - See GIF below which demonstrates both animations as they appear when the page loads.


![Hero Image](/assets/README-files/hero-image-animation.gif)


- __What is Crochet? Section__

  - This section consists of an overview of crochet derived from Wikipedia and located in a styled div floated left.
  - Floated right is a circular bordered close-up picture of persons hands as they crochet. 


![What is Crochet Section](/assets/README-files/what-is-crochet-section.jpg)

- __Why Learn to Crochet? Section__

  - This section highlights benefits to learning crochet in an unordered list along with font awesome icons to further style the text. 
  - There is another circular bordered photo of a person holding items of that have been crafted by crocheting.
  - The float properties of the image and paragraph container are opposite the corresponding elements for the What is Crochet section to create an offset effect and a visually stimulating transition downwards.
  - The section has a blurred background image of yarn again to create contrast and a visual effect. This background attachment is fixed.
  - The h2 heading font colour change and shadowing properties help it to stand out against the background image.


![What is Crochet Section](/assets/README-files/why-learn-to-crochet.jpg)


- __Why Little Woolly Snuggles? Section__

  - This is the last section on the Home Page and contains a paragraph giving context to what Little Woolly Snuggles is.
  - The circular image in this instance is the company logo along with company name with styled font.
  - The layout of image and paragraph div is the same as What is Crochet? section and creates a further offset agains the Why Learn to Crochet section.

![What is Crochet Section](/assets/README-files/why-little-woolly-snuggles.jpg)

- __The Footer__ 

  - The footer section includes links to the actual social media sites for Little Woolly Snuggles. The links will open up a new tab to allow easy navigation for the user. 
  - The footer also contains a link to the company's Etsy shop.
  - The footer is fixed to the bottom of the page and is accessible at any time whilst browsing. 
  - The links use fontawesome icons with a colour consistent with the text colour used elsewhere in the website.

![Footer](/assets/README-files/footer.jpg)

<!-- - __Gallery__

  - The gallery will provide the user with supporting images to see what the meet ups look like. 
  - This section is valuable to the user as they will be able to easily identify the types of events the organisation puts together. 

![Gallery](https://github.com/lucyrush/readme-template/blob/master/media/love_running_gallery.png) -->

- __The Sign Up Page__

  - This page will allow the user to subscribe to the Little Woolly Snuggles newsletter. Note this newsletter does not currently exist and is used as a means to demonstrate a form element.
  - The page header and footer are the same for the other pages, again to ensure consistency across the site.
  - The background image is the balls of yarn as used behind sections in previous pages. The difference in this page is that the blurred effect is absent which creates context to the previous pages and a continuous thread through all of them. 
  - The sign up form contains required input text fields for first name, last name and e-mail along with a submit button. 
  - Hover psuedo classes were adopted to responsively style the form elements as shown in the GIF below:


![Sign Up](/assets/README-files/form-responsive-elements.gif)

For some/all of your features, you may choose to reference the specific project files that implement them.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement

- Another feature idea

## Testing 

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.


### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

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