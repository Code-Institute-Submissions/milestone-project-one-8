
# Project - Cygnet Lawn and Maintenance

This project is a commercial page designed for my brother who is starting a new lawn mowing and garden maintenance business A demo can be found [here.](https://lesreddy.github.io/milestone-project-one/)

His brief was to create a page which provided a relevant online presence and which would persuade the visitor to make contact and get a quote.
He also wanted this achieved in a simple and clear way as his market demographic is older and less tech savvy than younger generations in general.

## UX

* Given the brief the need was clear for a strong pitch throughout the site to encourage visitors to get a quote.

* This meant highlighting the key value propostion early on to spark interest and potentially inspire a connection.

* With the purpose in mind several 'get quote' buttons on the landing page and at the bottom of each section were implemented.

* There is also a clear call to action (lawn mowed from $40) and a clear 'why' message in each section to re-enforce a 'get quote' response.

* The presence of the phone number in the corner is an important consideration, listening to clients feedback, customers liked an easy, simple and clear way to get in touch.
 
* As a new user to the site the intention is to keep their interest quickly and guide them to the get quote touchpoints easily.  

* For a returning visitor the site the quote forms need to be quickly accessible and the phone number needs to be easily sourced.

* For a commercial visitor they need to be easily guided to the quote forms and the contact page for making a query through the email address or the quote form.

* The typography, colors and images were chosen based on the brief and the purpose - simple, clear and fresh.  The green is an obvious link to the type of business.

### Wireframes

For the wireframes I used Figma and they can be found [Here.](https://www.figma.com/file/TFhKUFZm6Jwh3Q1qq7ujJ9hu/Explore?node-id=18%3A162)
I initially designed wireframes for the mobile and then the desktop and then I settled on the desktop styling for the final site.

## Features

### Existing Features

There are four key sections to the site

1.  Landing Page - Shows off the Logo, callout and Navbar with the first get quote button.
2.  About Page - Re-enforces the callout value proposition and shows second get quote button.
3.  Services Page - Re-enforces the about page with the services offered and another get quote button.
4.  Contact Page - Gives contact details and another clear method for customer connection.

Each section is designed to reinforce a different value propostion in order to persuade a customer to make contact.  A button is visible at each section for easy access to the quote modal/section.  Parallex scrolling is evident on the larger screen size (1024px and above).

### Features Left to Implement

The current state of the site is wholistically a layout and design blueprint.  The information will need editing as clarification on the exact services the business will offer is supplied at later date.

As the business matures customer testimonials will be added plus a gallery of photos which will each have their own section.  Also the photos behind the type of service will be changed to real shots from customer jobs.


## Technologies Used

The following was used to construct the site:

1. [Cloud9](https://c9.io/login) - a cloud based coding platform that was used for the coding and storing a local repository.
2. [BootstrapCDN](https://www.bootstrapcdn.com/) - used to simplify the structure and to make it responsive.
3. [jquery](https://www.jquery.com) - used to reference Javascript for the Modal.
4. [Google Fonts](https://fonts.google.com/) -  used to style the website fonts.
5. [Figma](https://www.figma.com) - cloud based design tool used for the wireframes.

### Languages

1. CSS - used externally in a file called [style.css](https://github.com/lesreddy/milestone-project-one/tree/master/assets/css).
2. HTML - created one page called [index.html](https://github.com/lesreddy/milestone-project-one/blob/master/index.html).


## Testing

The site achieves the objective to give the new business a bright fresh online presence and gives mulitiple opportunities for potential customers to connect and get a quote.

* The site was tested across multiple browsers (Chrome, Safari, Internet Explorer, FireFox) and on multiple mobile/tablet devices (iPhone X, IPad, Samsung Galaxy S7, Galaxy C5 Pro) to ensure compatibility and responsiveness.

* Responsiveness was heavily tested and fonts and images were altered accordingly to best suit the size of the display. 

* Due to the lack of parallex scrolling with smaller screens and a known bug with IOS ('background-attachment: fixed' plus 'background-size: cover' - [reference](https://caniuse.com/#search=background-size)) available on smaller screens (without adding JS which is beyond the scope of this project) I put in a media query to initiate 'background-attachment: scroll' feature for screens 1023px and smaller in width. 

* I would like to test the page on a larger apple computer but I dont have access to one, IOS might have an issue with the parallex scrolling.

* All links were tested and worked on all media browsers and devices I had access to. 


### Landing Page

* In regard to UX for a new visitor the page has access to a get quote button after a clear value proposition in the call out.
* For re-visits it also has an easy access to the phone number and quote and links to the other sections on the navbar.
* Social media links go to the main social media sites and will be more specific as when the pages for the business are created.


### About Us Page

* For new visitors this strengthens the value proposition and again has access to a quote modal.
* For re-visits it offers the quote modal (as they should already be convinced by the value proposition)
* Page is 3 columns which then splits into two as the screen size reduces, where the centre column (team photo) is removed until the mobile sizes where it is brought back in and all columns are stacked.
* This page can be reached from the Navbar and the Footer and is designed to sit neatly under the heading once clicked and scrolled.  For screens smaller than 992px it is still achieved the menu needs to be closed to see it (this applies to all sections)

###  Services Page

* For new visitors this helps re-strenthen the value proposition and again gives access to a quote button
* For revisits the quote page can be accessed.
* The landscaping image needed changing, even after it was reduced and put through Tinypng it was still 1mb and conscious of data usage/page load time it was switched to an image with a size of 619kb.


### Contact Page

* This page offers all connection options for both new visitors, re-visits or commercial customers.
* This page was split into two columns and the challenging part of this was getting the smaller logo and contact details to align centrally for smaller screens and then align to the left for screens larger than 767px.


## Deployment

The site was developed using [Cloud9 IDE](https://c9.io), commited to Git and then pushed to Github.

In order to enable this follow these steps:

1. On Github navigate to https://github.com/lesreddy/milestone-project-one
2. Under repository name (lesreddy/milestone-project-one) click `settings`
3. Use the Select source drop-down menu to select master branch as your GitHub Pages publishing source.
4. Select `save`.

If you would like to create a local repository then you need to clone it by taking the following steps:

1. On Github navigate [here](https://github.com/lesreddy/milestone-project-one) to access the remote repository.
2. Under the repository name click 'Clone or download' (big green button)
3. In the `Clone with HTTPs section`, click to copy the clone URL for the repository.
4. Open Git Bash in your IDE.
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type git clone, and then paste the URL you copied in Step 2. (https://github.com/lesreddy/milestone-project-one.git)
```console
git clone https://github.com/lesreddy/milestone-project-one.git
```
7. Press Enter. Your local clone will be created.

Whilst I did not use other branches when pushing it to github, I will be for future larger projects to break it up and then merge as required.

## Credits 

### Content

All content in the 'About' and 'Services' section was written by myself, as stated it will be edited as I get further clarification on the exact services offered.

The logo was supplied by my brothers friend - Matthew Barnes - who is a graphic designer.  Initially it was sent as JPEG and PNG, however, I had him send me a transparent SVG file to improve the scalability and loading time for the landing page.
His page can be found [here.](http://www.mzbarnes.com/) 

### Media

Images were taken from [Pexels](https://www.pexels.com/) and also [Adobe Stock](https://stock.adobe.com/ie/).  

The team photo was supplied by my brother.

[Tinypng](https://tinypng.com/) was used to compress images from high res state to maintain quality.

[MS Paint](https://ms-paint.en.softonic.com/) was also used to re-size images down to full hd before putting through Tinypng to maximise compression.


### Acknowledgements

Stack Overflow was used to edit the default bootstrap4 navbar colors and the link can be found [here.](https://stackoverflow.com/questions/43381596/bootstrap-4-navbar-color). The developer for this is [Zim.](https://stackoverflow.com/users/171456/zim)

Stack Overflow was also referenced to implement the hover effect of the images in the about services page and can be found [here.](https://stackoverflow.com/questions/22675760/text-over-image-using-css-transitions). The developer for this is [Cristofer Vilander.](https://stackoverflow.com/users/1137696/christofer-vilander)

The codeinstitute example site by [Haley Schafer](https://www.haleyschafer.com/) inspired the layout design.

The codeinsitute example cv mini project inspired the contact and get quote page and also the social media icons.

Css tricks was referenced to source the correct code snippets for [scroll behaviour](https://css-tricks.com/almanac/properties/s/scroll-behavior/) and [mailto](https://css-tricks.com/snippets/html/mailto-links/) functions.

Would like to thank Anna Greaves (CSS Fundamental Lead) and Simen Daelin (Mentor) for their great hints and tips along the way.