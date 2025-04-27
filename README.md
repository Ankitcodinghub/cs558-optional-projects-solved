# cs558-optional-projects-solved
**TO GET THIS SOLUTION VISIT:** [CS558 Optional Projects Solved](https://www.ankitcodinghub.com/product/cs558-optional-projects-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;121757&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS558 Optional Projects Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
1) Image Data Association (2.5 Points Max)

The goal of the assignment is to apply an unsupervised clustering algorithm to segregate a set of images observing different scenes. This is similar to the image classification problem in Assignment 4, in the sense that you need to build a global image representation and use that representation to associate images. However, instead of assigning a single label from a predetermined number of possible labels, you will perform unsupervised clustering to partition the set of all images into disjoint subsets.

a) Download the datasets fountain-P11, Herz-Jesu-P8, entry-P10 from the Strecha MVS evaluation website and form a single aggregated dataset comprised of all the images in the three datasets (i.e. a superset). For this problem you will only use the images and discard other info.

c) Implement a mean-shift unsupervised clustering algorithm to partition the aggregated dataset into disjoint image sets. You will need to execute the mean-shift algorithm multiple times using each of the images in the superset as a starting point and record the convergence “mean” obtained by the algorithm. Images converging to the same “mean” are considered to belong to the same cluster.

Include in your report the attained clusters; discuss your choice of image descriptor as well as the mechanisms used for parameter tuning of your clustering algorithm.

2) Segmentation (5 Points Max)

The goal of this assignment is to develop a framework to perform segmentation of a specific foreground object. The object of interest is a foreground tractor found in the images of the Castle-19 dataset.

The desired output is a pixel-wise segmentation for each of the images in the dataset.

Include in your report the attained segmentation and provide a detailed discussion of your solution.

3) Advanced Image Filtering (7.5 Points Max)

The goal of this assignment is to implement a multi-dimensional Gaussian filter using the Permutohedral Lattice. This advanced technique was NOT covered in the course slides, hence you will need to research and implement it. Develop a

MATLAB implementation (no other languages will be considered, no exceptions) based on the description in http://graphics.stanford.edu/papers/permutohedral/

a) Compare results of using a permutohedral-based 2D filter with with spatial std dev of 10 pixels on an RGB image vs running the typical 2D filter in each channel independently in order to aggregate results.

b) Deploy 5D filtering using pixel color and position (RGB+XY), define spatial std dev of 5, 10, and 10 pixels and RGB std dev of 10, 20, 30 intensity value. Experiment on any of the training outdoor images of the fourth assignment and test the nine possible combinations.

Notes: There are existing implementations available online, you are encouraged to use them for benchmarking/testing your own implementation (if you do so, include the comparative results in your report). The goal of this assignment is NOT for you to simply translate the code of an existing implementation into MATLAB, but to understand the material and implement it. There is NO REQUIREMENT to implement data access through a hash table as this is only an efficiency optimization.
