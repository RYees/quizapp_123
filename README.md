# Question Application

The website application uses to form a muliple question for any thing we want and counts the amount of correct answers and finally shows the result. It combines javascript,html and css in its implementation.

# Installation

`npm i questionapp --save`

# Usage

. Click the option you want to choose using the button() function:
             function button(event){
           	     app.check(event);
           	     app.unclick();
           }
. Click the next button to go to the next question using the next() funciton:
           function  next(){
              app.next();
              app.click();
         } 
. Click the next button to see your total score.