I did the same initial prompt with same base image as before.

# Gemini
Gemini was pretty bad since, it asked me to complete the styling and a lot of scripts part

# Output can be seen at [Gemini](Gemini.html)

# Co-Pilot
It had no image uploading feature. So, I prompted the experiment
> I want to teach some college level people about mean and covariance of points. .So, i want to design a single html website using html, js and css that can teach them. It needs to look modern and has to have a dark theme and icons. You can use d3.js or three.js for visualising the points. Make sure to add features where use can add custom points of class 1 or 2 and it will calculate the values as well as show in the graph. Also add a feature where user can generate points to visualise in a graph given their mean and covariance.

# Output can be seen at [Co-Pilot](CoPilot_1.html)

Here, the UI was pretty basic and stuffs did not work. So, I pointed out the mistakes to it
> make the webpage more user intututive. give example on how the values should be. also, custom points should be clickable on the graph to add them instead of putting in values. Also, I would like the graph in the left and the controls on the right. Also, generaition of points should be different for class 1&2

# Output can be seen at [Co-Pilot](CoPilot_2.html)
Here, the custom generation of the points are rendered. But, the calc of the values and the custom adding points arent implemented
> I want the values to be calculated and shown in a table whenever a point is rendered. Also, the custom points should be added when the user clicks on the graph after selecting the class.

This one doesnt work at all and breaks the previous features