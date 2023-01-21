# Knee_Bend_Detection
# Computer Vision using Mediapipe Python
Tasks :                 
- Write a robust algorithm to calculate successful rep count for knee bend exercise (Use mediapipe  pose model for this task)
- Add a holding timer limit of 8 sec
- Include feedback logic in your code, which should be triggered only when a person fails to stay in holding position till 8 sec.
- Feedback message - “Keep your knee bent”
- Run your code with provided video and upload the full recorded pose detected video in drive.
- Dummy frames have been added in between the video, to replicate the fluctuation behaviour of keypoints, you can add a logic to handle fluctuations ( rapid fluctuations should not affect the algorithm flow.).
- Report the performance of the user ( stat of bendness).


Exercise description -  
- Leg should be bent to start timer
- Slight inward bend is enough to start the timer. ( <140 deg)
- After a successful rep, the person has to stretch his/her leg straight.
- No restriction for back angle
- Consider leg closer to camera as exercised leg 

File Resource: https://colab.research.google.com/drive/1xOJUWfd0GQwpopA6gfyoqU9bS5uDV3ak?usp=share_link
