# User Centric Frontend Development Milestone Project

This is a website designed for the 1960's band 'The Monkees' to help promote their social media and availability for booking events to new and potential fans alike. Also including a back catalogue of their music. 


## UX

This project is aimed at existing fans of The Monkees who may be of the older generation. I have attempted to keep the design and interactivity simple and intuitive enough that anybody can make sense of it and make use of the site. 
The site is also aimed at newer potential fans who may be of a younger age group than that of the existing fans. I have attempted to keep a modern sleek design so as to be appealing to a younger audience, following key existing trends in order to do so. 

### User Stories

**Booking Service**

- As a potential customer and fan, I want to be able to book the band for an event (epic)
  - As a potential customer and fan, I want to be able to see pricing prior to booking
  - As a potential customer and fan, I want to be see when the band is available
  - As a potential customer and fan, I want to be able to contact someone to discuss the booking arrangements

**Back Catalogue**

- As a fan or potential fan, I want to be able to view existing work of the band (epic)
  - As a fan or potential fan, I want to view music videos made by the band
  - As a fan or potential fan, I want to listen to music made by the band
  - As a fan or potential fan, I want the content to be easy to find and access

**Latest content**

- As a fan or potential fan, I want to be kept up to date with what the band have been doing recently (epic)
  - As a fan or potential fan, I want to see content from recent performances
  - As a fan or potential fan, I want to know what performances the band has planned in the future

**Social Links**

- As a fan or potential fan, I want to be able to easily find and access the bands social media
- As a fan or potential fan, it would be easier to be able to follow the bands social media from the website

**Who we are**

- As a potential fan, I want to learn about the bands history (epic)
  - As a potential fan, I want to learn more about the band members
  - As a potential fan, I want some insight as to why I should become a fan

**Newsletter Form**

- As a fan, I want to be able to stay in the loop with the latest news relating to the band
- As a user, I want to be easily be able to navigate to a sign up page

### Planning 

Wireframes and other documentation is stored in the [Planning Folder](planning)


## Features

### Existing features

- Booking form: Allows users to register interest in booking the band for an event by filling out a form
- Contact details: Allows potential customers to contact the Band to discuss an existing booking, make an enquiry or discuss billing via telephone or email by displaying contact information on screen
- Viewable back catalogue (audio/video): Allows fans and potential fans to view media created by the band by watching videos or listening to audio
- New content/Latest content: Allows fans, potential fans and customers to keep up-to-date with the lastest content created by the band via a link to the bands youtube channel
- Links to social media: Allows fans, potential fans and customers to keep up-to-date with the lastest information and content created by the band by taking them to the bands various social media via buttons on screen
- Newsletter sign up Form: Allows customers to sign up for a regular newsletter by filling out a short form

### Features ideas yet to be added

- Schedule of future events with links to ticket sales
- Live news feed for Band related news and events
- Pricing chart for the booking section
- Band availability visible with booking form
- 'Subscribe' button so users can subscibe/follow band social media without leaving page


## Technologies Used

- [Bootstrap version 3.3.7](https://getbootstrap.com/docs/3.3/getting-started/)
  - The project uses bootstrap for a template for styling and the bootstrap grid system
- [Font Awesome version 4.7.0](https://fontawesome.com/v4.7.0/)
  - Font Awesome has been used for the glyphicons throughout the site 
- [Bootstrap JavaScript version 3.3.7](https://getbootstrap.com/docs/3.3/javascript/)
- [Bootstrap JQuery version 3.2.1.min](https://getbootstrap.com/docs/3.3/javascript/)
  - Both JavaScript and JQuery have been used for the navbar and modal included in the site


## Testing

All testing completed on Safari and Google Chrome at both mobile and desktop size on macbook pro and iphone 7 Plus. Unable to see difference between browsers tested on.

1. Booking Form:
 - Go to the 'Booking' page
 - Attempted to submit an empty form
 - Attempted to input invalid email format
 - Attempted to input alphabetic characters into the 'phone number' field
 - Completed form and checked there was no error message

2. Contact section responsiveness:
 - Go to the 'Booking' page
 - Check the contact information is readable on all resolutions/devices

3. Back Catalogue:
 - Go to the 'Music' page
 - Attempted to play video file
 - Attempted to play audio file
 - Tested use of the audio/video controls
 - Ensured cover images and content was visible/audiable on all resolutions

4. Latest content:
 - Go to the 'Music' page
 - Checked that the youtube link was visible on all resolutions
 - Tested link to ensure it opened new tab and took user to the youtube page

5. Social Links:
 - Go to the 'Home' page
 - Test all social media links in header and footer to ensure new tab is opened and appropriate page is loaded
 - Cycled through every page and repeated test

6. Band information page:
 - Go to the 'The Band' page
 - Hovered each image to ensure animation played
 - Checked to see all text stayed within parent image
 - Ensured all text was legible and visible at all resolutions
 - Tested between desktop and mobile to ensure information is readable and user friendly on all devices

7. Newsletter Form:
 - Go to the 'Home' page
 - Tested submit button with empty form to ensure required fields were functioning correctly
 - Tested submit button with complete form to ensure it was successful
 - Attempted to input invalid email format to ensure data type is correct
 - Tested modal button on smaller resolutions to ensure modal loads and form works as per testing above

Encountered various bugs while testing:

- Bug found when testing 'band member' information page where the image was scaling at smaller resolutions to fit the text overlay from larger resolution size. This was causing the cirular images to scale more vertically, causing an oval shape skewed image.
- Found that at smaller resolutions, some of the Form labels on the booking page were extending to two lines, causing the form the go out of alignment. 
- Found issue whereby the background image on the 'The Band' page would not scale vertically enough to fit the band member images and therefore leaving an undesirable cut off with the background. Only visible at certain resolutions due to the scale set to the viewport height.
- Encountered problem where the contact information text on the 'Booking' page was sized as described for the extra small devices, even on the larger resolutions.


## Deployment

In order to deploy this project, regular commits were made to the Github repository and then using Github pages I was able to deploy the website. No apparent difference between development and deployed builds.

I have only used one Git branch to develop and deploy this project. 

## Credit

### Content

- Text for the 'Music' page was taken from the [Daydream Believer Wiki](https://en.wikipedia.org/wiki/Daydream_Believer)
- Text for the band and band members information was taken from the following:
  - [The Monkees Wiki](https://en.wikipedia.org/wiki/The_Monkees)
  - [Davey Jones Wiki](https://en.wikipedia.org/wiki/Davy_Jones_(musician))
  - [Micky Dolenz Wiki](https://en.wikipedia.org/wiki/Micky_Dolenz)
  - [Michael Nesmith Wiki](https://en.wikipedia.org/wiki/Michael_Nesmith)
  - [Peter Tork Wiki](https://en.wikipedia.org/wiki/Peter_Tork)

### Media

- The Daydream Believer Cover image was taken from [Flickr](https://www.flickr.com/photos/cdrummbks/8265470236/)
- The Monkees Logo image was taken from [Band Logo Jukebox](https://www.bandlogojukebox.com/blog/2017/12/4/m1-the-monkees)
- The 'Music' page background image was taken from [Wikimedia](https://commons.wikimedia.org/wiki/File:The_Monkees_May_1967.jpg)

### Acknowledgments

Inspiration was taken from the following: 

- [The Kinks Official Website](https://thekinks.info/news/)
- [The Rolling Stones Official Website](http://www.rollingstones.com/)
- [The Who Official Website](https://www.thewho.com/)
- [The Beegees Official Website](http://www.beegees.com/)