
# SHADOW RIVER FARM

Link to Live project here. [Here](https://tetapehta.github.io/Shadow-River-B-B/)

This is a website for Open farm and B&B in Annascaul, Co.Kerry. The website is designed to be responsive and accessible on range of devices. It allows visitors to find out more about Shadow river and the surrounding area.

Below You can find a link to Am I responsive page that shows the website on different devices.

![Am-I-responsive](documentation/am-i-responsive.png)

## User Experience (UX)

   ### User stories
    
      - #### First time visitor Goals
         
        1. As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the Accommodation and Open farm.
        2. As a First Time Visitor, I want to be able to easily navigate throughout the site to find content.
        3. As a First Time Visitor, I want to look for testimonials to understand what their users think of them and see if they are trusted. I also want to locate their social media links to see their followings on social media to determine how trusted and known they are.

     -   #### Returning Visitor Goals

        1. As a Returning Visitor, I want to book my stay.
        2. As a Returning Visitor, I want to find out more about the Cafe on the Farm.
        3. As a Returning Visitor, I want to see updates on the offer..

## Design 
     
     - #### Colour Scheme
       - Main color used is #rgba (58, 58, 58). Slate grey is main masonary color that is used on the farm Therefore the theme flows from real enviroment into the webpage.The guest easly connects the real-life color to website presenting the farm.

     - #### Typography
       - The Lora font is the main font used throughout the whole website with Sans Serif as the fallback font in case for any reason the font isn't being imported into the site correctly. Lora is an elegant but readble font from small to large font size, so it is both attractive and appropriate.

     - #### Images
       - Images are important to show what the guest can expect in real life when visiting Shadow river Farm.

     - #### Wireframes
       - Balsamiq is used for wireframes. Links below.


## Features
      - Responsive on all devices

      - Ineractive elements

### Languages used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libreries, Programes Used

  1.  [Google Fonts:](https://fonts.google.com/)

    - Google fonts were used to import the 'Lora' font into the style.css file which is used on all pages throughout the project.
 
  2.  [Balsamiq:](https://balsamiq.com/)

    - Balsamiq was used to create the wireframes during the design process. 
![home](documentation/wireframe1.png)
![gallery](documentation/wireframe2.png)
![book](documentation/wireframe3.png)

   3. [GitHub:](https://github.com/)

    - GitHub is used to store the projects code after being pushed from Git.

   4. [Font Awesome:](https://fontawesome.com/)

    - Font Awesome was used on landing & gallery page of the website to add icons for aesthetic and UX purposes.

## Testing

    - The W3C Markup Validator and W3C CSS Validator were used. Every page was inspected to ensure there were no syntax errors in the project.
    
 [W3 Markup Validator](https://validator.w3.org/) 

![My-results](documentation/html-markup-result.png)

    - My CSS was showing numerous errors. 

 [W3-CSS-Validator](https://validator.w3.org/#validate_by_input) 

![CSS-error-one](documentation/css-error1.png)
![CSS-erroe-two](documentation/css-error3.png)
![CSS-error-three](documentation/css-error4.png)

    - I have succesfuly applied all the suggested corrections.

![My-results](documentation/css-validator-result.png)

## Furder Testing

   - The website was tested on Google Crome and Mozzila browser.
   - The website was viewd on wariety of devices.
   - Lighthouse was used for page performance.
   - Desktop:

![Lighthouse-desktop](documentation/lighthouse-desktop-home.png)

![Lighthouse-desktop-gallery](documentation/lighthouse-desktop-gallery.png)

![lighthouse-desktop-contact](documentation/lighthouse-desktop-contact.png)
    
   - Mobile:

![Lighthouse-mobile](documentation/lighthouse-desktop-home.png)

![Lighthouse-mobile-gallery](documentation/lighrhouse-mobile-gallery.png)

![Lighthouse-mobile-contact](documentation/lighthouse-mobile-contact.png)

   - Applied fix to Contact media queries:

![Lighthouse-mobile-contact-fix](documentation/lighthouse-%20mobile-after-1st-fix-media-queries..png)


### Failed code: 

1. -  Media queries between 950px and 1200px do not apply correctly.

       FIXED CODE: Error solved by removing the padding between conteiners and not inside like previously tried. This resulted in correct responsive media query.

2. - Gallery Images not showing in Mozzila browser.

       FIXED CODE: Error solved by transforming JPG format too WEBP format. Gallery displays correctly.

3. - Slide buttons not displaying on MAC device; Crome and Firefox browser. Screens max size 950px and down.

       FIXED CODE: Upon inspection of my commits, I have noticed that I have deleted CSS code that targeted Slider navigation. After 
       watching the Youtube tutorial one more time, I have succesfully applied the changes. 

  - MAC CROME:
     
![Missing-nav-bar-on-MAC-Crome](documentation/screenshot-mac-crome-missing-nav-bar.png)

  - MAC FIREFOX:

![Missing-nav-bar-on-MAC-firefox](documentation/Screenshot-mac-firefox-missing-nav-bar.png)

  - Fixed CSS:

![Missing-nav-bar-fix-CSS](documentation/screenshot-mac-fixed-css.png)





4. - Form Input was not applying correcty. The values of Imput were displayed incorrectly. 

   * FIXED CODE: Changed From 'action'to form 'formdump' as advised by my mentor. Changed method from 'get' to 'POST'. Values display correctly.

3. - Low Lighthouse performance for mobile.

   * FIXED CODE: Compress all Images with Tiny Ping.com. Lighthouse score improved from 75 to 89 on Performance.
  

## Credits 

### Code 

 - All content written by developer.

 - Sample README.md from Code Institute was used as template for this document.

 - Gallery section was build following the tutorial: https://www.youtube.com/watch?v=McPdzhLRzCg

 - Contact form was adopted from a felow student on SLACK: https://roddersnz21.github.io/project-1/

### Media

- Images used on Home and Book page were created by Eva Veber for developer.
- Images for -WINDOW INTO DINGLE PENINSULA- were created vy Florian Walsh.
- Images for -TAKE YOUR MEMORIES HOME- were created by Eva veber.

### External Links

- Social media icons link to Social media accounts of Shadow River Farm.
- Links to external websites in Gallery link to Photographers personal websites.

### Aknowlegments 

-   My Mentor Brian Macharia for continuous help and insightfull feedback of my work on mentor sessions.

-   Tutors at tutor support at Code Institute for their support.

-   Peer support on Slack and Stand Up meetings with Irene.



------



---




[def]: documentation/screenshot-mac-crome-missing-nav-bar.png