# Mo-Ahsan-Ahmad
In our practical approach, we imported the MNIST dataset using PyTorch and normalized it with a transformation (mean=0.5, standard deviation=0.5). The dataset included 60,000 training samples and 10,000 test samples. For efficient processing, we divided the data into 64-batch size. As a result, our training loader contained 938 (60000/64≈938), similarly the test loader contained 157 (10000/64≈157) batches of data, each containing 64 samples. Moving forward, we next initialized the weights for our Sum-Product Network (SPN) class and configured its architecture and settings for training and inference. This systematic methodology paved the way for implementing and experimenting with SPNs on the MNIST dataset.![image](https://github.com/rebelahsan/Mo-Ahsan-Ahmad/assets/66597497/e6d14c44-12cc-4f26-8187-896b0a9a4284)
