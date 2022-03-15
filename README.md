# Paintballers Elite
Paintballers Elite is a website gathering paintball lovers from Hertfordshire, England, and informing them of competition dates, locations and how long the contest is. This website is targeted towards people that enjoy paintballing, and would like to add a challenge to the game.

![Paintballers Elite Responsive Design](https://github.com/Dylan097/Project-1/blob/main/assets/images/media/responsive-design.png)

## Features

- __Navigation Bar__

    - Fully responsive, once completed, will be on all 3 pages, and will show what's active, and what the user is currently hovering over.

    - This feature allows the user to easily navigate throughout the webpage, allowing them to freely get to where they need to without using the "previous page" button.

    ![Nav Bar](https://github.com/Dylan097/Project-1/blob/main/assets/images/media/nav-bar.png)

- __The Landing Page__

    - This page allows the user to see the purpose of the page, and where the events are gonna be based.

    - The landing page includes an image as a background, and a very short description of what the website is meant to be for.

    ![Landing Page](https://github.com/Dylan097/Project-1/blob/main/assets/images/media/landing-page.png)

- __About Us Section__

    - This section describes in more detail what the website is about.

    - About Us let's the user know where the contests and strategies are roughly based, and it explains what sort of thing they can expect from meetups

    ![About Us](https://github.com/Dylan097/Project-1/blob/main/assets/images/media/about-us.png)

- __Contest Section__

    - This section let's website users know when each activity will be, what activity is on which day, and where each activity will be.

    - This section let's the user see that there won't be daily painballing, and that there will be a chance to talk to the people that go to the paintballing each week, and get to know each other better.

    ![Contest section](https://github.com/Dylan097/Project-1/blob/main/assets/images/media/contest.png)

- __Footer__

    - The footer contains links to social media websites and YouTube across all 3 pages.

    - This allows the website user to easily access any pages linked to the website.

    ![Page Footer](https://github.com/Dylan097/Project-1/blob/main/assets/images/media/footer.png)

- __Contact Us Page__

    - The Contact Us Page allows users to find a telephone number and email address to contact the website admin directly for any information, and to even sign up.

    - This allows the user to contact with any general questions about the event dates, and if they can just attend a couple of sessions instead of all of them.

    ![Contact Us Page](https://github.com/Dylan097/Project-1/blob/main/assets/images/media/contact-us.png)

- __Sign Up Page__

    - The Sign Up Page allows users to signup to the Paintballers Elite group directly from the website, without ever having to contact anyone if they wish to get straight on board.

    - This makes it easier for people to sign up to the group, with just a few little details to add, being first and last name, and their email address.

    ![Sign Up Page](https://github.com/Dylan097/Project-1/blob/main/assets/images/media/sign-up.png)

## Testing

### Accessibility testing

 - The testing for accessibility was successful, using lighthouse with dev tools in the browser screen

 ![Accessibility testing](https://github.com/Dylan097/Project-1/blob/main/assets/images/media/accessibility-check.png)

### HTML testing

- index.html was tested and came back with no errors using [W3C Validator](https://validator.w3.org/nu/#textarea)

- contact-us.html was tested and came back with no errors using [W3C Validator](https://validator.w3.org/nu/#textarea)

- sign-up.html was tested and came back with no errors using [W3C Validator](https://validator.w3.org/nu/#textarea)

### CSS testing

- style.css was tested and came back with no errors using [jigsaw Validator](https://jigsaw.w3.org/css-validator/validator)

### Bugs

#### Fixed Bugs

- Only one div in the contest section was showing. Used float: left in style.css to fix
- One div not showing in contest section. Used box-sizing: border-box in style.css to fix.
- Divs in about us section colliding with eachother after 950px size change. Used clear: both in style.css to fix.
- Most icons not showing on the contest section. Changed each broken icon so they show for each div in index.html and contact-us.html.
- In microsoft edge, sign-up form presented on top of the cover text at 565px or less width. I changed the top from 53% to 250px in the form id for 565px or less width.
- Contest divs overlapping eachother at less than 400px width. Changed the padding-top to 5px at less than 565px to fix this.

#### Unfixed Bugs

- None

## Deployment

- The website was deployed via gitHub pages. The deployment steps I took are as follows:

    - From the gitHub project_1 page, open the settings page

    - Find the gitHub pages section, then click on the link to gitHub pages

    - Once opened, go to source, then select branch: main

    - Once branch: main is selected, click on the save button

    - Once saved, the page refreshes automatically with a link to the webpage

This is the live link - https://dylan097.github.io/Project-1/

## credits

### contents

- Paintball arena locations come from [this webpage](https://go-ballistic.co.uk/en/index)

- Icons come from [this webpage](https://fontawesome.com/)

- Inspiration for the Contest section came from the Love Running walkthrough project from Code Institute

- [This webpage](https://www.delftstack.com/howto/html/html-transparent-hex-code/#:~:text=In%20CSS%2C%20select%20the%20div,hexadecimal%20value%2080%20is%20128.) was used to figure out how to set transparency using hex code.

- Background colours were found using [this color tool](https://material.io/resources/color/#!/?view.left=1&view.right=0&primary.color=f1000c&secondary.color=BA68C8)

- Paintballing locations in Hertfordshire were found using [go ballistic](https://go-ballistic.co.uk/en/index)

- The fonts used in this website were found with [google fonts](https://fonts.google.com/)

### media

- The photo used in the main page is from [this webpage](https://as1.ftcdn.net/v2/jpg/02/23/35/22/1000_F_223352240_YxbaMMwLbFTOFTds14Zrz0Aalk0epBBD.jpg)

- The photo used in the background for the contest info is from [this webpage](https://www.oakerwoodleisure.co.uk/app/uploads/2021/07/2-1800x750.jpeg)
