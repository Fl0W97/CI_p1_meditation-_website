# Calm down

Welcome to my first project, the calm down website is a landing page for people how are motivated to start meditating. It offers motivation and reasons why to start meditating, a few easy meditation techniques and further links to further sources to intensify meditation. The content is based on the book 'Search inside yourself'.

<img src="images_readme/AmIResponsive.PNG" alt="image shows responisveness by presenting preview on different devices">

## Features

### Navigation

The user is able to navigate on the navigation bar. There are three navigation elements according to the three pages Why, How, Who. Due to responsive design requiremets the behaviour and position of the navigation bar is slightly different.
To keep the complexity low and due to the fact that the menu elements are short, there is no toggle function for the mobile view.

Mobile view: Elements are aligned to the center. No toggle used. The width of the navigation is so small (~300px) that the content is not covered from the navigation once the screen gets smaller for mobile view. 

Tablet view: Logo on the left site, navigation elements on the right site.

Desktop view: Logo on the left site, navigation elements on the right site. However effect is implemented. 

There are three media query breakpoints used: (320px), 768px, 992px

Desktop view
<img src="images_readme/navigation_desktop.PNG" alt="image shows navigation desktop">

Tablet view
<img src="images_readme/navigation_tablet.PNG" alt="image shows navigation tablet">

Mobile view
<img src="images_readme/navigation_mobile.PNG" alt="image shows navigation mobile">

### The header 
Title and logo are above the navigation. Depending on the media query the header gets bigger. The font-size/size of title and logo increases. The header's height is around 100px, therefore. there is a margin-top value of 97px on the main element.

Header
<img src="images_readme/header.PNG" alt="image shows header">

### Homepage why.html / Welcome
The homepage shows a hero image that indicates what this site is about: meditation and finding peace. Below the hero image there is text and motivative reasons why the user should start meditating. Depeneding on the device the content adjsuted smoothly on the screen size.

Homepage
<img src="images_readme/preview_why.PNG" alt="image shows preview of why.html">

### How.html / Instructions and meditation techniques
Find here useful information to start meditating. There is a small image which remains the atmosphere of the homepage. Below you find short instructions. In addition, you find at the bottom different meditations texts and audio player. Each meditation is written down and recorded. For a better navigation there is a submenu above the meditations and anchors placed below each meditation. The anchor has to be fixed -97px and hidden due to the fix header at the top.

how.html
<img src="images_readme/preview_how.PNG" alt="image shows preview of how.html">

### Who.html / About authour and website creator
Displays content about author of the book 'Search Inside Yourself' and a few random information about the creator. Sections and divs are reused from previous pages.

who.html

<img src="images_readme/preview_who.PNG" alt="image shows preview of who.html">

## Design
Plain, simple design to lead the focus of the content. Peaceful image scenary is selected to calm down. The colors used are mostly white (#ffffff, #140b08), grey (#dcccb2), green (#0f9d58) and a few black elements such as the logo (#252525, #000000).
The main font color is black, grey (#918e8e) to provide a userfriendly contrast.  

## Testing
- Testing was done in small breaks during the development and at the end of the project
- Validators have been used.
- small feature checks has been made by using preview and the devtools device toolbar
- I tested that this page works in different browsers such as Edge,  Chrome and Firefox.
- Responsivness is tested with different screen sizes by using devtools device toolbar.
- navigation, header and content of all subpages is readable and easy to understand.
- the audio files are working and autoplay is deactivated when the page is opened.


### Bugs
Some adjustment has been necessary i.e. the flex features haven't been working correctly due to wrong values. Typos caused problems with css definitions, ...

id="menu_meditations"
Due to header fixation the anchor has to be placed to another section (more above). Same problem appears when the sub-navigation is used an the user wants to jump to i.e. the body scan meditation. The header covers the audio player, the user has to scroll up a bit. To fix this issue a hidden anchor was added.

id="logo-size"
Id selector is used multiple times, therefore the elemt type id is not valid. The elemt is transferred into a class element.

Due to a bad performance via Lighthouse the images have been compressed via [tiny.com](https://tinypng.com/)


### Validator Testing
Validator testing has been done on:

#### HTML validator test
https://validator.w3.org/
No errors were returned

#### CSS validator test
https://jigsaw.w3.org/css-validator/
No errors were returned

#### Accessability
I confirm that the selected colors and fonts are easy to read and accessible by using lighthouse in devtools (Chrome).

<img src="images_readme/Lighthouse_analysis_index_03.04.2023.PNG" alt="image shows Lighthouse result">

### Unfixed Bugs
No unfixed bugs.

## Deployment

The site was deployed to GitHub pages. 

Here the live link: https://fl0w97.github.io/CI_p1_meditation-_website/index.html

## Credits

### Media
Awesome font designs for Facebook, Youtube and Instagram logos are used
https://fontawesome.com/
https://kit.fontawesome.com/3b20d96fa9.js

Small illustrations and images are used from Freepik.com
https://www.freepik.com/search?format=search&img=1&last_filter=img&last_value=1&query=&selection=1
https://www.freepik.com/search#uuid=e32d609a-2728-482c-888c-a2f48f37a07b
https://www.freepik.com/icon/man_7118103#fromView=search&page=1&position=14&uuid=78e40cd6-31c1-4419-bb6f-f74405b905ab
https://www.freepik.com/icon/person-identify_11087997#fromView=search&page=1&position=28&uuid=405651ad-1d0c-48e0-a6f8-dcd2c157bd4f

Images for seasons why
https://www.freepik.com/icon/peace_9344997
https://www.freepik.com/icon/friend_10879075
https://www.freepik.com/icon/target_566958
https://www.freepik.com/icon/overwhelmed_6210111

Image for meditations
https://www.freepik.com/icon/boiling_2478676
https://www.freepik.com/icon/mindfulness_11245449
https://www.freepik.com/icon/one-man-walking_76865
https://www.freepik.com/icon/circle-arrows_7893895
https://www.freepik.com/icon/body-scan_10890662

Image hero image
https://picjumbo.com/download?d=woman-meditating-on-wooden-platform-with-amazing-scenery-view-free-photo.jpg&n=woman-meditating-on-wooden-platform-with-amazing-scenery-view&id=1

Background image
https://i0.wp.com/picjumbo.com/wp-content/uploads/romantic-fall-scenery-countryside-road-in-foggy-autumn-morning-free-photo.jpg?w=2210&quality=70

Logo Calm down
https://www.istockphoto.com/de/vektor/abstrakte-pyramide-der-lebensbalance-suche-mit-anpassung-des-mentalen-und-gm1353485594-428574758


Favicon generator
https://favicon.io/

Reduce image size
https://tinypng.com/

Fonts
https://fonts.google.com/

Photos of the author:
https://community.thriveglobal.com/wp-content/uploads/2017/08/20120201_1_0032.jpg

All audio files are recorded by the website creator.


### Content
Book 'Search Inside Yourself by Chade-Meng Tan
https://www.helpguide.org/meditations/guided-imagery-meditation.htm
https://www.mindful.org/how-to-meditate/
https://siyli.org/check-out-siylis-new-look/
https://www.headspace.com/

### Code
Reused code/ idea from Love Running project:
flex:box logic for responisive navigation and content