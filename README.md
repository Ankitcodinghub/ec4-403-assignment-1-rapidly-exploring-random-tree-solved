# ec4-403-assignment-1-rapidly-exploring-random-tree-solved
**TO GET THIS SOLUTION VISIT:** [EC4.403 Assignment 1-Rapidly exploring Random Tree Solved](https://www.ankitcodinghub.com/product/ec4-403-assignment-1-rapidly-exploring-random-tree-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95463&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EC4.403 Assignment 1-Rapidly exploring Random Tree Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Rapidly-exploring Random Tree (RRT)

The goal of this assignment is to implement the RRT path planning algorithm for a robot. The robot is to navigate a two dimensional space, avoiding known locations with obstacles, traveling from its initial location to a goal location. Given localization information (robot’s initial position, obstacle location, goal location), your task is to implement a path planning decision maker to drive the robot from its initial position to the desired location.

Specifically, the problem can be formed as follows: Consider a 2D grid instantiated with different kinds of obstacles (for instance, geometrical shapes like Rectangles, Circles, Triangles or a combination of any of the above 2/3). Assign a start and end point on this grid. You must implement the RRT algorithm for two cases, (1) Holonomic Robot and (2) Non-Holonomic Robot.

You must submit two videos for each of the above cases, showing the evolution of your graphs. The first one should showcase only the platform center velocity, that is, the trajectory of the center of the robot. Something like this:

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Your second video should show the individual wheel trajectories (evolution of all the wheels in all the possible paths). Ensure that no collisions happen near the boundaries and use methods explained in the class for this. Also, the trajectories for each individual wheel must appear consistent. The left wheel should not go haywire while the right wheel’s trajectory is smooth – they must be in sync with one another. If you code the algorithm right, the kinematics will guarantee this! 🙂

You can refer to this video, which shows the trajectories plotted for all three wheels of the robot. Although this is done in 3D, and you need to implement this for only two dimensions.

Hence, there will be 4 videos in total: 2 for holonomic and 2 more for non-holonomic. For each case, one video will show platform center velocity and the other, the individual wheel trajectories. You should save all the graphs, combine them into a video and upload it to your OneDrive or Google Drive, and include that link in your report. You should also include a few pictures of the graphs in your report, along with the video links. For generating videos from individual graphs, you may use this script.

The more complex the grid, the more appreciation you get! At the same time make sure you don’t fill the entire grid with obstacles. The obstacles can be made complex by combining different shapes like circles, rectangles or any other geometric shapes you prefer. Also, fix the size of your robot and increase the size of the obstacles accordingly near the boundaries (as discussed in the class).

Deliverables:

<ul>
<li>Code for both the cases. You can use Python, MATLAB or whichever language you are comfortable with. Please ensure the code is well written, and we can ask you to explain certain snippets of it during the evaluations.</li>
<li>Two graphs as explained above, for each case.</li>
<li>A report summarising your understanding of the algorithms and explaining the results.</li>
<li>Put all these files in a folder 〈TeamName〉, zip it, and submit it on moodle.
Feel free to reach out to the TA’s for any queries. All the best, and may the Force be with you.
</li>
</ul>
</div>
</div>
</div>
