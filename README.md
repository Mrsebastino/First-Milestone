### Private Chef Escoffier

### First Milestone. User Centric Frontend Development. Code Institute.
 This is a website that promote an imaginary chef organising private event.
The website include a description of the chef study and work experience,
example of dishes with photos, imaginary quotes, a contact form and a menu.

### Demo 
[Private Chef](https://mrsebastino.github.io/First-Milestone/)

### UX/UI
My intent with this website is to make it simple to use, attractive and showcase
the experience of the private chef. I used a handwriting font to give it a more personal and artistic touch, so that the user feel they can have a more
service.

For the customer the website will increase his business, create word of mouth and attract more customer.
### Technologies Used
* 
* html
* css 
* Bootstrap v 4.3.1
* Font Awesome
* Google Font
* JQuery
* POpper.js


### Features
 The Navbar  is taken from Bootstrap, i have made some adjustment to it. The animation on the title is from animate.css.
 In the footer i've added a link to the top of the page and some social media link. I removed the top of the page link in the footer for the
 mobile version and moved the social icon to the center.
 In the contact section, i used a  contact form and a button submit form from Bootstraps.

Bug encountered.
I had an horizontal overflow, and when i tried to fix it by adjusting `container-fluid` it affected the mobile version. I have look using node removal
in chrome devtools and couldn't find anything, in the end it was a problem with `row` so i override it in CSS not sure if this
qualified as a bug.
 At one stage when i clicked on the logo in the nav bar and in the footer it went from orange to white which was expected but just before it
refresh the page it went blue for a few second. None of the other hover animation for events, quotes and contact had that problem. That was
fixed by changing the colors all together, It is now white and the text enlarge when hovered.

### Testing

I have tested the pages on my mobile and on friends mobile, the site is responsive. I also check with the devtools in Google Chrome.
I have tested it on laptop and PC, on 4k there was issue with content spreading too much. It has been fixed by making sure that the content remain centered.

I have filled the contact form but not the email, and has expected i was prompted to fill the the box.
I have tried the above with all the fields that need filled and every time i had the expected result of being prompted to fill the box.
I have set up the submit button to a fake email address  and the response is "mike.escoffier sent an invalid response" which is the expected outcome.
I am confident that the website has been tested and is responsive on mobile and desktop.
it has been tested in google chrome, safari IOS and safari MAC IOS, Mac book pro and 4k, the website is responsive across all platform.

### Deployment

The sites is deployed using GitHUb, it is deployed directly using the master branch.
That allowed me to make change to the webpages and it will update automatically.

## Credits

### Contents

All the content is written by me. Escoffier is a surname of a famous French Chef, Auguste Escoffier.

### Media

Most of the photos are taken from Pexels, one photo is mine, and two photos are from Google,
The icon in the page tab was created with favicon, after somebody recommended it on Slack.

### Acknowledgements

I have took inspiration from two Code Institute mini project, the Bootstrap project and Resume project.
I made adjustment to the contact form and the navbar form, the contact form is part from bootstrap and helps form a slack mentor.
My mentor and Slack were both great help throughout my project.

