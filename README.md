# AIforSea_Grab_Submission
Hello, this my submission to the competition held by [Grab](https://www.aiforsea.com/).

This competition has three challenges and one of them is on Computer Vision, the [Cars Dataset](https://ai.stanford.edu/~jkrause/cars/car_dataset.html) from Stanford University is given as a dataset.

You need to build you classifier on this dataset.

I build a model using Progressive Image Resizing technique and I have started with a 64x64 image size and then increasing the size 128x128, 256x256 and finally to 512x512, and it is on top of the classic resnet50 model.

Since I have computational constraints otherwise the same will be done with resnet152 model, which would have given more accuracy.

Programming language --> Python

Deep Learning Framework --> Fast.ai

Image reading/writing --> Opencv

other Python packages are like scipy, numpy, pandas etc.

To achieve the same results you have to run each cell in the Jupyter Notebook.
