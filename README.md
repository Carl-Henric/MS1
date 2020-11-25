
# Project: My own resume page 
#### *This project is a website to promote myself in a trustworthy and visual way. Focus on the process has been to make an easily digested impression of me that is pretty straight forward with both design and technology. The main reason of the visitor is to contact me so I can introduce myself more properly in a meeting.*
---
## UX
### Project Goals
Show off my skills and attract future employers with a modern and trustworthy website built in html, css and bootstrap. A website that will talk for itself and not just empty words. 

### User Goals
- Get enough information to hire me for employment or projects. 
- Send a form or email. 
- Get a nice overview of my skills to recommend me. 

### User Stories
- As a user/employer, I want the site to talk for itself when it comes to skills and communication. 
- As a user/employer, I want to get served short handed information that quickly explains what the site owner can and how. 
- As a user/employer, I want it to be very easy to get in touch with the site owner. 
- As a user, I want the site to load fast and easy to navigate no matter what device I use. 
### Site Owner Goals
- As s site owner, I want to get in touch with employers.  
- As a site owner, I want to show off my whole spectrum of skills in a simple and easy to understand way. 
- As a site owner, I want to encourage my visitors to contact me. 
### User Requirements and Expectations
#### User requirements:
- Understand the information architecture on the site.
- Directly understand how to navigate on the site.
- A fully functional contact form
- Access the sites content without friction on both desktop and mobile. 

#### User expectations: 
- Get a great overall overview of the site owners skills both visually and technical. 
- A non-bugging site no matter what device the user is using. 
- Clearly and professional impression. 

---
### Design Choices
My main focus with this site is that I want it to reflect me both as a professional and person. I want the design to clearly communicate my visual and technical skills. I want the impression to be serious but almost too simple with a technical twist. The design is based on mobile first and fast loading times. 

### Fonts
I will use fonts from Google fonts because they are flexible and reliable. My main focus is mobile first and I want the fonts to be crystal clear on mobile devices primary. I want it to be a contrast between the fonts I use, one playful and heavy for headings and a lighter for content text with great readability. 

I have been using Raleway in a bold (800,900) variant for all headings and the regular in two different sizes for content. I want the content to be easy to read so the font-size is big and airy. 

