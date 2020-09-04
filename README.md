# [Shoe Shine](https://jacktubby.github.io/ShoeShine/)

![index screenshot](/assets/images/index-screenshot.png)

This website is "Shoe Shine". Shoe Shine is for users who need their shoes cleaned. They are able to send their favourite and well-loved shoes in for a basic or premium clean, to show this there is a comparison of what the different packages include. Also incorporated on the site is a gallery, frequently asked questions and contact page. 
 
## UX
 
The projects aim is to give the user all the information needed about Shoe Shine, so they can decide if it is what they need.

### Project Goals 

- Tell the user all useful information about the company, so they understand where Shoe Shine came from.
- Show the user examples (before and after), so they can see the results of the cleaning process.
- Get the user to fill out the contact form.

### Owner Stories

- As a site owner, I want users to be able to see how we receive, clean and deliver the shoes. So they understand how the business works.
- As a site owner, I want users to be able to know how the company was created and where we started, to build a relationship with the consumer.
- As a site owner, I want the different packages to be easily accessible, so they can compare.

### User Stories

- As a user, I want to know the origins of the company, to understand their background.
- As a user, I want to be able to see the different packages, so I can compare.
- As a user, I want to know what my shoes are cleaned with, so I know they are not harmful.
- As a user, I want to find out the opening hours.
- As a user, I want to find out the location.

### Surface 

#### colours

- I have decided to use two main colours throughout the website, (#1F4068, #206A5D). I have chosen these colours because they complement each other well, are easy on the eye and shows the typography well. For the background I have chosen grey, which is neutral (#EBECF1) therefore enhancing the two main colours. Some parts of the website will have the background color (#1F4068) which is a deeper blue, therefore I have chosen to use white text on this background to capture the users eye.


#### Typography 
- I have used 'Lato' for the main text throughout the website and also the navbar, I have gone with this font as it is clean, sleek and easy to read.
- I have used 'Krona One' for the main logo, and some headings including the 'faq' page questions. I have chosen this font as it stands out well and catches the users eye.


### Wireframes

My wireframe includes a desktop and mobile version. I did not choose to include a ipad version as it looks the same as the desktop.

[WireFrames](https://github.com/JackTubby/ShoeShine/blob/master/assets/docs/ShoeShine%20Wireframe.pdf)

## Features

### Existing Features

- Designed with HTML5, CSS3 and Bootstrap.
- Packages Section - allows users to compare packages to decide what package is best for them.
- Testimonials Section - allows users to read the testimonials, which will let users see previous users experiences.
- Contact Form - allows users to put their information about them and their shoes and choose the right package for them, so the company knows what the user is after.

### Features Left to Implement

A future feature I would like to implement would be some videos, showing the cleaning process. 

## Technologies Used

- HTML5 
- CSS3
- Frameworks
  - The project used Bootstrap for responsive design.
- FontAwesome
- Google Fonts
- Git
- GitHub
- Visual Studio Code

## Testing

- Testing the "Contact Us" page.
   1. Clicked on the "Contact Us" page.
   2. Clicked on the submit button with an empty form, to see that the required fields appears.
   3. Entered an invalid email to check the relevant error message appears.
   4. Entered all inputs to check the form submits successfully.

- Testing the gallery "get in touch" link.
    1. Clicked on the "Gallery" page.
    2. Clicked the "get in touch" link.
    3. Checked that it took me to the contact page.

- Testing footer social links
  1. Clicked on all social links (Facebook, Twitter, Instagram) on each page of the website.
  2. Made sure they opened the correct website in a new tab.


### Validator Tests

After putting my code through the validator I got a list of errors, (list of errors and fixes below) after going through the errors and fixing them I placed my code back through the validator. The validator returned with "Document checking completed. No errors or warnings to show." The reason I used the W3C validator is for quality assurance.

- I used the [W3C](https://validator.w3.org/) for html validation.
- I used [W3C](https://jigsaw.w3.org/css-validator/) for css validation.

#### Index.html

- 2 errors - 2 unclosed div's.

- fix - To correct this I closed the div's and put it back through the validator which then came back with no errors.

#### gallery.html 

- 2 errors - A element must not appear as a descendant of the button element / Named character reference was not terminated by a semicolon. (Or & should have been escaped as & amp;.).

- fix - Removed the button and just used the link element | Added a semi-colon after &copy.

#### faq.html 

- 2 errors - Stray end tag i / Named character reference was not terminated by a semicolon. (Or & should have been escaped as & amp;.).

- fix - Removed stray i tag | Added a semi-colon after &copy.

#### contact.html

- 5 errors -  End tag nav seen, but there were open elements | Unclosed element div | Named character reference was not terminated by a semicolon. (Or & should have been escaped as & amp;.) | x2 The aria-describedby attribute must point to an element in the same document.

- fix - To fix error 1/2 I had to close the div element | Added a semi-colon after &copy | Changed aria-describedby to aria-label.

#### style.css

- 1 error - .gallery_text_styling	Property size doesn't exist. The closest matching property name is resize : 20px.

- fix - Changed the size property to font-size.

## Deployment

This site was deployed on GitHub Pages, the steps I took to do this was:

- The code was written in VS Code.
- I pushed the code to my GitHub repository.
- In the repository settings, I scrolled down to the GitHub Pages.
- Under 'source', I selected the 'master branch'. 
- I published the project to GitHub pages, which provided me with a url.
- The deployed website and development site are the same.

## Credits

### Media

* The photos used in the Gallery were obtained from two sites: https://en-gb.facebook.com/pg/myshoemo/photos/?tab=album&album_id=912590665539042&ref=page_internal and https://www.pexels.com/

### Acknowledgments

- Bootstrap - I used bootstrap for it's responsive features and showing how the code works with demos, which helped with the development process.
- Slack - I used Slack for peer review of my site and any minor bug fixes.
- Mentor - My mentor helped me decide where to focus my time and make improvements, which was very beneficial for my site development. 