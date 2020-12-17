# Computer-Vision
### TITLE :- Duplicate Instance Detection in Multiview and Multiscale Scenario 


### DATA :- 
https://www.cs.columbia.edu/CAVE/software/softlib/coil-100.php


### Image.csv :- 
Images pairs of all the objects which add upto half a million , paired with the absolute difference of angle

### train.csv :- 
Randomly chosen 80% of data.

### test.csv :- 
Rest 20% of the data.

### Phase-2 :-
All the content we submitted for phase 2. Includes a pdf of Literature Survey by all the team Members, a Jupyter Notebook Visualizing all the data.


### Phase-3 :-
All the Content we submitted for phase-3. Includes 
1) A notebook(Traditional.ipynb) visualizing SIFT, ORB and Fundamental Matrix Estimation between Images.
2) A notebook(Siamese Network.ipynb), where one object images (obj1), has been paired up with each other forming a total of 5,184 pairs. 


### final.ipynb :-
* It is the final Netwrok which was trained on 80% of the data i.e; 414,720 image pairs.
* Pytorch was Used.
* It's basically a regression task
* Used RMSE loss
![Network](network.PNG)


### CONTENT :- 
There are 7,200 images of 100 objects. Each object was turned on a turnable through 360 degrees to vary object pose with respect to a fixed color camera. Images of the objects were taken at pose intervals of 5 degrees. This corresponds to 72 poses per object. There images were then size normalized. Objects have a wide variety of complex geometric and reflectance characteristics.

### What problem will your Computer Vision solution solve, and for whom?
In a multi view or multi scale scenario, we tend to detect multiple instances of the same object. At
times, this leads to double counting or redundancy for downstream processing modules. One
example can be detecting damages in vehicles from images captured from different angles.

### What value will it provide them? What are their pain points?
The repair cost can be exaggerated if the solution is not able to recognize that the two different
images point to the same damage. The main pain point will be to identify duplicate instances of
the same object, when captured from multiple angles. Our approach could also be used as a
foundation for many other applications.

### How big is the potential market?
Identifying duplicate instances of the same Object could be used in most of the vehicle insurance
coverage companies. Which is a big market all over the world, right now. Since there are many
similar problems that can be addressed with our approach, the market could be even bigger.
