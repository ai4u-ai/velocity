## Train algorithm:

<iframe width="560" height="315" src="https://www.youtube.com/embed/bbxKzSOaHdo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Select one of the preselected algorithms and the data set you want to be training on. Select the number of epochs and the number of steps per epoch and click train.
You can monitor the training job in the training jobs section by selecting the training job in the dropdown. You can choose a metric (loss, accuracy) to visualise in the dash board.
You can as well open tensorboard to monitor the training job.
You have access to all the loggs from the training job in the lower part of the same page.

Options:

-Type of algo: The type (architecture) of algorithm you wish to train.
-Images height and width: The images will be scaled before training. The algorithm input shape will be adjusted accordingly to avoid exceptions.
-Test train split: The percentage of the data set you wish to keep for validation. This will not be used during training. If there are not sufficient images for validation it will be not be
executed and you will see it in the logs.
-Destination path: Where all the files will be stored. You can always ftp into the instance to retrieve the files.
-Data Set: choose the data set you wish to use from the dropdown
-Training epochs: The number of epochs you wish to train the algorithm. (Epoch is a full cycle through the entire data (training) set)
-Steps per epoch: The number of steps you wish to train per epoch. (Steps or iterations is the number of batches needed to complete one epoch)
-Start from previous training: If you wish to continuously train a model you can select a previous straining session. Velocity will load the checkpoints from the selected training session and will start training from
there. (Note that the session files are stored to the file system. If you manually delete them from the file system it is impossible to restore them.)
-Training Type : From scratch you will start with a brand new algorithm with randomly populated weights. 
                 Transfer learning: Velocity will download a pre-trained model from a model zoo. Construct a new top and train it.  
-Class mode: 
                Categorical: Supports multi-label output
                Binary: Supports binary output
                Input: Label is equal to the input. Used in autoencoders. 

## Use the trained model:


<iframe width="560" height="315" src="https://www.youtube.com/embed/9vtxXtn5kMc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
Once the status of the training is end you can go to the publish section and select the training session you are interested in and download model,labels,checkpoints,data set.