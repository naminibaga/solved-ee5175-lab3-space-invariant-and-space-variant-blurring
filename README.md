Download Link: https://assignmentchef.com/product/solved-ee5175-lab3-space-invariant-and-space-variant-blurring
<br>
Space-invariant and space-variant blurring

<ol>

 <li><strong>Space-invariant blurring </strong>Perform Gaussian blurring on pgm with standard deviation <em>σ</em>. Assume space-invariant blur and a kernel of size <em>d</em>6<em>σ+</em>1<em>e×d</em>6<em>σ+</em>1<em>e</em>. Observe the outputs for these values of <em>σ</em>: 1.6, 1.2, 1.0, 0.6, 0.3 and 0.0.</li>

 <li><strong>Space-variant blurring </strong>Now assume the blur to be space-variant, i.e. the standard deviation varies for each pixel. Consider the distribution of <strong><em>σ </em></strong>to be</li>

</ol>

´

<strong><em>σ</em></strong>(<em>m</em>,<em>n</em>)<em>=A</em>exp,                         0<em>≤m</em>,<em>n</em><em>≤N</em><em>−</em>1

<em>B</em>

with

µ<em>N N</em>¶

<strong><em>σ </em></strong>,          <em>=</em>2.0 and <strong><em>σ</em></strong>(0,0)<em>=</em>0.01,

2   2

where <em>N</em><em>×N </em>is size of the image and pixel indices are in the range [0,<em>N</em><em>−</em>1]<em>×</em>[0,<em>N</em><em>−</em>1]. Find <em>A </em>and <em>B</em>, and create the matrix <strong><em>σ</em></strong>. Perform Gaussian blurring on Globe.pgm using the values of <strong><em>σ</em></strong>(<em>m</em>,<em>n</em>).

<ol start="3">

 <li>Blur pgm using

  <ul>

   <li>space-invariant blur code of part 1 with <em>σ=</em>0, and</li>

   <li>space-variant blur code of part 2 with <strong><em>σ</em></strong>(<em>m</em>,<em>n</em><sup>)</sup><em>=</em>0 for <sup>0</sup><em>≤m</em>,<em><sup>n</sup></em><em>≤</em><em><sup>N</sup></em><em>−</em>1.</li>

  </ul></li>

</ol>

Verify that the blurred images of the above two steps are same.

–end–