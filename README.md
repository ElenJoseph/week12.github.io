My brief description on how I created my interactive galery:

HOW the interactive was created, what techniques or technologies were used, what challenge were faced and how you over came them:

I    had to creaate an HTML ON JV using callig  one elemen of HTML 
calling Body tag using ID ex:
const body = document.getElementById('body')
body.innerHTML = `<H1> Write Anything here... </H1>`

I create an id "pageTitle"
               "grid"
               "overlay"

Then I create the a const to call the pictures.

I used for of loop to criate a class imgBox, to call a sorce of the image, to crate a thumnail and to call a class hoverText

Then I called image from grid which I created before

I used var hoverText = document.querySelectorAll('.hoverText') to the name of the oicture apper when I hover the mause on it.


I used "for of if loop" again to create an event of click and a called a fuction of makeBig

I used window.addEventListener('mouseup', closeMe); to close the image when if it is clicled outside of the overlay with the function close.Me


Every step I made was a chaleenge the I had to face and I had the teacher in class to help me to overcome some of them as well as the PA section.


WHY some design / functional choices where made, and their purpose?
I used a  background-image of a world map to make my gallegy more appeling since I used the pictures of my trevels arround the world.

I used .imgBox position relave 
and .hoverText position absolute to fix the image and text
I used #overlay  background-color: rgba(255,255,255,0.2); to make it transparent.



WHAT you learned from creating the interactive gallery?

I learned That cooding cold be fun as soon as I understand it and see the results of each fuction really working. Eventhoug its still very difficult to me.
I enjoied working on this exercise.