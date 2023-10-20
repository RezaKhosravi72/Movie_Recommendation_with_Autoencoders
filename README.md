# Movie Recommendation System with Stacked Autoencoders

### Project Overview:

This project showcases the development of a sophisticated movie recommendation system using deep learning techniques. Stacked Autoencoders (SAEs) play a central role in this project, enabling the system to understand user preferences and provide personalized movie recommendations.

#### Key Components and Steps:

1. Data Preparation:

- The project begins by importing and preparing data from the MovieLens dataset. While the MovieLens dataset is rich in movie-related data, it is not used in this project. Instead, the focus is on building a recommendation system based on user-movie interactions.

2. Data Conversion and Preprocessing:

- The user-movie interaction data is converted into Torch tensors, making it compatible with PyTorch, a popular deep learning framework.
- Ratings are processed to represent binary ratings: 1 (liked) or 0 (not liked).

3. Stacked Autoencoder Architecture:

- A Stacked Autoencoder neural network is designed, comprising multiple layers: an input layer (movies) and several hidden layers.
- The SAE's architecture is specifically tailored for capturing complex patterns in user-movie interactions.

4. Training the SAE:

- The SAE is trained using a combination of Mean Squared Error (MSE) loss and backpropagation.
- During training, the SAE learns the underlying structure of user preferences, reducing the reconstruction error in representing user-movie interactions.

5. Testing and Evaluation:

- The trained SAE is tested using a separate test dataset to assess its performance.
- The test loss is calculated to measure the accuracy of the recommendations, providing insights into the model's ability to predict user preferences.

#### Key Insights:

- Stacked Autoencoders are powerful tools for modeling and understanding user preferences in recommendation systems.
- The project demonstrates how deep learning techniques can be used to provide personalized recommendations, enhancing user experience.

#### Dataset Source:

The MovieLens dataset serves as the source for this project. Although the dataset contains extensive movie-related data, this project focuses on the user-movie interaction aspect. The MovieLens dataset is widely used in the field of recommendation systems.



On the whole, this project highlights the application of deep learning in the development of recommendation systems and showcases the capabilities of Stacked Autoencoders in understanding and predicting user preferences.
