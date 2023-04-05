# Frusciante Facts V1

(For details on the updated site, please scroll down to heading "Frusciante Facts v2")

Frusciante facts is a page made to create a historical database for American musician John Frusciante, covering facts about his career, discography and musical equipment.
Users of this site will able to discover facts about his life, explore his discography and find out what musical gear (guitars, synthesizers etc) has been used on famous tracks and performances. This last section will allow the user to recreate the sounds of songs/performances that they like. I thought it also has potential for affiliate links as pages of gear or music can have direct links on them to find that specific piece of gear or song/album.

## Navigation:

- The navigation bar starts from the left, first featuring the name of the site “Frusciante Facts”, which acts as a homepage button when clicked
- The three links on the right of the page take you to different pages. The “About” leads to a page featuring a brief biography of the artist. The “Discography leads to a gallery of John’s album art, which when clicked, leads you to an individual page for that album, as well as the albums tracklisting, release date and a link to listen to the album (all of these links lead to user made playlists of each album which all feature uploads from the official Chili Peppers YouTube page rather than a 3rd party upload which could be taken down. The last section, “Gear”, features equipment used on tour by John, which appeals to those who want to recreate his sound
- The bar has been laid out the way it has to accommodate for the users visit. For example, the about section is for those wanting to know about the artist, the discography page is set out for the use to discover or rediscover the artists back catalogue and the gear page caters for the more knowledgeable user who may already be aware of the artists story and or/music and want to know how themselves can recreate such sounds. It can also cater to a newer user who lets say has learned about the artist through the site as well as heard some of the music from the external links and are inspired by what they have heard and want to make similar music

![Nav Bar](https://github.com/ArunHTV/portfolio-one/blob/72f7110b243ad1ae58c1d996032966b96af71596/markdown-images/nav.png?raw=true)


## Header

- 	The header on the homepage features the text “ Welcome To Frusciante Facts!”  and a brief description of the page to give the user a clear insight on the purpose of the site

![Header](https://github.com/ArunHTV/portfolio-one/blob/72f7110b243ad1ae58c1d996032966b96af71596/markdown-images/header.png?raw=true)


## About 

- 	A page giving a brief history about the artist. Due to time constraints, this information has been sourced from WikiPedia as a placeholder which I have also credited on the page for full transparency 
- 	This page, when fully finished, will be a more informative page to give the user a better understanding of the artist and their story, whereas at the moment it is more something more along the lines of an appetizer

![About](https://github.com/ArunHTV/portfolio-one/blob/72f7110b243ad1ae58c1d996032966b96af71596/markdown-images/about.png?raw=true)


## Discography

-	A page that features a chronological flow of the artists album art that leads to a page featuring that albums release date, tracklist and an external link leading to an audio playlist that allows you to listen to that albums
-	Due to time constraints , I have only added John’s work with the Chili Peppers thus far but have adhered to a column layout with shared code for the individual album pages so these can be added at a later date. 
-	As mentioned, I haven’t covered every album yet so I have kept the image sizes on this page quite large to avoid the page looking bare and to catch the users eye

![Discography](https://github.com/ArunHTV/portfolio-one/blob/72f7110b243ad1ae58c1d996032966b96af71596/markdown-images/discography.png?raw=true)

![Discography2](https://github.com/ArunHTV/portfolio-one/blob/72f7110b243ad1ae58c1d996032966b96af71596/markdown-images/album.png?raw=true)



## Gear

-	The “Gear” section of the website will feature equipment John has used on certain albums/performances, as well as the sources of the information for full transparency

![Gear](https://github.com/ArunHTV/portfolio-one/blob/main/markdown-images/gear.png?raw=true)


## Bugs

- At the moment, I'm having a bit of an issue using media queries to make the site look better in mobile so I'm currently looking into a fix for this

## Testing

- Each time a new HTML page has been made, I have used the HTTP Server on GitPod to make sure the page leads you to the right place. For example, I had originally had an issue opening the Gear page from the Discography page. When I searched the HTML for causes, it seems that there was a typo in the href for the gear page in the Discography html. When this was corrected, it took me to the correct page.

- The site was also tested for smaller screens. However, I was having an issue when trying to center my headings and text for a mobile page. While I had been testing on a browser window a lot so I knew how each internal and external link would work, mobile testing was left a little bit late. I will revise into media queries for the next submission and potential resubmission of this project.

## Validator Testing

- Each  individual page has been put through W3 Validator and all edits have been made to the HTML so there are no real issues other than the discography page where it has asked for a title for one of the sections
- Currently no CSS errors. Only one was flagged in the text area whhen using the W3C CSS Validator and this was quickly amended

## Deployment

- This site was deployed by going to the repository, clicking it's settings, finding the pages tab and then hit Deploy from branch and selected my root folder

- The live site can be found at https://arunhtv.github.io/portfolio-one/index.html

## Credits/Content Credits

- All album art found on  https://redhotchilipeppers.com
- Love Running Site used as reference for navigation bar and social media links
- Lessons found on codeinstitute.net used for help with setting out content
- All other references have been included in the pages they helped create (e.g the pedal board)

# Frusciante Facts V2

The following is an update to my initial markdown, chronicling how the site has been developed since it was first deployed. The most major change is that the site is now fully responsive, which I will discuss, amongst other improvements

![responsive](https://github.com/ArunHTV/portfolio-one/blob/main/markdown-images/responsivescreenshot.png?raw=true)

## Navigation

- The navigation bar is largely the same in principle, it has been created using a list and each list item is given an anchor tag. However, it is now fully responsive. This is achieve by using a flex display, aligning the navigation to the center of the page and then adding a media query that decreases the font size when appearing on a small screen
- The title of the page (which itself directs the user to the home page) has been made responsive using a the same method, albeit without the flex display, as I just need to display one block of text as opposed to the three different sections

![NavUpdate](https://github.com/ArunHTV/portfolio-one/blob/main/markdown-images/navbarupdate.png?raw=true)


## Homepage

- The homepage is now fully responsive, using a flex box and using flex-direction to have the content display as a vertical column. A media query has then been used so the font-size decreases for smaller screens
- The video embedded on the page is now also fully responsive. I have applied a media query so that the pixel size of the video is smaller depending on the size of the screen

![HomeUpdate](https://github.com/ArunHTV/portfolio-one/blob/main/markdown-images/homepageupdate.png?raw=true)

## About 

- The image used on this page has been changed as an aesthetic choice. 
- The container method has been used to center the content. The text has been given it#s own class and used the flext method so that the text shrinks with the screen
- A media query has then been applied to shrink the image and text for smaller screens with slight padding so that neither the image or text are cropped

![AboutUpdate](https://github.com/ArunHTV/portfolio-one/blob/main/markdown-images/aboutupdate.png?raw=true)

## Discography

- The discogaphy page is now responsive. The images have been placed in a container and laid out in a grid so that the images appear in rows of three.
- A media query has been applied for smaller screens that collapses the images so that they appear in a column, as a grid view on a mobile screen would make the artwork too small to view

![DiscogUpdate](https://github.com/ArunHTV/portfolio-one/blob/main/markdown-images/discographyupdate.png?raw=true)

## Album Pages

- Album pages now share CSS as opposed to the initial build which had individual styling for each page. This was too time consuming and also destroyed the flow a bit, hence switching to just the one CSS
- To create the format for the page (image next to the lists), I have used flex direction and column for big screens and have applied a media query so that the content collapses to one vertical column for mobile screens

![AlbumUpdate](https://github.com/ArunHTV/portfolio-one/blob/main/markdown-images/albumupdate.png?raw=true)

## Gear

-  The method used in the previous "Album Pages" section has been used for the album page, including the ordered list styling, so that the image and list of pedals vary sizes on the screen by using a media query

![GearUpdate](https://github.com/ArunHTV/portfolio-one/blob/main/markdown-images/gearupdate.png?raw=true)

## Bugs 

- All bugs from previous build (the issues making each page responsive) have been fixed

## Testing

- No errors found in the HTML pages using Nu HTML Checker
- No errors found in CSS page using W3C CSS Validation Service
- Phone test using own mobile (Samsung Galaxy A52)
- Bytes' "Am I Responsive?" site used to test how responsive site is on various screen sizes (a screenshot of this can be found under the "Frusciante Facts V2" main heading)

## Deployment

- Deployed from repository https://github.com/ArunHTV/portfolio-one by going to the repository clicking settings, finding the pages tab and then hit Deploy from branch and selecting my root folder to build the site
- The deployed site can be found at https://arunhtv.github.io/portfolio-one/index.html

# Credits

- All album art found on  https://redhotchilipeppers.com
- Love Running Site used as reference for navigation bar and social media links
- Lessons found on codeinstitute.net used for help with setting out content
- All other references have been included in the pages they helped create (e.g the pedal board)
- Tutorial used to help better understand flex boxes https://www.youtube.com/watch?v=phWxA89Dy94

