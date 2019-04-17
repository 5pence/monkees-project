# The Monkees Responsive Website Project

### What does it do and what need does it fulfil?

This project uses skills learnt to build a mobile-first responsive Website for the 60's band The Monkees.
It fulfils the need for fans and potential fans to listen to The Monkees music, watch a music video, join a fan club, enquire through a contact form to hire the band 
as well as view pictures related to the band members and album cover artwork.

### Functionality of project

The website is fully responsive, on desktop and larger screen sizes there is a small amount of additional content (one picture on the header).
The navigation is functional and two forms (join the fan club and hire us) are input validated which then resolves to a respective thankyou page. These forms are not fully functional in that they don't alert anyone from the Webteam that a form has being filled nor do they fill a database.  Currently the join the fan club thankyou page works however the hire-us form thankyou page does work on my local desktop but not on github pages, I believe this is due to appending PUSH data on the URL which github pages disallows due to injection risk.

### Technologies Used

- HTML5
- CSS3
- Bootstrap
- Bash
- Ubuntu
- GIT
- GITHUB
- Google Chrome developer tools
- Cloud 9 IDE
- Javascript and JQuery are imported for the join the fan club modal.

### Deployment

Website was coded in the Cloud 9 IDE, a local GIT directory was used for version control and then uploaded to GITHUB using Ubuntu / Bash script. Once in a GITHUB repositories it was made live using GITHUB Pages. The website can be found at:
https://5pence.github.io/monkees-project/

### Testing

Each page was tested locally and on GITHUB pages using Chrome developer tools, testing its functionality as well as look and feel (in landscape and portrait mode) on Galaxy S5, Nexus 5S, Nexus 6P, iPhone 7, iPhone 7 Plus, iPhone 8, iPhone 8 Plus, iPhone X, iPad, iPad Pro and responsive desktop. All links were tested along with music tracks audio controls and video player. The modal join fan club form and the hire us form was tested locally and remotely.

### Work based on other code

Only the modal fan club form code was re-used from the previous Whiskey Drop exercise. I modified its content and changed some of the code within it to reflect semantically what it was being used for. I also changed its action to point to a fan club thankyou page to confirm their action and increase user experience. 

### What changed after user design experience (UDX) phase

I had planned to put the video on the gallery page however after discovering the video wasn't one taken from their TV series (which I assumed to be the case) but rather a music video I placed the video on the music page.
