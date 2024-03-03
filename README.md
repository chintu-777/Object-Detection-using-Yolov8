# YOLOv8 Object Detection for Video Surveillance

The YOLOv8 algorithm capitalizes on the strengths of the YOLOv8 architecture to enhance object detection performance. This project focuses on real-time analysis of surveillance camera-generated video data, introducing an automated detection approach that leverages smart networks and algorithms.

## Project Setup

### Step 1: Access Google Colab

1. Open your web browser and go to [Google Colab](https://colab.google/)

### Step 2: Open a New Notebook

1. Click on "File" in the top left corner.
2. Select "New Notebook" from the drop-down menu.

### Step 3: Mount Google Drive

In the new notebook, run the following code to mount your Google Drive:

`from google.colab import drive`
`drive.mount('/content/gdrive/')`


This will prompt you to click on a link, sign in to your Google account, and copy a verification code.

### Step 4: Navigate to Project Directory

Change to the directory where your YOLOv8 session is stored. Modify the path accordingly based on your project's location in Google Drive.

`cd /content/gdrive/MyDrive/your_project_directory`


### Step 5: Install Ultralytics Library

`!pip install ultralytics`

Now, you have successfully set up your Google Colab environment and navigated to the directory where your YOLOv8 project is stored on Google Drive. You can proceed with the remaining steps mentioned in the [main](./main.ipynb)  for your project.

## Notes

- Ensure that your Google Colab is configured correctly with the necessary dependencies.
- Make sure to provide the correct file paths and names in the code.
- Adjust hyperparameters and configurations in the code as needed.

## License

This project is licensed under the [License Name] - see the [LICENSE.md](./LICENSE) file for details.

