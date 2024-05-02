# Mo-Ahsan-Ahmad

## COSC 5P77, SPN project under the guidance of Prof. Dr. Li.
### Dept. of Comp. Science, Brock University, ON, CA
In our practical approach, we imported the MNIST dataset using PyTorch and normalized it with a transformation (mean=0.5, standard deviation=0.5). The dataset included 60,000 training samples and 10,000 test samples. For efficient processing, we divided the data into 64-batch size. As a result, our training loader contained 938 (60000/64≈938), similarly the test loader contained 157 (10000/64≈157) batches of data, each containing 64 samples. Moving forward, we next initialized the weights for our Sum-Product Network (SPN) class and configured its architecture and settings for training and inference. This systematic methodology paved the way for implementing and experimenting with SPNs on the MNIST dataset.
Direct Link to access the code: https://github.com/rebelahsan/Mo-Ahsan-Ahmad/blob/main/SPN_Project_code_colab.ipynb
