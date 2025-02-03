So I decided to update the calculator project to add a graphing equations feature.

First, I asked gpt to add a linear equations graphing function which it sucessfully added without any axis scaling or markers

Then I asked for markers which seemed to be acurate

Next I asked it to expand the graphing functionality to graph exponetial equations such as y = a*x^b and y = a*e^(bx) which it also managed to do

Note* the equations must be in specific formats
y = a*x^b / y = a*e^(bx) / y = m*x + b
for simplicity heres an equation 
y = 2*x - 1

The last thing I added which I was supprised didnt work was a simple changable scaling feature. I wanted to be able to write a min-x min-y max-x max-y and type in values for the edges of the graphic window, and change the created graph to acuratly represent the new scale. Interestingly it could get the x-axis scaling to work but not the y-axis. The y-axis was always centered around the y-min value not 0,0. BUT the graph itself was going through the correct y-coordinates despite the odd looking axis. Im not sure why it was unable to add this feature but it was able to add graphing generally. 