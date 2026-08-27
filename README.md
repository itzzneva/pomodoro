# pomodoro

My own timer with a short break, long break and focus button. The maximum the user can concentrate for is 50 minutes. They can take a short break for 5 minutes and a long break for 10 minutes. The buttons allow them to switch in between. They can pause in case they need to do something else. My timer displays the count in the middle so the user is aware of how much time is passed in a circle. It has a blue background and button changes colour once you hover over it so they user is aware of what they are pressing. 

How I designed this: 
1) In the HTML file, I created different classes and buttons which I could style in CSS.
   There is a reset button, in case the person wants to reset the process.
3) In the CSS file, I have designed the button and the time box, allowing it to have a circular border. I found hex codes through searching for a certain colour scheme.
   I embedded google fonts. I kept the sizes of the buttons consistent. 
   I have also allowed different colours for my blue theme, which makes my design more visually appealing overall. 
5) In the Javascript file, I have allowed the user to click on buttons so the time can start running.
   use JavaScript's setInterval() function to count down each second.
   There is an event listener for the reset button, allowing the user to repeat the process. The focus button starts counting down from 50 minutes. 
