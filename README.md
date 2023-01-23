# Neural Style Transfer on video
The project is created to show how can we use the Neural Style Transfer algorithm on the video. 
The repository also cotains video and style image used in the Notebook. You can clone the repository and run in your local machine but also, open in Google Colab and import given files in order to get the shown result.

The given code follows the following steps:
1. Load model
2. Read style image and preprocess
3. Read the frame of the video and preprocess it
4. Apply Neural style transfer to the frame
5. Reapeat 3 and 4 till the last frame and save it using OpenCV VideoWriter function
