<h1> Private Chef Escoffier</h1>

<h3> First Milestone. User Centic Frontend Development. Code Institute.</h3>
 This is a website that promote an imaginary chef organising private event.
The website include a description of the chef study and work experience,
example of dishes with photos, imaginary quotes, a contact form and a menu.

<h3> Demo </h3>
A live demo can be found at GitHub.  https://mrsebastino.github.io/First-Milestone/

<h3>UX/UI</h3>
My intent with this website is to make it simple to use, attractive and showcase<br>
the experience of the private chef. I used a handwriting font to give it a more personal and artistic touch, so that the user feel they can have a more
service.
<h3></h3>
For the customer the website will increase his business, create word of mouth and attract more customer.

<h3>Technologies Used</h3>
<ul>
<li>html  </li>
<li>css </li>
<li>Bootstrap v 4.3.1</li>
<li>Font Awsome</li>
<li>Google Font</li>
<li>JQuery</li>
<li>POpper.js</li>
</ul>

<h3> Features</h3>
 The Navbar  is taken from Bootstrap, i have made some adjusment to it. The animation on the tiltle is from animate.css.
 In the footer i've added a link to the top of the page and some social media link. I removed the top of the page link in the footer for the
 mobile version and moved the social icon to the center.
 In the contact section, i used a  contact form and a button submit form from Bootstraps.

Bug encountered.
I had an horizontal overflow, and when i tried to fix it by adjusting |container-fluid| it affected the mobile version. I have look using node removal
in chrome devtools and couldn't find anything. In the end it was a problem with `row` so i override it in CSS not sure if this
qualified as a bug.
 At one stage when i clicked on the logo in the nav bar and in the footer it went from orange to white which was expected but just before it
refresh the page it went blue for a few second. None of the other hover animation for events, quotes and contact had that problem. That was
fixed by changing the colors all toghether, It is now white and the text enlarge when hovered.

<h3>Testing</h3>

I have tested the pages on my mobile and on friends mobile, the site is responsive. I also check with the devtools in Google Chrome.
I have tested it on laptop and PC, on 4k there was issue with conttent spreading too much.

I have filled the contact form but not the email, and has expected i was promted to fill the the box.
I have tried the above with all the fields that need filled and every time i had the expexted result of being promted to fill the box.
I have set up the submit button to a fake email address  and the response is "mike.escoffier sent an invalid response" which is the expected outcome.
I am confident that the website has been tested and is responsive on mobile and desktop.

<h3>Deployment</h3>

The sites is deployed using GitHUb, it is deployed directly using the master branch.
That allowed me to make change to the webpages and it will update automatically.

<h3>Credits</h3>

<h4>Contents</h4>

All the content is writtne by me. Escoffier is a surname of a famous French Chef, Auguste EScoffier.

<h4>Media</h4>

Most of the photos are taken from Pexels, one photo is mine, and two photos are from Google,
The icon in the page tab was created with favicon, after somebody recomended it on Slack.

<h4>Acknowledgements</h4>

I have took inspiration from two Code Institute mini project, the Bootstrap project and Resume project.
I made adjustment to the contact form and the navbar form, the contact form is part from bootstrap and helps form a slack mentor.
My mentor and Slack were both great help throughout my project.

