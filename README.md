
# Project - Cygnet Lawn and Maintenance

This project is a commercial page designed for my brother who is starting a new lawn mowing and garden maintenance business, it can be found [here](https://lesreddy.github.io/milestone-project-one/)


His brief was to create a page which provided a relevant online presence and which would persuade the visitor to make contact and get a quote.
He also wanted this achieved in a simple and clear way as his market demographic is older and less tech savvy than younger generations in general.

## UX

Given the brief it was clear we needed to have strong clear pitch throughout the page to reiterate to the visitor why it was worthwhile to get in touch for a quote.
This meant considering the key value propostion that needed communicating within a relatively short space of time to spark interest and potentially inspire a connection.
With a clear purpose of generating as higher chance of a customer making contact, this objective is reflected with several 'get quote' buttons on the landing page and at the bottom of each section.  There is also a clear call to action on the landing page and a clear 'why' message in the about page presented almost immediately, followed by the services offered.
The presence of the phone number in the corner is an important consideration, my brother Ken has often found his customers like an easy way to get in touch and has taken feedback that other businesses are too hard to navigate to the phone number.
Again this is a reflection of the bulk of his customer base at the moment, which tends to be the older age bracket.  That said, if any demographic visits the page it still needs
to look interesting and colorful enough to hold their interest and potentially inspire a connection.

The typography, colors and images were chosen based on the brief and the purpose - simple, clear and fresh.  The green is an obvious link to the type of business.

For the wireframes I used Figma and they can be found [Here.](https://www.figma.com/file/TFhKUFZm6Jwh3Q1qq7ujJ9hu/Explore?node-id=18%3A162)

I initially designed wireframes for the mobile and then the desktop and then I settled on the desktop styling for the final site.


## Features

### Existing Features

There are four key sections to the site

1.  Landing Page
2.  About Page
3.  Services Page
4.  Contact Page

Each section is designed to reinforce a different value propostion in order to persuade a customer to make contact.  A button is visible at each section for easy access to the quote modal/section.  Parallex scrolling is evident on the larger screen size (1024px and above)

### Features Left to Implement

The current state of the site is wholistically a layout and design blueprint.  The information will need editing as clarification on the exact services the business will offer is supplied at later date.

As the business matures customer testimonials will be added plus a gallery of photos which will each have their own section.  Also the photos behind the type of service will be changed to real shots from customer jobs.


## Technologies Used

The following was used to construct the site:

1. [Cloud9](https://c9.io/login)
2. CSS 3
3. HTML 5
4. [Bootstrap 4](https://getbootstrap.com/)
5. [Github](https://github.com/)
6. [Figma](https://www.figma.com) (Wireframes)

## Testing

The site achieves the objective to give the new business a bright fresh online presence and gives mulitiple opportunities for potential customers to connect and get a quote.
The site was tested across multiple browsers (Chrome, Safari, Internet Explorer, FireFox) and on multiple mobile devices (iPhone X : Chrome and Safari, iPad, Samsung Galaxy S7) to ensure compatibility and responsiveness.
Responsiveness was heavily tested and fonts and images were altered accordingly to best suit the size of the display. 
Due to the lack of parallex scrolling with smaller screens and a known bug with IOS ('background-attachment: fixed' plus 'background-size: cover' [reference](https://caniuse.com/#search=background-size) available on smaller screens (without adding JS which is beyond the scope of this project) I put in a media query to initiate background-attachment: scroll feature for screens 1023px and smaller in width. 
I would like to test the page on a larger apple computer but I dont have access to one, there maybe be an issue with the parallex scrolling.

### Landing Page

This page, whilst fairly simple aesthetics, caused me the most challenge.  One of the biggest difficulties I had was incorporating the transparent image to enlargen in size as the screen went from mobile size and up.
I intially attempted this with straight CSS and then moved on to bootstrap 4 which did prove to be much easier once I had a good handle on the grid system.   
Currently the social media links are not working as the pages are not created but they will be soon and I wanted to leave them there for design purposes.

### About Us Page

This page is 3 columns which then splits into two as the screen size reduces, where the centre column (team photo) is removed until the mobile sizes where all columns are stacked on top of each other.
This page can be reached from the Navbar and the footer and is designed to sit neatly under the heading once it scrolls down, which is achieved on screens larger than 992px.  On screens smaller than this it still works but the menu needs to be closed to see it.
This goes all the pages other than the landing page.

### Contact Page

This page 


  Specifically the image of the business owners is displayed for desktop sizes and is removed for tablet sizes and then re-inserted for mobiles.  Also the font sizes get smaller as the viewport decreases.

## Deployment

The site was deployed to github directly from the master branch.  Whilst I did not use other branches when pushing it to github, I will be for future larger projects to break it up and then merge as required.

## Credits 

### Content

All content in the 'About' and 'Services' section was written by me and then cross checked for accuracy and validation by my brother and his business partner.

The logo was supplied by my brothers friend - Matthew Barnes - who is a graphic designer.  His page can be found [here.](http://www.mzbarnes.com/) 

### Media

Images were taken from [Pexels](https://www.pexels.com/) and also [Adobe Stock](https://stock.adobe.com/ie/).  

The team photo was supplied by my brother.

[Tinypng](https://tinypng.com/) was used to compress images from high res state to maintain quality.

[MS Paint](https://ms-paint.en.softonic.com/) was also used to re-size larger images to a size which Tinypng would accept (5mb)


### Acknowledgements

Stack Overflow was used to edit the default bootstrap4 navbar colors and the link can be found [here.](https://stackoverflow.com/questions/43381596/bootstrap-4-navbar-color) 

The developer for this is [Zim.](https://stackoverflow.com/users/171456/zim)

Stack Overflow was also referenced to implement the hover effect of the images in the about services page and can be found [here.](https://stackoverflow.com/questions/22675760/text-over-image-using-css-transitions)

The developer for this is [Cristofer Vilander.](https://stackoverflow.com/users/1137696/christofer-vilander)

The codeinstitute example site by [Haley Schafer](https://www.haleyschafer.com/) inspired the layout design.

The codeinsitute example cv mini project inspired the contact and get quote page and also the social media icons.