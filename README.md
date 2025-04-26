# csc420-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CSC420 Assignment 1 Solved](https://www.ankitcodinghub.com/product/intro-to-image-understanding-csc420-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116888&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC420 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
Instructions for submission:

• Please write a document (pdf format) with your solutions.

• For the coding part: Please include visualization results of each step. Please also attach your code in the document. E.g. for each relevant question, first show its image results, then attach the code at the end. If you only submit the code without the visualization figures, you will get at most half of the full mark.

Written Part (Max points: 6):

1. Assume we are doing convolution for an image with size H × W and a filter with size

K × K:

(a) [0.5 point] What is the number of operations required for performing 2D convolution? E.g. how many add and multiplication operations in total? You do not need to consider padding.

(b) [0.5 point] What is the number of operations required for performing convolution with a separable filter? Assume this filter K × K is separable. You do not need to consider padding.

2. Filter Separation:

(a) [1 point] Is a vertical derivative, , of a Gaussian filter G a separable filter? Analyze both the isotropic and anisotropic case.

(b) [1 point] Is a Laplacian of Gaussians (LoG) a separable filter?

(c) [1 point] Generally speaking, given a 3×3 filter, show that under which condition it is separable.

3. [1 point] We know that convolution is commutative. Is cross correlation also commutative? Please provide a proof. You can do your analysis in 1D.

4. [1 point] If I first convolve an image with a Gaussian filter with σ = 1, and then convolve the output with a Gaussian with σ = 2, this gives an equivalent result as if I just convolve the image with a Gaussian with what σ?

Coding Part (Max points: 9):

1. Convolution Operation:

(a) [2 points] Write your own function for computing convolution of the 2D (grayscale) image and a 2D filter. If the image is not grayscale, convert it to grayscale inside your function (you can use built in functions for the conversion). The function should accept a 2D image and a 2D filter (you can assume it’s a square matrix with odd height and width), and return the resulting matrix obtained by convolving the input image with the given filter. Make the output matrix be the same size as the input image. Be careful to correctly deal with the border of the image – the easiest way to do this is to “zero-pad” the image prior to convolution. Please include a visualization of the result, when convolving the included waldo.png with

 0 0.125 0 

the filter 0.5 0.5 0.125. Please show the original image and the image

0 0.5 0

after convolution.

(b) [0.5 point] Write a function to verify that the above filter is separable or not.

(c) [0.5 point] Write a faster convolution function leveraging the fact that the filter is separable. If the above filter is separable, use this one. If not, choose another separable filter, and visualize the result when convolving waldo.png with the filter. Show the time comparison.

(d) [1 point] Assume the above filter is separable, but now you want to perform cross correlation instead of convolution. Can you still take advantage or separability for correlation? If so, please implement it, and include a visualization of the result, when performing cross correlation on waldo.png with the filter

 0 0.125 0 

0.5 0.5 0.125.

0 0.5 0

2. [1 point] Convolve the attached waldo.png with a (2D) Gaussian filter with σ = 1 and visualize the result (display the filter and the result of the convolution). You should implement the Gaussian filter generation code with kernel size and σ as input. You can use your implemented convolution code or built-in functions for convolution operation. Include the visualized result in the assignment’s document.

3. Gradients Computation:

(a) [1 point] Compute magnitude of gradients for the attached images waldo.png and template.png. Write your own function to do this. You can use the built-in convolution function or your own implementation. Include the visualized result in the assignment’s document.

(b) [1 point] Write a function that localizes the template (template.png) in the image waldo.png based on the magnitude of gradients. Write your own function to do this. Visualize the result and include it in the assignment’s document.

4. [2 points] Implement the Canny edge detector yourself. You do not need to do hysteresis thresholding. However, do perform non-maxima suppression. Please visualize your results on waldo.png.
