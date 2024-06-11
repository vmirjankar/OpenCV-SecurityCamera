# OpenCV_Security_Camera

NAME: VED VISHAL MIRJANKAR <br/>
PROJECT: SECURITY CAMERA SYSTEM USING PYTHON <br/>

ABSTRACT: <br/>
Creating a Security Camera System using the OpenCV library in Python where the webcam will detect a face and will start recording until the face is in the frame. After the recording is complete, the video will be sent to a folder. 

BRIEF PROCESS DESCRIPTION:<br/>
•	Imported all the required packages. <br>
•	Used the predefined classifier: Haarcascade which detects objects in images. In this case, it detects the face and body. <br>
•	Wrote the Security Camera Logic: <br>
1.	Converted frame to grayscale.
2.	Checks if there is any face or body in the frame.
3.	If a face is detected, it will start the video recording.
4.	If a face is not detected after being detected previously in the same recording, it will wait for 5 seconds before it stops recording. This process is done to ensure one long video recording instead of many short ones as without the condition, the recording will stop and start as soon as a face is not detected.
5.	If a face is not detected after 5 seconds, it will create the video recording and send it to a folder.










