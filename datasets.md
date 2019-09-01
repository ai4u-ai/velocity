## Create Data Sets:

<iframe width="560" height="315" src="https://www.youtube.com/embed/XjjC4A37Sy0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
Use the tool to create data sets by dragging and dropping annotations and or other data sets. A data set name is generated but you can change it if you wish.
The tool will inform you during the creation of the data set how many labels there are and how many annotations per label.
This is important as you don't want you data to be unbalanced. Make sure that you have similar amount of annotations per class.

## Transform data sets:

Different algorithms need a different type of data format and annotation. For instance a classification algorithm take the full image as an input and provides the probability of a class as a prediction.
An object detection algorithm will predict not only the class but the bounding box of this class. Our tool permits you to transform your annotations to both use cases.
You are able as well to just download the transformed data set and use it. 


<iframe width="560" height="315" src="https://www.youtube.com/embed/_UQagNYNses" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## Transform size and train validate split:
You can indicate if you wish to transform the size of the images in the data set. The train validation split can be indicated as a percentage. Velocity will do the needed conversions and splitting and will
produce the data set at the destination path indicated in the details. You can download it from there or mount this path to a bucket or your local file system.