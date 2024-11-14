# Football Analysis and Visualization
## Description:  
Dataset : Roboflow  
Model : YOLOv8
Famework : utralytics,openCV,deepsort,supervision
API : Flask

## Install and setup:  
**1.Features**    

+Player and Ball Detection: Utilizes machine learning models to detect players, goalkeepers, referees, and the ball within video frames.  
+Team Classification: Classifies players into their respective teams using a custom team classifier based on cropped player images.  
+Player Tracking: Implements the Deep SORT algorithm for tracking player movements across frames.  
+Position Projection: Transforms player and ball positions from video coordinates to a standardized soccer pitch model.  
+Speed Calculation: Computes the speed of players by analyzing their movement over time on the pitch.  
+Visualization: Generates three types of output videos:  
+Tracking Video: Displays bounding boxes and IDs for players and the ball on the original video.  
+Player Projection Video: Shows the positions of players and the ball on a model soccer pitch.  
+Voronoi Diagram Video: Visualizes the area of influence for each player using Voronoi diagrams on the pitch.  

**2.Install** 
```pip install -r requirements.txt```  

**3.Customization**  
+API Keys: Replace 'YOUR_API_KEY' in the script with your actual API key for accessing the models.  
+Model IDs: Ensure that the model IDs used in get_model correspond to models you have access to.  
+Frame Stride and Rate: Adjust STRIDE, FRAME_RATE, and FPS to control the processing speed and output video frame rates.  

**4.Demo output**  

[](https://github.com/ductai07/-BTL-Python-Football-Analytics-/blob/dev/static/results/video_2/tracking_video.mp4)



