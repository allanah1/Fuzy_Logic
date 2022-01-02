# Fuzzy_Logic
This project involved being able to determine the speed and steering angle of a robot based on rules set by the programmer.
These rules were dependent on 2 precedents - distance to an object and angle between the robot and the object.
Mamdani inferencing and centroid of area defuzzification were used.
The Rules included:
 If distance is near and angle is small, then speed is medium speed.
 If distance is near and angle is medium, then speed is slow speed.
 If distance is near and angle is large, then speed is slow speed.
 If distance is near and angle is small, then speed is medium speed.
 If distance is far and angle is small, then speed is fast speed.
 If distance is far and angle is medium, then speed is fast speed.
 If distance is far and angle is large, then speed is fast speed.
 If distance is very far and angle is small, then speed is maximum speed.
 If distance is very far and angle is medium, then speed is maximum speed.
 If distance is very far and angle is large, then speed is maximum speed.
 If distance is near and angle is small, then steering is sharp turn.
 If distance is near and angle is medium, then steering is sharp turn.
 If distance is near and angle is large, then steering is very sharp turn.
 If distance is far and angle is small, then steering is mild turn.
 If distance is far and angle is medium, then steering is mild turn.
 If distance is far and angle is large, then steering is mild turn.
 If distance is very far and angle is small, then steering is mild turn.
 If distance is very far and angle is medium, then steering is mild turn.
 If distance is very far and angle is large, then steering is mild turn.