### Icons
Icons are from [Fontawesome](https://fontawesome.com/) via their cdn-kit. It's kept very simple and sparingly just to not take focus from the content itself. 
### Colours
**Fonts**: The colors that have been used in fonts are three different shades of blue (#155399;#57A5FF;#3789E6;) and light-orange (#E6A737;). The orange colour is used for the contact section just to make it even more visible. 

**Backgrounds**: For the different sections there are three different colours: Black, white and beige (ededeb).  Focus is on readability and make the content contrast to the background in a nice looking way.

---
## Wireframe
The wireframes are made in [Balsamico](https://balsamiq.com/) both for mobile and desktop. 

- [Wireframe for desktop](assets/wireframes/desktop.jpg)
- [Wireframe for mobile](assets/wireframes/mobile.jpg)
---

## Technologies used
**Language**
- [Html](https://en.wikipedia.org/wiki/HTML#:~:text=Hypertext%20Markup%20Language%20(HTML)%20is,scripting%20languages%20such%20as%20JavaScript.)  For creating content and structure. 
- [CSS](https://en.wikipedia.org/wiki/CSS) For styling the html to the actual design. 
- [Javascript](https://en.wikipedia.org/wiki/JavaScript#:~:text=JavaScript%20(%2F%CB%88d%CA%92%C9%91%CB%90v,%2C%20and%20first%2Dclass%20functions.)  For making the mobile menu collapse with Bootstrap.  

**Tools & libraries**
- [Bootstrap](https://getbootstrap.com/)  For navbar, columns and form. 
- [Git](https://git-scm.com/)  For version control and keeping this project alive.  
- [Github](https://github.com/)  For storing this project in a safe way. 
- [Font Awesome](https://fontawesome.com/)  For using Icons in a safe and easy way. 
- [Google Fonts](https://fonts.google.com/) For using nice looking fonts in this project. 
- [Google Dev tools](https://developers.google.com/web/tools/chrome-devtools)  For testing on various screens and mobile devices on a daily basis.  
- [Lambdatest](https://app.lambdatest.com/)  For testing it on more screens that Google Devtools provide as a complement. 
- [Beautifier](https://beautifier.io/) For final touches on the code formatting. 

---

## Features
###  Features that have been implemented:
- Fixed navigation bar with anchors. 
- Form with name, email, company and textfield. 
- Mailto action when clicking on “Book a meeting” and Email address.
- Link to Linkedin profile opens in a new tab. 

### Features that will be implemented in the future:
- Implement calendly with their own API so it's easy to book a meeting directly on the site. 
- Real showcase projects. 	
- Make menu close after click on mobile.
---
## Testing
Google Devtools has been used to test the site on the following devices:
- Moto G4
- Galaxy S5
- Pixel 2
- Pixel 2 XL
- iPhone 5/SE 
- iPhone 6/7/8
- iPhone 6/7/8 Plus 
- iPhone X 
- iPad
- iPad Pro
- Surface Duo 
- Galaxy Fold. 

All testing has been made manually.

**Contact form**

The contact form has been tested on both desktop and mobile devices and it works well, except the form is not sended. The Email field is required and it reacts when there is no “@” filled in. Tested in various browsers and devices. 

**Contact** 

Email and Book a meeting works correct and opens up in a new mail window. 

**Navigation**

The navigation is tested in Google Devtools devices and different browsers and works correct. 

**Responsive testing & design**

For responsive testing on mobile devices, Google devtools and Lambdatest have been used. 
All devices/screens that Google devtools provide has shown excellent results. 

[Lambdatest](https://app.lambdatest.com/) has been used to ensure that it looks correct on all 56 screens that they provide. I find Lambdatest as a great complement to Google devtools when it comes to testing it on mobile devices. 


For testing the **HTML** and **CSS** [W3C](https://validator.w3.org/) has been used. 
#### Validator results: 
- **HTML Validator**: No errors or warnings to show.  
- **CSS validator**: No errors were found. The document is validated as CSS level 3 + SVG. 
![Validated css](http://jigsaw.w3.org/css-validator/images/vcss
)

**User story testing**
 - *As a user/employer, I want the site to talk for itself when it comes to skills and communication.*
 - - There are no errors or bugs in the site. 

- *As a user/employer, I want to get served short handed information that quickly explains what the site owner can and how.* 
- - The information is very shorthanded on the frst screen you see, then it explaines more and more among the scroll. 

- *As a user/employer, I want it to be very easy to get in touch with the site owner.* 
- - On the first screen there is a Contact button. 

- *As a user, I want the site to load fast and easy to navigate no matter what device I use.*
- - The menu is very clear and easy to use. 

#### Bugs
Among this project, the navigation has been the main problem.  

- **Fixed navigation**: When using fixed navigation combinated with section anchors there is a problem to position the scroll to the exactly correct position. This has been challenging but I find the solution [here](https://gomakethings.com/how-to-prevent-anchor-links-from-scrolling-behind-a-sticky-header-with-one-line-of-css/). 

---
## Deployment
This project is made with Gitpod, using Git and hosting on Github. 
**How I deploy**
1. Logged in on [Github](https://github.com/).
2. Then go to [https://github.com/Carl-Henric/MS1](https://github.com/Carl-Henric/MS1)
3. Clicked Settings in the tab menu above the content area. 
4. Scrolled to GitHub pages-section.
5. Then I choose Master Branch from the source dropdown menu.
6. Clicked to confirm my selection, and then its live. 
 
**How to run this project locally instead**
1. How to clone this project from Github:
2. Go to [https://github.com/Carl-Henric/MS1(]https://github.com/Carl-Henric/MS1) 
3. Click the “Code”-button and copy the http-adress. 
4. Open Gitpod and open a new terminal, terminal → new terminal. 
5. In the terminal, paste the code and press enter. 
---
## Credit

#### Images

All the images that´s been used is from [Pexels](https://www.pexels.com/).
- [https://www.pexels.com/photo/be-brilliant-neon-light-2002719/](https://www.pexels.com/photo/be-brilliant-neon-light-2002719/)
- [https://www.pexels.com/photo/crop-unrecognizable-doctor-with-vision-test-device-3846021/](https://www.pexels.com/photo/crop-unrecognizable-doctor-with-vision-test-device-3846021/)
- [https://www.pexels.com/photo/photo-of-golden-cogwheel-on-black-background-3785927/](https://www.pexels.com/photo/photo-of-golden-cogwheel-on-black-background-3785927/)
- [https://www.pexels.com/photo/man-standing-infront-of-white-board-1181345/](https://www.pexels.com/photo/man-standing-infront-of-white-board-1181345/)


### Snippets that i used from others:
- **Rotation:** https://www.w3schools.com/cssref/css3_pr_transform.asp

- **Scroll margin top:** https://gomakethings.com/how-to-prevent-anchor-links-from-scrolling-behind-a-sticky-header-with-one-line-of-css/

- **Resume Timeline from Mini Project with Bootstrap 4-project on Code institute.**


