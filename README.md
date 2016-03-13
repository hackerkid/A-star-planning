# A-star-planning

<b> Prerequisites</b>
- Python
- OpenCV
- Numpy
- Matplotlib

This is extended implementation of A-star algorithm.

For basic knowledge of A-star , one can refer following links : https://en.wikipedia.org/wiki/A*_search_algorithm

Now,  we are trying to guide a robot which has dimensions, so such robot should avoid obstacles. It would be better if that robot searches a path which is minimum at delta distance from obstacles.

Input Images

![alt text](1.jpg)

![alt text](2.jpg)

![alt text](3.jpg)

For this we preprocess our input images to create clearances for robot.

![alt text](Clearance/1.jpg)

![alt text](Clearance/2.jpg)

![alt text](Clearance/3.jpg)

Now on the basis of these clearnace values, we deviced our cost function as normal distribution of this clearance value.

After applying A* on these images , we get following output:

Output Images:

![alt text](output/1.jpg)

![alt text](output/2.jpg)

![alt text](output/3.jpg)
