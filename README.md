# First Milestone Project / Astirian-Rae Games
____

Asirian-Rae Games is a small mobile-games company set up by my brother, Daragh Wickham. They make 2D platform mobile games using C# and Unity.
This is the link to the deployed webapge: [Astirian-Rae Games](https://martycistudent.github.io/First-milestone-project/)

## UX Design:

### Strategy

#### Who is this for?
The vision of this business is to produce games using traditional gaming styles, modelled on those of the 80’s and 90’s, delivered on a mobile platform. 
This provides a huge range for exposure demographically due the accessibility of this medium. Therefore, the initial target audience will probably be 
between the ages of 20 – 40, with scope for a growing target audience.

#### What type of content will be relevant? 
As the company is still in it’s formative stages, the main goals for the company will be increasing brand awareness, product awareness and creating more 
opportunities for expansion. In order to achieve this I will be focusing on three key areas of content;

Branding - the logo should be heavily emphasized and unique. I want to establish a font as well as a colour scheme.

Media content – to give a good sense of what each game is about, I will provide some screenshots of each working game as well as some play-through videos and possibly some concept art to provide additional background for the story of the games setting. 

Social media –  to further promote the business brand and content across other social media platforms.

### Scope

#### What does the client need?
* A brand name and logo to help make the business more recognisable and create a sense of familiarity.
* A mobile first website approach
* A catalogue page displaying any games the company has produced, including a brief outline of what each game is about and the style of play.
* Videos and screenshots will feature for each game respectively in the catalogue page to help anyone better visualise what kind of games the business has to offer.  
* Links to their social media pages

#### What else can we provide for the client?
* A news section that will update fans with any new products that are being released, or any new updates or bug fixes for current products
* A contact section to leave feedback about games, or for any potential collaborations with other people or businesses in the industry.

#### User scenarios
**Scenario:**
A fan would like to download a new game ---  
**Requirement:**
the ability to download the games via download links.

**Scenario:**
A fan wants to learn more about any other games the business has made ---  
**Requirement:**
The ability to view a catalogue of games the business has produced.

**Scenario:**
A fan wants to share videos and pictures of one of their favourite games ---  
**Requirement:**  
The ability to share links to the business’ social media pages.

**Scenario:**
A fan wants to get in touch about leaving feedback for a way t0 improve one of the games they play ---  
**Requirement:**  
The ability to access contact information to send an email to the business.

### Structure

#### Information Architecture
For this project I will be using a standard tree structure. To achieve this, the header of each page will 
consist of a navigation bar that contains the logo of the business and the main navigational links for each page in the website. 

### Skeleton

#### Wireframe
[A link to my Mobile wireframe](https://github.com/martycistudent/First-milestone-project/tree/master/wireframes/mobile%20wireframes)
[A link to my Desktop wireframe](https://github.com/martycistudent/First-milestone-project/blob/master/Wireframe/Screenshot%20(52).png)

## Features

### Existing Features
* Feature 1 - A subscribe bar at th very top of the page that allows th user to subscribe for updates and notifications by submitting their email address 
                 in a pop up modal.

* Feature 2 - A games catalogue that take the form of cards allows the user to hover over the card and click it which will take them to the playstore/appstore
                to download the game.  

* Feature 3 - A slideshow allows the user to viewport screenshots and covers for the different gsmes so they have abetter understanding of what each game is about.

* Feature 4 - A contact page allows the user to get in touch with the company about working on projects together in the future, or to leave feedback about games.

* Feature 5 - Social media links allow users to view the companies social media pages to view and share content.

* Feature 6 - A return to top button allows the user to navigate back to the top of the page when they click it.

* Feature 7 - Hover effects help users to identify buttons by changing color and size (navbar). 
 

## Technology's Used:
Information Architecture

For this project I will be using a standard tree structure. To achieve this, the header of each page will 
consist of a navigation bar that contains the logo of the business and the main navigational links for each page in the website. 
* [HTML5](https://www.w3schools.com/html/html5_intro.asp) - a markup language used to create the structure of the webpage.
* [CSS3](https://www.w3schools.com/css/) - used to style the HTML code. 
* [Bootstrap4](https://getbootstrap.com/) - a front-end component library used to build responsive mobile-first desifn for this webpage.
* [Font Awesome](https://fontawesome.com/) - an icon library and toolkit used to implement various icons and social logos on this webpage
* [Google Fonts](https://fonts.google.com/) - a library of fonts that can eb imported in to your projects.
* [Cloud9](https://c9.io/wiickmar) - This is the IDE used to write and test the code for this project.
* [Git](https://git-scm.com/) - Git is a tool that is used to track and store changes to your codes as you work. It stores your code in a local repository.
* [Github](https://github.com/) - Github is a remote repository used to store our code. It is also used to deploy this project. 

## Testing
In order to ensure the website functioned as expected, all of the testing for this project was done using the browser web developer tools. This was a very 
important tool for me through the creative process as it helped me to isolate where the problems were in my code. The issues that this helped me resolve 
include:

* Navigation bar links:
.. 1. Click each link on the main page to verify they work.
.. 2. Navigate to "Contact" page.
.. 3. Click each link on the "Contact" page to verify that they work.

* Contact form:
.. 1. Go to the "Contact Us" page.
.. 2. Try to submit the empty form and verify that an error message about the required fields appears.
.. 3. Try to submit the form with an invalid email address and verify that an error message appears.
.. 4. Try to submit the form with all inputs valid and verify that a success message appears.

* Subscribe button/ Modal:
.. 1. Click "subscribe" button.
.. 2. Try to submit without any information and verify that an error message about the required fields appears.
.. 3. Try t submit an invalid email address and and verify that a relevant error message appears.
.. 4. Verify that a successful message appears by submitting a valid email address.

* Game download links:
.. 1. Click on the "Games" link in the navigation bar.
.. 2. Click each card to verify that they open up the correct app page in a new tab.

* Social Media links:
.. 1. Go to the footer of the home page.
.. 2. Click each link to verify that they open up the correct social media page in a new tab.

* Hover effects:
.. 1. Hover over any buttons and links in the project.
.. 2. Ensure the use of appropriate color and time transitions to help ensure a good user experience.

* Grid system:
.. 1. Open bwoser developer tools. 
.. 2. Display device toolbar. 
.. 3. Select iPhone 5SE.
.. 4. Review layout for small screen widths.
.. 5. Select Ipad in the device toolbar.
.. 6. Review layout for medium screen widths.
.. 7. Select Laptop in the device toolbar.
.. 8. Review layout for large screen sizes.
.. 9. Make any necessary changes. 

* Layout - mostly padding and margins, to ensure adequate spacing between elements as well as sizing for elements.

* Media queries - certain elements that might overflow such as titles, on very small screen sizes. Viweing the change of elements with screen sizes allowed
  me to make the necessary changes so that elemnts were proportional across differnet screen widths. 

I used a *code validator* on [W3 Markup Validation Service](https://validator.w3.org/#validate_by_input) to checks for any errors that needed to be 
fixed in my code. 

Finally, I posted my project in the peer-code-review channel on Slack and received some very helpful criticism to help me fix some mistakes that 
slipped under the rader.

## Deployment 
1. The project was written and developed in the Cloud9 IDE.
2. A local repository was intialized using Git. Regular changes were commited to the local repository.
3. Github was used as a remote repository, and at the end of each development session, all local commits were pushed to (https://github.com/martycistudent/First-milestone-project)
4. The project’s source file was published from GitHub repository to GitHub pages using GitHub default settings via the master branch.
5. GitHub Pages was then enabled to publish the site from the master branch following this path:
.. 1. GitHub repository settings page.
.. 2. Scrolling down to the GitHub Pages Repository box, the master branch was selected from the dropdown menu.
.. 3. The action was saved by clicking the save button.

6. The Project’s source file is now published as a site on GitHub Pages at [Astirian-Rae Games](https://martycistudent.github.io/First-milestone-project/)

## Credits
### Media 
All media for this project was supplied by Astirian-Rae Games. 

### Acknowledgements 
For the main layout of this project I took inspiration from <https://www.zelda.com/> and <https://bethesda.net/en/dashboard>. For more
specific features I also received inspiration from our Bootstrap classes creating the Whiskey Drop page and the Rosie Odenkirk resume page. 
