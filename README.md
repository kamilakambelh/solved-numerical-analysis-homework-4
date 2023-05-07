Download Link: https://assignmentchef.com/product/solved-numerical-analysis-homework-4
<br>



<ul>

 <li>To get full credit, <em>you must write down sufficient intermediate steps</em>, only giving the final answer earns you no credit!</li>

 <li>Please make sure that your handwriting is recognizable, otherwise you only get partial credit for the recognizable part.</li>

</ul>

<ol>

 <li>Consider on [0<em>,</em>2]:</li>

</ol>

( <em>p</em>(<em>x</em>)         if <em>x </em>∈ [0<em>,</em>1]<em>,</em>

<em>s</em>(<em>x</em>) =

(2 − <em>x</em>)<sup>3          </sup>if <em>x </em>∈ [1<em>,</em>2]<em>.</em>

Determine <em>p </em>∈ P3 such that <em>s</em>(0) = 0. Is <em>s</em>(<em>x</em>) a natural cubic spline?

<ol>

 <li>Given <em>f<sub>i </sub></em>= <em>f</em>(<em>x<sub>i</sub></em>) of some scalar function at points <em>a </em>= <em>x</em><sub>1 </sub><em>&lt; x</em><sub>2 </sub><em>&lt; </em>·· <em>&lt; x<sub>n </sub></em>= <em>b</em>, we consider interpolating <em>f </em>on [<em>a,b</em>] with a quadratic spline.

  <ul>

   <li>Why an additional condition is needed to determine <em>s </em>uniquely?</li>

   <li>Define <em>m<sub>i </sub></em>= <em>s</em><sup>0</sup>(<em>x<sub>i</sub></em>) and <em>p<sub>i </sub></em>= <em>s</em><sup>|</sup><sub>[<em>x</em></sub><em>i<sub>,x</sub></em><em>i</em>+1<sub>]</sub>. Determine <em>p<sub>i </sub></em>in terms of <em>f<sub>i</sub>,f<sub>i</sub></em><sub>+1</sub>, and <em>m<sub>i </sub></em>for <em>i </em>= 1<em>,</em>2<em>,…,n </em>− 1.</li>

   <li>Suppose <em>m</em><sub>1 </sub>=              <em>f</em><sup>0</sup>(<em>a</em>) is given.       Show how</li>

  </ul></li>

</ol>

<em>m</em><sub>2</sub><em>,m</em><sub>3</sub><em>,…,m<sub>n</sub></em><sub>−1 </sub>can be computed.

<ul>

 <li>Let <em>s</em><sub>1</sub>(<em>x</em>) = 1+<em>c</em>(<em>x</em>+1)<sup>3 </sup>where <em>x </em>∈ [−1<em>,</em>0] and <em>c </em>∈ R. Determine <em>s</em><sub>2</sub>(<em>x</em>) on [0<em>,</em>1] such that</li>

</ul>

<em>,</em>

is a natural cubic spline on [−1<em>,</em>1] with knots −1<em>,</em>0<em>,</em>1. How must <em>c </em>be chosen if one wants <em>s</em>(1) = −1?

<ol>

 <li>Consider with <em>x </em>∈ [−1<em>,</em>1].

  <ul>

   <li>Determine the natural cubic spline interpolant to<em>f </em>on knots −1<em>,</em>0<em>,</em></li>

   <li>As discussed in the class, natural cubic splineshave the minimal total bending energy. Verify this by taking <em>g</em>(<em>x</em>) be (i) the quadratic polynomial that interpolates <em>f </em>at −1<em>,</em>0<em>,</em>1, and (ii) <em>f</em>(<em>x</em>). V. The quadratic B-spline <em>B<sub>i</sub></em><sup>2</sup>(<em>x</em>).</li>

   <li>Derive the same explicit expression of <em>B<sub>i</sub></em><sup>2</sup>(<em>x</em>) as that in the notes from the recursive Definition of B-splines and the hat function.</li>

   <li>Verify that d<u>d</u><em>x</em><em>B</em><em>i</em>2(<em>x</em>) is continuous at <em>t</em><em>i </em>and <em>t</em><em>i</em>+1.</li>

   <li>Show that only one <em>x</em><sup>∗ </sup>∈ (<em>t<sub>i</sub></em><sub>−1</sub><em>,t<sub>i</sub></em><sub>+1</sub>) satisfies d<u><sup>d</sup></u><em>xB</em><em>i</em><sup>2</sup>(<em>x</em><sup>∗</sup>) = 0. Express <em>x</em><sup>∗ </sup>in terms of the knots within the interval of support.</li>

   <li>Consequently, show <em>B<sub>i</sub></em><sup>2</sup>(<em>x</em>) ∈ [0<em>,</em>1).</li>

   <li>Plot.</li>

  </ul></li>

</ol>

<ol>

 <li>We proved a theorem on constructing B-splines from truncated power functions,</li>

</ol>

Verify it algebraically for the case of <em>n </em>= 2, i.e.

<em>.</em>

The above six problems weigh 4, 9, 4, 8, 10, and 5 points, respectively.

<h1>2           C++ programming</h1>

<ul>

 <li>Write a C++ subroutine for cubic-spline interpolation of the function</li>

</ul>

on evenly spaced nodes within the interval [−1<em>,</em>1] with <em>N </em>= 6<em>,</em>11<em>,</em>21<em>,</em>41<em>,</em>81. Compute the max-norm of interpolation errors at the nodes for each <em>N </em>and report the errors and convergence rates with respect to the number of subintervals.

Your algorithm should follow the example of interpolating the natural logarithm in the notes and your program must use an implementation of lapack.

Plot the interpolating spline against the exact function to observe that spline interpolation is free of the wide oscillations in the Runge phenomenon.

<ul>

 <li>(*) Write a Matlab subroutine to illustrate (1) by plotting the truncated power functions and building a table of divided difference where the entries are figures instead of numbers. See the hints in Section 4.</li>

</ul>

The two programming assignments weigh 14 and 6 points, respectively. Problem (b) is for extra credit. The total number of points of this homework is thus 54(+6).