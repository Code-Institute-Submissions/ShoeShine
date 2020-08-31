# ShoeShine

This website is "Shoe Shine". Shoe Shine is for users who need their shoes cleaned. They are able to send their favourite and well-loved shoes in for a basic or premium clean, to show this there is a comparison of what the different packages include. Also incorporated in the site is a gallery, frequently asked questions and contact page. 
 
## UX
 
  The website is designed to be sleek, but also informational so the consumer can complete achieve what they need. 

#### Owner Stories

- As a site owner, i want users to be able to see how we receive, clean and deliver the shoes. So they understand how to buisness works.
- As a site owner, i want users to be able to know how the company was created and where we started, to build a relationship with the consumer.
- As a site owner i want the different packages to be easily accessible, so they can compare.

#### User Stories

- As a user, i want to know the origins of the company, to understand there background.
- As a user, i want to be able to see the different packages, so i can compare.
- As a user, i want to know what my shoes are cleaned with, so i know they are not harmful.
- As a user, i want to know the process of how to shoes are cleaned from start to finish, so i can see if its right for me.
- As a user, i want to find out the opening hours.
- As a user, i want to find out the location.

## Features

#### Existing Features

- Designed with HTML5, CSS3 and Bootstrap.
- Packages Section - allows users to compare packages to decide what package is best for them.
- Testimonials Section - allows users to go to the testimonial section directly on a different page, which will let users see previous users experience.
- Contact Form - allows users to put there information about them and their shoes, to understand what they need from the service.

#### Features Left to Implement

A future feature i would like to implement would be some videos, showing the cleaning process. 

## Technologies Used

- HTML 
- CSS
- Frameworks
  - The project used Bootstrap for responsive design.
- FontAwesome
- Google Fonts
- Git
- GitHub
- Visual Studio Code

## Testing

- Testing the "Contact Us" page
   1. Clicked on the "Contact Us" page
   2. Clicked on the submit button with an empty form, to see that the required fields appears
   3. Entered an invalid email to check the relevant error message appears.
   4. Entered all inputs to check the form submits successfully.


#### Validator Test

**Index.html**
2 errors - 2 unclosed div's
**fix**
 To correct this i closed the div's and put it back through the validator which then came back with no errors.

**gallery.html** 
2 errors - a element must not appear as a descendant of the button element / Named character reference was not terminated by a semicolon. (Or & should have been escaped as & amp;.)
**fix** 
Removed the button and just used the link element | Added a semi-colon after &copy 

**faq.html**
2 errors - Stray end tag i / Named character reference was not terminated by a semicolon. (Or & should have been escaped as & amp;.)
**fix**
Removed stray i tag | Added a semi-colon after &copy

**contact.html**
5 errors -  End tag nav seen, but there were open elements | Unclosed element div | Named character reference was not terminated by a semicolon. (Or & should have been escaped as & amp;.) | x2 The aria-describedby attribute must point to an element in the same document
**fix**
To fix error 1/2 i had to close the div element | Added a semi-colon after &copy | Changed aria-describedby to aria-label

**style.css**
1 error - .gallery_text_styling	Property size doesn't exist. The closest matching property name is resize : 20px
**fix**
Changed the size property to font-size

## Deployment

This site was deployed on GitHub Pages.

## Credits

#### Media

* The photos used in the Gallery were obtained from two sites: https://en-gb.facebook.com/pg/myshoemo/photos/?tab=album&album_id=912590665539042&ref=page_internal and https://www.pexels.com/