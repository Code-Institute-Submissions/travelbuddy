![TravellBuddy logo](https://github.com/redlik/travelbuddy/blob/master/assets/images/tb_logo_flat.svg "Travel Buddy logo")
# TravelBuddy
TravelBuddy is a portal for people looking for organised experience tours at locations around the world. It also allows people providing such an experience to become a part of the TravelBuddy community and have an exposure on the site with their programme, pricing and duration of the tours.
## UX
### User Stories
The main target for the site are people looking for organised tour experience. TravelBuddy believes the best tour experience is provided by locals and their expertise in their home towns. Each tour listed is unique and contains many attractions so the expected feedback is always positive.  
The second group of users that TravelBuddy would like to attract are people providing tour experiences. Dedicated page lists the benefits of joining TravelBuddy and includes a registration form that collects the most important information about the person wishing to join the community. Each participant is thoroughly vetted and only accepted when their knowledge and experience meet TravelBuddy high standards.
### Structure
#### The site is broken down into main sections: 
1. Homepage with call to action, selection of locations and user testimonials.
2. Location subpages - each location lists details, price, and a booking button.
3. Become Host - a page dedicated to people willing to join Travel Buddy.
4. Contact page with contact form and location map.
This breakdown allows visitors to quickly get an idea what the site is all about the move to the section they’re interested the most.
#### Each page is broken into 3 main parts: 
1. Navigation bar, clearly showing where the user is at the site (bolder font for active page).
2. Main section - this is where the main content of each page is displayed in clear, organised fashion using headings, separation lines or different backgrounds.
3. Footer where we link again to individual pages, social media links and small version of the logo to go back to index page.
### Skeleton
The wireframes were created prior to coding process using Balsamiq Mockups desktop application, both for mobile and desktop layouts.
- [Homepage on Desktop][1]
- [Location on Desktop][2]
- [Become a Host on Desktop][3]
- [Contact on Desktop][4]
- [Homepage on Mobile][5]
- [Location on Mobile][6]
- [Become a Host on Mobile][7]
### Surface
The main font used on the website is “Montserrat” and some headings use “Playfair Display” to stand out more. Both fonts are linked from [Google Fonts][8] library in the stylesheet file.  
I use simple, two colour palette on logo, buttons and backgrounds to keep the site consistent and matching company brand colours.
## Features
### Existing Features
The site welcomes the user with an effective call to action and the list of most popular locations directly below. To add credibility to the service I’ve listed a selection of user’s testimonials to make sure new visitors will see TravelBuddy as a trustworthy services and be more inclined to make the first booking.  
Each available tour has its own separate page where I list the price, duration, short description and list of attraction. I’ve also included a selection of photos to help a user to make a booking.  
I’ve also included a separate page for people wishing to join TravelBuddy as a host. I’ve listed main benefits of becoming a host at TravelBuddy and a registration form to collect the details about the person. I’ve made sure the form has couple of required fields to avoid sending incomplete submissions.
The last page of the portal is the contact page where I provide a simple query form and a fictional office location marked on Google Maps in Dublin.
### Features Left to Implement
Once I become accustomed to using Python with its frameworks I’d like to create a true travel hosting portal with user registrations, members logins and search functionality. 
## Technologies Used
The site is built using HTML and CSS. It is based on Bootstrap framework.
## Testing
The site was tested thoroughly using main browsers: Google Chrome, Mozilla Firefox, Apple Safari and MS Edge using built in Developer Tools. I’ve tested all simulated devices (mobile phones, tablets) and large desktop windows. I’ve also tested the site using various physical devices - iPhone 11, Samsung Galaxy Prime, iPad Pro and various desktop computers (iMac, MacBook and Windows PC). I’ve used flexible units (em, rem, %) to make sure the site scales properly without using too many media queries in my stylesheet.  
During the testing phase the most common issues were related to sizing, items not looking correctly at different screen resolutions. Thanks to extensive selection of Bootstrap utility classes I was able to fix most of them without the need to create extra custom classes.  
I’ve made sure both forms do not allow submissions without missing information using ‘required’ parameter on selected fields. Thank to Bootstrap’s built in validation the forms will not allow incorrect data passed in email and phone fields.
The site was validated using both HTML and CSS validators and all pages passed the tests successfully.
## Deployment
The site is hosted at GitHub pages, using directly the master branch.  In order to make the pages visible on GitHub pages I had to turn on the function at the Settings tab inside my repository. The site is being updated automatically each time there’s a new commit uploaded.  
In scenario when somebody wishes to clone the repository it can be done with by downloading the zip file containing the whole repository or use `git clone  https://github.com/redlik/travelbuddy.git` command in the terminal window. The site can be run locally without a need to use a web server, each page will open in any browser installed.
## Credits
The site content was created especially for the purpose of the project with a help from friend of mine, Sean Powers, the owner of [Irish Experience Tours][9].
Photography and vector graphics used on the website come from royalty free websites:
- [Unsplash][10]
- [Pixabay][11]
- [Freepik][12]

[1]:	wireframes/homepage-desktop.png
[2]:	wireframes/location-desktop.png
[3]:	wireframes/host-desktop.png
[4]:	wireframes/contact-desktop.png
[5]:	wireframes/homepage-mobile.png
[6]:	wireframes/location-mobile.png
[7]:	wireframes/host-mobile.png
[8]:	https://fonts.google.com
[9]:	https://irishexperiencetours.com
[10]:	https://unsplash.com
[11]:	https://pixabay.com/
[12]:	https://www.freepik.com/
