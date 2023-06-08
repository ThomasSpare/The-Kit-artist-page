# The Kit - On the Road with the fans
##

The Kit is a DJ duo of two girls. The band is touring heavily 
and they want a site that si like a meeting place for fans. 
Their fanbase is growing rapidly as they tour the world and their 
spectacular shows are becoming infamous among fans.
A page where listeners can discover them, a fan page where fans
can follow them, stay updated, buy merch or support them
on channels like Mix-cloud (a sort of youtube for DJs where 
artists earn money from subscribers).

Fans will come back to the site to stay updated on what´s 
happening - so the news section is where they will find 
recent tour photos - some taken by fans, comments from fans, 
upcoming releases and exclusive content not found anywhere else. 
The client want the site to look good with high quality photos
preferably live photos from shows they had. 

---

![Preview after build](https://github.com/ThomasSpare/The-Kit-artist-page/blob/de1148b9ee267ce4e80dfc15a8dc66c7c8729513/documentation/responsive.jpg)

----

## Wireframes
![Wireframe of page before build](https://github.com/ThomasSpare/The-Kit-artist-page/blob/main/documentation/wireframes/Wireframe%20main%20page.png)




---

## Features


**Zoom feature**


Prior to starting build of the site I did some research on similar
artists webpages and found a style I liked where the background on
all pages consist of high-res photos that will start to zoom in
once the visitor opens the page.
[Reference website: Carl Cox](https://carlcox.com/)
Using media query the same effect could be possible on smaller devices.
I also liked the style of menu from Carl Cox site on mobile devices 
so that was something I wanted to incorporate in the build.
Unfortunatly build a hamburger navbar was to complicated at my level.

Using zoom is an effective yet tasteful way to present photos for the user. 
As these photos are from live shows the goal is to get the users more
interested in visiting a show.

The page consist of 4 pages, they are accesscible through the navigation
bar at the top of each page.

The pages are:
* Main page
* News 
* Merch
* Support
* Gallery


**The Navbar**
This is a fully responsive navigation that appears on every page. On the intro page the logo appears bigger and stationed on the left side for a more effectful display of the background image. On the main page there is a text area up to the left displaying where the next show will be. The logo act as a return to homepage in the navbar.

**Spotify player**
On the top main page is a spotify player that the user can press play and hear the bands most popular track.
The user can also from this player follow the band on spotify. I did some research about tweaking the spotify
widget. The widget can be tweaked in many ways using spotify developer tools to fit different purposes.

**Merch**
In the merch section the user can look at merch items designed by the band. In the form at the bottom they can 
write a request for certain items.

**Gallery**
In the gallery below are photos that the user can hover over to enlarge them or press a photo to open it 
in a new tab. This section can be filled with more photos later on.
![Gallery section](https://github.com/ThomasSpare/The-Kit-artist-page/blob/2b84773be2909c61daa7f26ef5c2fa8c40dbbb73/documentation/gallery.jpg)

**News section**
In the news section below are two columns. The first column is a fan oriented column displaying photos and comments mostly
from fans. The right column is where the band can post news and share what is going on like upcoming releases or
a new design of a merch item.
![News section](https://github.com/ThomasSpare/The-Kit-artist-page/blob/2b84773be2909c61daa7f26ef5c2fa8c40dbbb73/documentation/news-page.jpg)

**Support section**
This where links to the bands platforms are gathered. By clicking them the user opens a new tab to the bands user profile on the choosen platform.




---


# User stories

## Client goals
* To be able to share news and important information (like next gig, new releases, special events, new products)
* A place to inspire the audience and encourage them to visit a live show
* To nurture the connection with fans
* A way for fans to discover and follow the band on digtal platforms where the band is active

## User goals

**First time visitor**
* I want to find out more about the Kit and see live photos
* I want to read news about what is coming up next
* I want to see where the band is active and explore links to visit their profiles

**Returning visitor goals**
* I want to stay updated about the band
* I want to see footage from a live show near my location
* I want to see live footage from a show I went to
* I want to see where the band is active and use links to stay updated on their platforms

**Frequent visitor goals**
* I want to stay updated about the band
* I want to see if the band choose a photo I took from a show
* I want to see if a comment I sent to the band was posted

---
## Design

I wanted the main page to have a large area for photos, so I
thought a transparent navigation bar would be good on this page. In the gallery page below the footer will show up fixed in vertical on the left side when scrolling on larger screens, on smaller devices its fixed at bottom of screen. I made it vertical on only this page as this page can be quite long before reaching the bottom with added photos after a while.

The navbar from the outset was supposed to have non-transparent bakground and I wanted to use the bands logo as a home button in the navbar. I designed the logo myself using the app photoleaps design function on my iphone. The logo will show up on larger screens but only the index page and will not display on smaller screens. In the index page at the bottom I also used a customized css animation called pulse for the merch image to draw attention to it. If the visitor clicks the T-shirt image they will be forwarded to the merch page. 

![The kit logo](https://github.com/ThomasSpare/The-Kit---artist-page/blob/main/documentation/graphic/The%20Kit%20LOGO.png)

For background I used a gradient from uiGradients.com called pacific dream
![Collor Pallette](https://github.com/ThomasSpare/The-Kit-artist-page/blob/d2f3fcffaeab17ee089431b4fbf5c116e6926d87/documentation/pacific-dream.jpg)


---

## Future Implementations

**The Merch section**
The Merch section could benefit from being more developed and automated. 
Due to time constraints and the fact that I never before coded a webpage before, 
the merch section is a bit rudimentary. Of course the visitor should be able to purshase
and pay for merch in one instant.

**Heavy maintance**
A site like this would be rather maintance heavy. As this site in a live setting would need to be constantly updated
with news, fan mail, merch and photos from recent shows. So ways to make updating easier would be a good idea.

**Communication**
It would also be a good idea to have some sort of email form when trying to contacting
the band instead of just open the email provider in a new tab, one could have a popup
form that the user can fill out on the site and upload photos directly on the page.


---

## Accessibility ##

I have used alt text on images and the fonts I picked on google fonts was
choosen with the purpose of making reading more easy. Perhaps larger fonts
could be used on the main page in the column and the news section where it is
quite small.

## Technologies used ##

**Languages Used**
HTML, CSS

**Frameworks, Libraries & Programs Used**
Balsamiq Wireframes, Microsoft Paint, Adobe illustrator, Github, Gitpod, Photo Leap (mobile application)

## Deployment ##

The site was deployed to GitHub pages. The steps to deploy as follows:

1. Final gitpush from Gitpod
2. In settings in my github repository
3. Select The branch to deploy
4. The site deployed succesfully

The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html

---


## Debugging ##

At first the pages did not work well when testing in google dev tools. The sides of the page on smaller devices
shrank to half the width and I did not undertsand why. Finally I found the problem had to do with using the css 
command transform: scale(%) on the main background photo. I accidently had put the header image inside the <head> element. 
I fixed this on all pages and this improved translation to smaller devices.



## Testing
  
  **All tests can be found in the documentation folder in my repository**
  [Documentation](https://github.com/ThomasSpare/The-Kit-artist-page/tree/main/documentation)

**Responsive testing**
Below are links to screenshots when performing test on an Ipad Mini
  
[ipad test screenshots](https://github.com/ThomasSpare/The-Kit-artist-page/tree/main/documentation/test/responsive/Ipad)
  
And test on Iphone 12 pro
[Iphone 12 Pro test](https://github.com/ThomasSpare/The-Kit-artist-page/tree/main/documentation/test/responsive/Iphone%2012%20pro)

  
  

## Lighthouse test
  When conducting test in google dev lighthouse I found errors on the main page
  these where:
  * Some Imgages dont have fixed width or height
  * missing specified charset in head, or to late
  * Some images are missing alt="" text
  
 After fixing these errors I could see the performance and accessibilty went up in the green.
 And after some tweaking the score looked like this:
  ![Lighthouse for mainpage](https://github.com/ThomasSpare/The-Kit-artist-page/blob/main/documentation/test/responsive/lighthouse/Lighthouse%20test%20main%20page.jpg)
 [Lighthouse tests all pages](https://github.com/ThomasSpare/The-Kit-artist-page/tree/main/documentation/test/responsive/lighthouse)
  
  I only tested for desktop devices. I went on after this and improved more on the code for improved accessibilty
  but have not documented it yet.
  
  --
  
  ## W3C Validator
  
  I tested the sites pages in W3C checker, using my url for the live pages. The test with W3C revealed several erros
  in code. Many of the issues had to do with Duplicate of code or wrong input of code. So a more thorough debugging
  of the code with w3C as a reference would need to be carried out. 
  
  --
  
  **Manual Testing**
  
  I also manually performed test on my own iphone 12 by looking on the deployed
  site. I found some issues with the support section that could be improved visually.
  Other then that I could navigate the site, fill in the forms on the main page
  and in the merch section and saw a submit form message
  when I correctly submited my email.
  
  **Inter explorer**
  I tested the deployed site in Microsoft Edge browser
  Version 110.0.1587.63 (Official version) (64 bit)
  Every function performed as on google chrome browser
  Version 110.0.5481.178 (Official version) (64 bit)
  
  
  
  ## Credits:
  
  Thanks to Kera Cudrow for excellent walkthrough of the readme section.
  
  Thanks to my mentor Brian O'hare for insights and invaluable pointers 
  
  
  













