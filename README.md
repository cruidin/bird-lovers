# The Bird Lovers Club

![club logo](/assets/images/logo.jpg)

## Table of contents

1. Introduction
1. UX
    * Demographics
    * User Stories
    * Development Planes
    * Design
1. Features
    * Design Features
    * Additional Comments
    * Future Features
1. Troubles
1. Technical Information
    * Languages Used
1. Credits
    * Art work
    * Texts
    * Websites Consulted
    * Additional Resources
1. Acknowledgements


## Introduction </a>

The Bird Lovers Club is a personal art project in the format of a website. It is about my journey and relationship with birds in general but with a focus on my encounters with birds in Ireland, where I’ve been living for the last decade. In it I share my bird adventures through my drawings and stories and I invite people to join me in my appreciation for those creatures.

I take a very simple and laid back approach to birding and this is reflected in the design style I created for this project. Since it is not only just a coding project but also an artistic one, the aim is to showcase my drawings and stories to an audience of primarily art and bird lovers.

This project was conceived as a response to our first Milestone Project at The Code Institute for their Full Stack Web Development Program. It comprises of a responsive and static website with 4 pages using HTML5 and CSS.

Back to top ⇧

## UX

### Demographics

**Ideal users of this website**
* Art lovers
* Bird lovers
* Curators and people who work in the art field
* Family and friends

### User Stories

*As an art lover:*
1. I want to get to see the art work in this website.
2. I want to get to see more of Patricia’s work.
3. I want to follow Patricia on social media to stay up to date with her art.
4. I want to stay in touch with Patricia and try one of her drawing sessions.

*As a birder:*
1. I want to see bird related art.
2. I want to know about Patricia’s experiences with birds.
3. I want to stay in touch with Patricia and exchange ideas and experiences.
4. I want to try one of Patricia’s monthly get togethers.

*As a curator or person who works in the art field:*
1. I want to get to know Patricia’s work.

*As Patricia's family, friend or acquaintance:*
1. I want to see what she’s up to.

### Development Planes
This was tricky. Even though I knew from the beginning that I wanted to make a website about birds, I still spent over two weeks trying to come up with a plan - and not really knowing how to stick with the plan so I kept changing it. Originally I intended to make this more informative but given that there are tons of comprehensive resources out there my project naturally evolved into an art piece, focusing more on the drawings and stories about birds.

#### Strategy

**Audiences**
* Art lovers
* Bird lovers
* Curators and people who work in the art field
* Family, friends and acquaintances.


**What the user needs to achieve**
* Stay engaged:
    * See pictures clearly
    * Be able to read stories and find stories of specific birds easily
    * Be able to find out how to contact artist easily 

**What the artist needs to achieve**
* Showcase art work
* Provide an accessible way for user to stay in touch
￼
![main image](/assets/images/viability-importance.jpg)

#### Scope
* Content Requirements
    * Illustrations
    * Stories
    * Contact page with form
    * Social links
* Functionality Requirements
    * The user will be able to:
        * Navigate through website with ease and curiosity
        * Contact the artist directly through the form or social media

#### Structure

![main image](/assets/images/structure.jpg)
￼
**Skeleton** 

I used good old pencil on paper for the wireframe of the main page first, then I had a go at Balsamiq and before I started coding I drew the website on the iPad to get a better idea of what I wanted to achieve in terms of colours, layout and design style.

**Balsamiq wireframes**

![main image](/assets/images/home.png)
![main image](/assets/images/mobile.png)
![main image](/assets/images/tablet.png)

**iPad drawing**

![main image](/assets/images/home.jpg)

#### Design

**Colour Scheme**

I used a combination of different soft shades of green and pink as well as a deep dark somber share of brown for contrast. Those colours were chosen to reflect the easy going nature of the drawings and stories and also to communicate pleasantness.

![main image](/assets/images/colour-scheme.jpg)
￼
**Typography**
The fonts used were Roboto and Girassol, with Helvetica as a fall back.

**Illustrations**

All illustrations were made but me for the purpose of this project. There are essentially two different styles of illustrations, both are digital and were made on Procrete, iPad. The more simplistic ones are found throughout the website and are mostly simple outline drawings in very dark brown. The main image present on all pages are coloured. On birds.html the style used is more realistic made in a quick sketch style with more accurate details. In order to merge the two different styles in a cohesive way, I added coloured backgrounds and rounded corners to those images to give them an element of playfulness that is compatible with the design of the rest of the website.

*Simple illustration*

![main image](/assets/images/hide-and-seek.jpg)
￼
*More realistic style illustration*

![main image](/assets/images/starling2.jpg)
￼
Back to top ⇧

## Features

### Design Features

Each page of the website contains:
* Header with logo and horizontal navigation menu (home, birds, activities, contact pages)
* Main image just below header
* Back to the top link - brings back to the header
* Footer with links to birds

Birds, Activities and Contact pages contain:
* A brief description of the page

Home and Activities pages contain:
* A secondary navigation menu to bring to the corresponding subject within the home page	

Birds page contain: 
* A list of links of the birds featured within the page

Home, Birds and Activities pages contain:
* A 2 div structure side by side with illustration on the left and the text on the right on bigger screens and in a single column with illustration above and text below on smaller screens.

Contact page contains:
* Social links styled with Font Awesome and a form.

### Additional Comments

* We have a simple logo with just the name of the website at the top and the navigation menu just below it. When the mouse hovers on the links the background and font color change. The header is consistent throught the website

* Just below the header I opted for an image in a div as opposed to a hero image. After some research and consideration I decided this approach was more in tune with what I wanted to achieve. The image is consistent throughout the website. This article was particularly helpful: https://www.laralee.design/hero-image-alternatives/

* To facilitate the navigation within the main page I added a secondary navigation menu for this purpose 

* There is a basic structure and it is used in all pages (except contact.html): two divs, the left for the illustration and the right for text
 
* The footer contains the links to all birds in birds.html page. They land in their specific location in birds.html.

### Features to be implemented in future - possibly:
* Tips page - with added stories and suggestions on how to attract birds to garden, where to go birdwatching, what to feed as well as links to other resources.
* Shop - a page featuring bird related art prints for sale.
	
Back to top ⇧

## Troubles

I ran into a lot of trouble during this project. Troubles of all sorts. After I had chosen my subject I spent too much time trying to figure out how to plan. Realising that I was taking a bit too long to finalise my plan I had to start coding even without a clear plan. Because of that, my code was messy and all over the place. So it took me a long time to make sense of it and tidy it up/ I also realised that there was a lot of things that I still didn’t understand how they worked.
Eventually, things did settle a bit and I was able to focus on what was essential. 
Things I found particularly difficult:
* Media queries - I just couldn't get the hang of it but with the help of my mentor, Seun, I was able to really get it eventually.
* Aligning divs, content etc - I took a long time to learn how to align things properly but with the help of a game to learn how to use flexbox I was able to understand it well. http://flexboxfroggy.com/ 
* Form - I tried to do this from scratch but styling it the way I wanted proved to be very challenging. I ended up using a combination of two different sources


## Technical Information 

### Languages Used
* HTML5
* CSS3

## Credits

### Art Work

All illustrations were made by me, Patricia Melo (developer and artist)

### Texts

All texts were written by me, Patricia Melo (developer and artist)

### Websites Consulted

* Stack Overflow
* W3Schools
* http://flexboxfroggy.com/ 

### Additional Resources



## Acknowledgements

I would like to thank:
* My mentor, Seun, for her help 
* My fellow classmates who kept me amused when things got desperate
* My family for giving me the space and support that I needed during this project


