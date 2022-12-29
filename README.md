# Gym_Counters_Pushups_Pullups_Squat_Counter
### A squat is something when a human switches between sitting and standing position
### Similarly a complete pullup cycle will be called when a hanging person folds his/or her elbows and then straightens it.
### Similarly any exercise that has extreme positions can be used in this counter.
##### We simply dump positional value of various joints in a human body in one file for one given position, and values of other extreme pose in second csv file. (this could be done by file:g_bootstrap_images.py)

### The logic behind it is: we are using knn to match the value of distance of all body joints in a given video frame to the csv files(that are basically two classes: i)sitting or ii)standing : in case of squats). Just use a simple counter or flags that given the number of switches b/w the classes.
- To run the code use the last file : i_classification.py. It requires video file path to work upon. as well as csv. Use same CSV file for the respective exercise. For example, you canot use sitting and standing csv file for a pull up video. :P.


Using media pose and KNN algorith, I have created gym counter for three exercises. Pull-ups, push-ups and Squats. 
![squats-out](https://user-images.githubusercontent.com/96057833/209930146-daec351c-a81c-42ea-b29b-4595b11c798f.gif)
![pushups-3reps](https://user-images.githubusercontent.com/96057833/209930511-759a92c5-4e7a-49ad-946e-415192a80c38.gif)
![pull-ups](https://user-images.githubusercontent.com/96057833/209931113-c173df2f-42f4-4049-8a78-c388b2200191.gif)
![pull-ups-my-out](https://user-images.githubusercontent.com/96057833/209931641-83d0dad1-99ea-4bd4-8bb6-3248e9583975.gif)
