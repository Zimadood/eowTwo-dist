# eowTwo-dist
# eowTwo-dist
Gulp Project completed.
My Gulp is constructed to minify css and have a separate
task for expanded css.

index.html file is set to opperate from the scss folder
The GulpFile is outside of the src and other folders.

NOTE 'del npm' is downgraded to 6.1.1

& imagemin.js is version 7.1.0
*********************************************
Tuesday 14th november.

Disaster recovery major distraction (Acccountant telephoned and navbar links styling was lost.
I should have paid more attention to what I was doing and packed up by then.
moral of story: "Effective backups works no matter how small the the projects you do change or are updated."
***********************************************

Sunday 3rd December 2023 Version 48

Slider Theme grid has been understood and nearly/ almost completed all bar media queries and breakpoints.

***********************************************

NOTES: 4th December 2023
eileens of wendover udemy account has the most useful css/sass course.

*Lecture: 56. Let's Use the Power of Sass Mixins to Write Media Queries
re-watch towards the end is the beakpoint/mixin solution you are looking for.

*Lecture: 121. Writing Media Queries - Part 1 (most applicable to eowTwo Project),
I believe not all the queries in this lecture should be employed for eowTwo but 
adapt them to the slide theme and navbar as you see fit.

*Sidebar Navigation needs a good look at when it conmes to shrinking the page.
It's not really very good on smaller screens.

*************************************************
Media Queries to consider
/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {...}
/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 600px) {...}
/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {...}
/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {...}
/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {...}

*************************************************
Saturfay 8th December 2023.

Managed to with success, after being scuppered by a typo,
to work the media queries via _mixins.scss file.
Have yet to re-study Jonas's sidebar change, I seem to remeber that didn'tablets
involve too much code but will have to see how it works with my megre mods.

*************************************************
Sunday 9th December 2023 NOTES.
LAP-13 Size = 1280px wide by 720px height.
iPad Air 3 10inch Tablet Size = 1112px wide by 834px height.

Learning the order of media queries is essential.
Learn from Jonas 'Natours Project' Lectures 56/57.

*************************************************
Monday 11th December 2023.

mixins are working though I do expect some gotchas further on.
I have included max-widths to each mixin 
in the hopes of preventing clashes of media query order.
I'll soon find out if I'm being to big for my own good.

MIXINS used in headerLeft file theme gallery button...
@include respond(phone-port){
  background-color: #41b825;
}
@include respond(phone-lan){
  background-color: #f31606;
}
@include respond(tab-port){
  background-color: #277cc5;
}
@include respond(tab-lan){
  background-color: #f57b18;
}
@include respond(laptop){
  background-color: #fff937;
}
@include respond(desk){
  background-color: #277cc5;
}
@include respond(desk-lg){
  background-color: #41b825;
}

******
2 I have done what I didn't want to do and that is use the Nexter 
Header grid layout for my slide, .slide-theme position.
Had to adapt it slightly.
An extra min-content row was applied and the slide logo has a position 
of 'Absolute' instead of 'relative.


*************************************************

55-Version: Tuesday 12th December 2023

I think I have the media queries covered, There is certainly a lot
a pro will say I've created too much, they are not necessary but I am 
learning.
I get very confused trying to invisage them, Thank heavens for media queries 
horizontal bar code in the chrome dev tools.

I will reduce them but not just at the moment.

*************************************************

Thursday 14th December 2023.

Hope to have the header able to shrink across all devices.
May have to hide certain items to achieve this.

*************************************************
Sunday 17th December 2023

Total change for practical purposes.
Have increased the header and reduced the size of the slider (Header-Feature).
Just working on colors.Gone for a peachy Prawn Pink Primary color.
Brakpoints are understood and set ready for minor adjustments when needed.

***************************************************

Tuesday 28th December 2023
Using GitHub Copilot, (Noth for the first time, please note),
Have had more success and understand how to use the basics better.
It was really useful when increasing the thicknes of the css Hamburger Nav reveal bars.
When trying to do this manually I and other have wasted a lot of time increasing the line thickness
without breaking the perfect X shape after click to open event occurs.
Looks good but might need to revert back to thin lines if I can't loose the bars when page scrolls.

Using Copilot to hide ,hamburger-menu on scroll and unhide when scroll stops is trickier than I thought.

*******************************************************
Friday 29th December 2023

I don't think i've quite finished for todays coding.
Have had some success with Copilot Ai coding assistant.
Now the hamburger lines disappear for 1.5s and reappear in the same time.

i never could find the correct solution to the javascript needed 
to perform this task and it took a couple of good goes trying to
get copilot to understand what I wanted to do.

Looks just as I wanted it to and all then I needed to do was to style to my liking.

TIP: 
SAVE OFTEN THE WHOLE PROJECT IF YOU NEED TO TASK
COPILOT WITH A BIG CHALLENGE.
HAD TO START OVER A COUPLE OF TIMES, (LEARNT THE HARD WAY).

****************************************************
Sunday 31st December 2023

Lesson 197: Jonas javascript course

(Intersection Observers)
Have done it before twice.
Still don't understand a bloody word.
Keep doing it over and over again until I do.
Happy 2024.

*******************************************************
Tuesday January 16th 2024.

Just a shrinking of most elements in the header.
Tidied up the sidebar centering Hamburger.

*******************************************************
Wednesday January 17th 2024.
Added new feature file, re named other different/accordingly

********************************************************
Sunday January 21st 2024 Version 70
Bit of a rescue plan was needed (thank heavens I backup regularlly)
This is backup 70////Backup 69 I should keep but the code is a bit corrupt/ can't use.
Not much more done, can't consentrate/distractions all the time.
********************************************************
Sunday January 28th 2024 Version 74
Github copilot has proved it's weight in gold.
I knew the issue but was looking for a shortcut 
Unfortunaley there wasn't one. 
I'm refering to the slider background images and scaling theme
down for different screen sizes.
Using mixins creates less code but it's still quite a lot more than 
I was expecting. 
Anyway Sizing down or up each jpg file is important but I 
must not forget it can also be helped by increasing and reducing the size of the grid
row the slide is inside...
Take Note of that.
*****************************************************************
Monday January 29th 2024 Version 75
Almost done the mobile media queries for max-width 20em.
Just need to adjust or insert a new background image.
*****************************************************************
Friday 2nd February 2024
Deleted eowTwo git's main folder with all the partials.
Because I keep the whole job backed up locally I just use git as
a web server for portabilty.
Hopefully won'tget any further repository clashes.
Coding for git became a confusing mess.

Have set the 320px media queries, will start over with the 
others next session, then onto the rest of the page.
We're getting there.
*******************************************************************
Saturday 3rd February 2024
Have completed iphone 6-7-8 media queries for slider only. 
Of course there is little else to attend to with them.
Looks ok.
Have also darkrned the translucent background of .slide-theme.
*******************************************************************
Thursday 8th February 2024
Media Queries almost complete.
New git repo created eowTwo-dist