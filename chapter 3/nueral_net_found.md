Functions are really important, we give it input and then it process and gives us outpiut,
key properties of functions:
all the possible inputs are called domain, it could be any real number
all the possible outputs are called range, it could be any real number
Single neuron  = simple fuction
Each nueron takes input, multiplies them be weights, adds a bais and applies " activation fuctions
This is just like our f(x) = 2x + 3, but with multiple inputs!

A nueral network is just a mathemathical function, it is the most standard kind of nueral network. 
The function:
multiplies each number by the number of values, these numbers are called parameters.
add them up for each group of values
replaces the negetive number with zeros

this represent one layer and these are the steps repeeated, using the output of the previous layers as inputs to the next layer
Initially, the parameters in this function are selected randomly. Therefore a newly created neural network doesn't do anything useful at all -- it's just random!

To get the function to "learn" to do something useful, we have to change the parameters to make them "better" in some way. We do this using gradient descent. 

**Youtube video about nueral networks"
What are nueral networks:
Each nueron has a number, and each number inside is called actiivation


Equation has two equal parts.
expression is jsut consites of numbers
linear euqation: highest value of x is 1, draws straitght line
quadtarcie: highesat value of x is 2: draw u shape (parabola)
activation fuction: decide what to keep and remove:relu sigmoid
gradient dcent: A way the model improves itself step by step to reduce the loss.

“We chose a parametric model (a parabola)”

Parametric model just means a formula whose shape is controlled by a few numbers (parameters).

In our example, the formula is

𝑦
=
𝑎
 
𝑥
2
+
𝑏
 
𝑥
+
𝑐
,
y=ax 
2
 +bx+c,
and the three parameters are 
𝑎
a, 
𝑏
b, and 
𝑐
c.

“Fitted it to noisy data by manually tweaking its parameters”

We generated “data” by sampling points from the true parabola but then adding random wiggles so they don’t lie perfectly on the curve.

At first, we turned “knobs” for 
𝑎
a, 
𝑏
b, and 
𝑐
c by hand (via sliders) until the red curve looked like it went through the cloud of points.

“Measured the fit with Mean Absolute Error”

 “that looks good,” we calculated a single number—MAE—that’s the average vertical distance between each data point and our curve.

Lower MAE means the curve is closer, on average, to all the points.

“Then replaced manual tuning with automated gradient‐descent optimization”

Gradient descent is the algorithm that, for each parameter, asks “If I nudge this number up or down, will the error go up or down?” and then makes the small move that reduces error.

Repeating this “forward pass → compute loss → backward pass → update parameters” loop lets a computer hone in on the best 
𝑎
,
𝑏
,
𝑐
a,b,c without you dragging sliders.

“Using ReLU activations”

When we move beyond a simple parabola to a neural network, each layer does two things:


A ReLU step, which replaces any negative results with zero.

These two steps (linear + ReLU) stacked together let the network learn very flexible, piecewise-linear shapes—far richer than a single parabola.

In short:

We started with a simple formula and noisy sample points.

We eyeballed the fit and then measured it with a loss.

Finally, we taught the computer to do the tweaking automatically (gradient descent) and built more powerful predictors by adding ReLU “kinks” in each layer.

We use matrix multipication to combine input and weighta, Like the input is our data and then the wwights are initlized random at first..


