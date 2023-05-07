Download Link: https://assignmentchef.com/product/solved-mast30025-lab-8
<br>
<ol>

 <li>Consider a dataset where each sample has a response and two factors, which have 2 and 3 possiblelevels respectively. We take 2 samples from each possible combination of factor levels. We model this with a less than full rank model with one parameter for the overall mean, and one parameter for each level of each factor which adjusts the overall mean additively. Write down the linear model in both equation and matrix form.</li>

 <li>Let</li>

</ol>

<em> .</em>

<ul>

 <li>Show that <em>r</em>(<em>A</em>) = 2.</li>

 <li>Find two distinct conditional inverses for <em>A</em>.</li>

</ul>

<ol start="3">

 <li>Show that <em>A </em>= <em>A</em>(<em>A<sup>T</sup>A</em>)<em><sup>c</sup>A<sup>T</sup>A</em>. You may use the result that if <em>A<sup>T</sup>A </em>= 0, then <em>A </em>= 0. (<em>Hint: Consider the matrix A </em>− <em>A</em>(<em>A<sup>T</sup>A</em>)<em><sup>c</sup>A<sup>T</sup>A</em>.)</li>

 <li>It is known that toxic material was dumped into a river that flows into a large salt-water commercialfishing area. We are interested in the amount of toxic material (in parts per million) found in oysters harvested at three different locations in this area. A study is conducted and the following data obtained:</li>

</ol>

Site 1       Site 2       Site 3

15             19             22

26             15             26

<ul>

 <li>Write down the linear model in matrix form.</li>

 <li>Write down the normal equations.</li>

 <li>Find a conditional inverse for <em>X<sup>T</sup>X</em>.</li>

 <li>Find a solution for the normal equations.</li>

</ul>

<ol start="5">

 <li>In a manufacturing plant, filters are used to remove pollutants. We are interested in comparingthe lifespan of 5 different types of filters. Six filters of each type are tested, and the time to failure in hours is given in the dataset (on the website) filters (in csv format).

  <ul>

   <li>Use the csv function to read the data. Then convert the type component into a factor.</li>

   <li>Construct <em>X </em>and <strong>y </strong>matrices for this linear model.</li>

   <li>Using the algorithm given in the lecture slides, find a conditional inverse for <em>X<sup>T</sup>X</em>.</li>

   <li>Use ginv to find another conditional inverse for <em>X<sup>T</sup>X</em>.</li>

   <li>Verify that <em>X</em>(<em>X<sup>T</sup>X</em>)<em><sup>c</sup>X<sup>T </sup></em>is the same for your two conditional inverses.</li>

   <li>Find two solutions for the normal equations.</li>

   <li>Express one of your solutions in terms of the other.</li>

   <li>Write down a form for all solutions to the normal equations.</li>

  </ul></li>

 <li>Show that <em>A<sup>T</sup>A </em>= 0 ⇒ <em>A </em>= 0.</li>

</ol>

Hence show that <em>AB </em>= <em>AC </em>⇔ <em>A<sup>T</sup>AB </em>= <em>A<sup>T</sup>AC</em>.<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2022/04/558.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2022/04/558.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>