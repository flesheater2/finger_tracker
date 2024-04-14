# finger_tracker
Tracks location in terms of co-ordinate of  fingers.
Library used for finger tracking : Mediapipie 
Multiple use cases of the program are available, which will be uploaded very soon.

Moving a step further from hand detection ; data of location of finger is extracted from 'results.multi_hand_landmarks' and is stored in a variable 'handlandMarks'. Still the data is very complex so further the x-y position is accesed and stored in a new variable 'landmarks' which is further fed to an empty array 'han'. The data from han is now used to draw circles for finger tracking purpose.

THE PROGRAM IS CASE SENSITIVE TO FRAME SIZE...MINE IS WORKING WITH 640 X 480 ('width = 640', 'height = 480').
