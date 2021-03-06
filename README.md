# The Monkees #
## Front-end Web Development Project ##


## Aim ##

The aim of this project was to create and build a front-end only website that has 4-5 pages for the rock band [The Monkees](https://anthonynicklin.github.io/milestone01-TheMonkees/). 
I was provided with content to use which included a video and audio tracks which they wanted fans to be able to play on their website. Other assets they provided where photos of 
the band, album covers and individual band member photos. 

## UX ##

Starting with a mobile first design approach to this project I started creating wireframes for mobile and small screens. I then moved onto creating mockups 
for medium and larger screens. The design of the site is clean, simple but funky in keeping with the 60's style the band has. I kept to a simple colour scheme matching
the main background image that I chose to use. Having a clean cut design, I feel makes it easier for the fan to read and use the website.

Below are user stories that were conducted in order to gain clear goals that needed to be achieved for this website.
1. As a fan I wanted to listen to current and back catalogue tracks.
2. As a fan I wanted to see where and when the band will be preforming.
2. As a fan I wanted to be able to find and book tickets to the bands next gigs.
3. As a fan I wanted to read interesting facts about the band and about each artist.
4. As an event promoter I wanted to hear and preview their tracks.
5. As an event promoter I wanted to see a promotional video of the band.
6. As an event promoter I wanted a way in which I could contact the band for bookings.
7. As an fan I wanted to be able to contact the band to book for my own event.
8. As an event promoter I wanted to check out their social media via links.
9. As a fan I wanted links to their differnt social media pages on different platforms.

The navigation bar is responsive having break points for smaller, medium and large screens. The navigation links disapear on screen width's below 992 pixals and a burger menu icon appears 
top right. When the burger icon is clicked it brings a drop down menu with the navigation links in displayed vertically down the left-hand side. The bands logo continues to be displayed in the 
navigation bar when the navigation bar is collapsed and provides a way back to the home page when clicked on without having to toggle the drop down menu. 

The [Home page](https://anthonynicklin.github.io/milestone01-TheMonkees/) has a great picture of the band performing and has been put as the first image visitors see in order to attract the fan 
to attend one of the bands gigs. Under the bands image is the [Live Dates](https://anthonynicklin.github.io/milestone01-TheMonkees/index.html#live-dates) section which provides a easy way to 
find tickets using the Find Ticket buttons next to each upcoming live date. The [Book Us](https://anthonynicklin.github.io/milestone01-TheMonkees/index.html#book-us) section provides fans or 
promoters with a way to contact the band in order to book them with a neatly laid out and easy to use form.

A promotional video is displayed at the very begining of the [Media](https://anthonynicklin.github.io/milestone01-TheMonkees/media.html) page. This is 
to encourage the fan to see the band play live. Underneath is a neat section of album tracks with album cover images with controls to play a track from each one. Content is provided
next to each album to give the visitor a bit of interest about that album the band is promoting. 

[Meet the Band](https://anthonynicklin.github.io/milestone01-TheMonkees/meet-the-band.html) uses a simple layout so the fan can easly read information about the band and then about
each individual member. 

During the process of developying the site I found that the layout on the [Media](https://anthonynicklin.github.io/milestone01-TheMonkees/media.html) and [Meet the Band](https://anthonynicklin.github.io/milestone01-TheMonkees/meet-the-band.html) 
pages did not look great across all devices. I decided to change the layout and reposition images and content but, still keeping the design theme consistent. These pages now look much 
more appealing across all screen sizes and devices giving a better user experience than sicking with the orignal layout in the wireframes.

## Features ##

Features on this website are:

* On every screen size the logo of the band is presented and is also a link to the [home page](https://anthonynicklin.github.io/milestone01-TheMonkees/).
* The links in the navigation when hovered over turn grey to indicate which link the fans cursor is over.
* Navigation links are active meaning the link will stay black when the fan is on that page.
* When hovering over any links the cursor changes from a pointer to a hand.
* On every page in the footer there are links to the band's social media pages to the respected social media platforms.
* When hovering over a social media icon, the icon changes colour to that social media platforms colour.
* For each [live date](https://anthonynicklin.github.io/milestone01-TheMonkees/index.html#live-dates) there is a 'find ticket' button that takes them the respected page on ticketmaster.com.
* The [booking form](https://anthonynicklin.github.io/milestone01-TheMonkees/index.html#book-us) lets the fan input their information and gives an error message if the data is not in the correct format or missing.
* Video and audio on the [media](https://anthonynicklin.github.io/milestone01-TheMonkees/media.html) page have controls that the fan can use to fully control the video and audio.

## Technologies Used ##

Below are a list of the programming languages, technologies and frameworks used for this website.

* HTML5
* CSS3
* Markdown
    * Used to write the README.md file.
* [Bootstrap4.3.1 framework](https://getbootstrap.com/)
    * The website uses boostrap framework for it's grid system, pagelayout, button styling and responsive navigation bar.
* [Cloud9IDE](https://aws.amazon.com/cloud9/)
    * Cloud9 was the IDE used to write the code for this website.
* [MarvelApp](https://marvelapp.com)
    * This was used to design and create the wireframes for this project.
* [Google Fonts](https://fonts.google.com/)
* Git
    * Version control
* [GitHub](https://github.com)
* [Font Awesome](https://fontawesome.com/)
    * For social media icons and Glyphicons
* Google Chrome Developer Tools
* Firefox Inspector
* Safari

## Testing ##

I conducted testing across different platforms and web browsers in order to make sure the website worked correctly, and
looked great across each one. I also asked friends and family to test across their own devices and to give me honest opinons and feedback.

Platforms:
* Samsung Galaxy 8
    * Google Chrome
    * Firefox
    * Samsung web browser
* iPad Mini
    * Google Ghrome
    * Firefox
    * Safari
* MacBook Pro
    * Google Chrome
    * Firefox
    * Safari
* Ubuntu 18.0
    * Google Chrome
    * Firefox
* Windows 10
    * Google Chrome
    * Firefox
    * Mircosoft Edge
    * IE 11

Manual testing was conducted to ensure the user story objectives where achieved.
1. Audio
    * Click on "Media" page.
    * Click on audio control bar to hear and control music.
2. Book tickets
    * Scroll down on home page and also use the navigation link to "Live Dates" section.
    * Click on "Find Ticket" in order to book tickets for that event. This opens up a new tab in browser and directs you to the booking page for that gig.
3. View promotional footage
    * Click on "Media" page.
    * Click on video control bar to view and control footage.
4. Book the band
    * Scroll down and use navigation link to "Book Us" section.
    * Try to submit the empty form and verify that an error message about the required fields appears.
    * Try to submit the form with an invalid email address and verify that a relevant error message appears.
    * Try to submit the form with an invalid telephone number and verify that a relevant error message appears.
    * Try to submit the form with all inputs valid.
5. Social Media links
    * Hover over each social media icon. Each icon should change colour to the respected social media platforms colour.
    * In the footer of each page click on each social media icon to be redirected to the respected site and open in a new tab in the browser.

I reached out to fellow students on Slack to view my website and test. A lead mentor found a major problem with the responsive
aspect of the website. Even though the website looked correct on small devices, when adjusting a web browser on a desktop below 400 pixals there was huge
overflow. This pointed out I had not applied the mobile first approach correclty. I did more research on mobile first design and implementation and went 
back over notes and lessons. To correct the fault I had to rewrite 60% of my style.css file. 


## Deployment ##

The website was created using Cloud9 IDE using Ubuntu with BASH. Git was used for version control and pushed to a repository hosted on 
[GitHub](https://github.com).

The website is deployed using GitHub pages [The Monkees](https://anthonynicklin.github.io/milestone01-TheMonkees/)

## Credits ##

### Content ###
Information about the band was taked from a number of sources listed below:
* [Wikipedia](https://en.wikipedia.org/wiki/The_Monkees)
* [The Monkees](https://www.monkees.com/)
* [Biography - The Monkees](https://www.biography.com/people/groups/the-monkees)

Please note some content is made up as I did not want to write the same information that other students would come across and possibly write up.

### Images ###
Main background image used was sourced under free commercial license from [Pixaby](https://pixabay.com/en/red-abstract-spiral-2829985/).
Images of band, Monkees logo and artists where provided by Code Institude.

### Media ###
Audio tracks and video was provided by Code Institude.

