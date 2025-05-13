# cs-se4x03-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CS-SE4X03 Assignment 3 Solved](https://www.ankitcodinghub.com/product/cs-se4x03-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92466&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS-SE4X03 Assignment 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Problem 1&nbsp; Consider the integral 􏰄 1 sin(πx2/3)dx. Suppose that we wish to 0

</div>
</div>
<div class="layoutArea">
<div class="column">
integrate it numerically with an error of magnitude less than 10−8 and using equally spaced points and the trapezoidal rule. Derive how many points are needed to achieve this accuracy.

</div>
</div>
<div class="layoutArea">
<div class="column">
Problem 2 Approximate 􏰄 1 (x − 0.5)2 dx using the Simpson’s rule with 5 −1

equally spaced points and calculate the error in this approximation.

Problem 3&nbsp; A common problem in surveying is to determine the altitudes of a series of points with respect to some reference point. The measurements are subject to error, so more observations are taken than are necessary to determine the altitudes, and the resulting overdetermined system is solved in the least square sense to smooth out the error. Suppose that there are four points whose altitudes x1, x2, x3, x4 are to be determined. In addition to direct measurements of each xi, with respect to a reference point, measurements are taken of each point with respect to all of the others. The resulting measurements are:

</div>
</div>
<div class="layoutArea">
<div class="column">
x1 = 2.95

x3 = −1.45 x1 −x2 =1.23 x1 −x4 =1.61 x2 −x4 = 0.45

</div>
<div class="column">
x2 = 1.74

x4 = 1.32 x1 −x3 =4.45 x2 −x3 =3.21 x3 −x4 = −2.75

</div>
</div>
<div class="layoutArea">
<div class="column">
From these data, find the best values for the altitudes. How compare with the direct measurements?

</div>
<div class="column">
do your computed values

</div>
</div>
<div class="layoutArea">
<div class="column">
Problem 4&nbsp; Implement the composite Simpson’s rule and adaptive Simpson. Construct an example of a function f(x), interval [a,b] and tolerance tol such that, to achieve about the same accuracy, the composite Simpson’s rule on a uniform mesh requires at least 100 times more function evaluations than your adaptive Simpson.

For this purpose consider the following steps.

<ul>
<li>Use Matlab’s quad function to compute an accurate approximation. For example, you
can use tolerance 1e-2*tol in quad.

To measure the error produced by your implementations, you can subtract from the

quad’s result and take absolute values.
</li>
<li>Select an n in your composite Simpson such that the error is about tol.
Count the number of function evaluation for this n; denote them by C1.
</li>
<li>In the adaptive Simpson, use tol and compare with the result from quad, to ensure that your computed result is within the tolerance.

Count the the number of function evaluations; denote them by C2.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Then C1 ≥ 100C2 should hold.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Do Not Share this document

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
Name the program implementing the above main_simpson.m. It should output the errors of the composite and adaptive Simpson, C1 and C2, and should also plot f(x) versus x.

Submit

<ul>
<li>PDF: your function (in math notation), the plot, the errors of composite and adaptive Simpson, and C1 and C2</li>
<li>Avenue: main_simpson.m and all the files it uses (if there are such)</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Problem 5 The error function is defined as 2􏰅x2

</div>
</div>
<div class="layoutArea">
<div class="column">
erf(x) = √π In Matlab, it can be evaluated as erf(x).

</div>
<div class="column">
e−t dt

</div>
</div>
<div class="layoutArea">
<div class="column">
(a) Use the midpoint, trapezoid, and Simpson composite quadrature rules to compute an approximate value for erf(1).

Using loglog, plot on the same figure the error in each of these methods versus h = 1/2i, where i = 1,2,…,10.

(b) The errors in these rules behave like chk for constants c and k, where k is the order of a method. Using least squares, estimate these constants for each of the methods using the error data. Output the computed constants for each method as e.g. fprintf(’trapezoid %.2e*h^%.2f\n’, c, k);

You must use this format specification.

Name the main program main_integration_error.m implementing the above. It should produce the plot and output the constants.

Submit

• PDF: plot, the computed constants

• Avenue: main_integration_error.m and any files it uses

Problem 6 [10 points] You are given the data file nbody.dat with positions of Jupiter, Saturn, Uranus, Neptune and Pluto.

<ul>
<li>The first column is time. Each time unit is 100 days. This file contains data up to time 5000, which gives 5000 × 100/365 ≈ 1369, 86 years.</li>
<li>Columns 2, 3, 4 contain the coordinates (x,y,z) of Jupiter, then next three columns contain the coordinates of Saturn, and so on. Distance is measured from the sun in astronomical units (AU), where 1 AU is the mean radius of the earth’s orbit.
3
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Do Not Share this document

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
A planet follows an elliptical orbit, which can be represented in a Cartesian (x, y) coor- dinate system by the equation

ay2 +bxy+cx+dy+e=x2. (1) Write a Matlab program that uses linear least squares to find for each of the planets the

coefficients a, b, c, d, e in (1). Your program should output them in the from abcde

Jupiter Saturn Uranus Neptune Pluto

Name your program main_orbit.m.

Note. If x and y are the x, y coordinates of a planet, and if you have computed a, b, c, d, e

correctly, the plots from

<pre>plot(x,y);
hold on;
[xs, ys] = meshgrid(min(x)-1:0.1:max(x)+1, min(y)-1:0.1:max(y)+1);
contour(xs, ys, a*ys.^2+b*xs.*ys+c*xs+d*ys+e-xs.^2, [0, 0], ’k--’, ’LineWidth’, 1);
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
should overlap.

</div>
</div>
</div>
</div>
