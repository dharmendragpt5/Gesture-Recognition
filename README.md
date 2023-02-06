
<h2>Gesture Recognition Case Study</h2>

    Dharmendra Kumar – Group Facilitator
    Ashwin Kumar h

In this group project, you are going to build a 3D Conv model that will be able to predict the 5 gestures correctly. Please import the following libraries to get started.
Problem Statement

In this group project, you are going to build a 3D Conv model that will be able to predict the 5 gestures correctly. Please import the following libraries to get started. Problem Statement

Imagine you are working as a data scientist at a home electronics company which manufactures state of the art smart televisions. You want to develop a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote.

<table>
<thead>
<tr>
<th>Gesture</th>
<th>Corresponding Action</th>
</tr>
</thead>
<tbody>
<tr>
<td>Thumbs Up</td>
<td>Increase the volume.</td>
</tr>
<tr>
<td>Thumbs Down</td>
<td>Decrease the volume.</td>
</tr>
<tr>
<td>Left Swipe</td>
<td>'Jump' backwards 10 seconds.</td>
</tr>
<tr>
<td>Right Swipe</td>
<td>'Jump' forward 10 seconds.</td>
</tr>
<tr>
<td>Stop</td>
<td>Pause the movie.</td>
</tr>
</tbody>
</table>

The data is in a zip file. The zip file contains a 'train' and a 'val' folder with two CSV files for the two folders. These folders are in turn divided into subfolders where each subfolder represents a video of a particular gesture. Each subfolder, i.e. a video, contains 30 frames (or images). Note that all images in a particular video subfolder have the same dimensions but different videos may have different dimensions. Specifically, videos have two types of dimensions - either 360x360 or 120x160 (depending on the webcam used to record the videos). Hence, you will need to do some pre-processing to standardise the videos.

Each row of the CSV file represents one video and contains three main pieces of information - the name of the subfolder containing the 30 images of the video, the name of the gesture and the numeric label (between 0-4) of the video.

Your task is to train a model on the 'train' folder which performs well on the 'val' folder as well (as usually done in ML projects). We have withheld the test folder for evaluation purposes - your final model's performance will be tested on the 'test' set.
