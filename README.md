# Using SVM to classify the Rice Dataset: SVM model selection and tuning process

This project illustrates the process of justifying why the linear kernel performs better for Rice Dataset than other kernels.

The 'accuracy' term in this case refers to the classical measure, namely the count of all correctly predicted data points divided by the size of dataset.

It turned out that however we tuned the kernel parameter for radial, it still performed no better than the linear one; Or put it more precisely, 
it was asympototically approaching the performance of the linear kernel. 

More intuitively, it can be seen by plotting across features for the rice. Despite some random external derivations, the data points are largely linear separable.

To conclude, linear kernel is preferred in this case for its suitability, scalability and efficiency.


