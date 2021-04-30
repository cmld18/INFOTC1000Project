# Object Position Calculation
## INFOTC 1000 Assignment
### This was created using Python.

```
#ObjectPosnCalc

#Information from user
initial_Position = float(input("Enter the object's initial position: "))
initial_Velocity = float(input("Enter the object's initial velocity: "))
acceleration = float(input("Enter the object's acceleration: "))
time_Passed = float(input("Enter the time that has passed: "))

#Calculate using User Information
final_Position = initial_Position + initial_Velocity * time_Passed + 0.5 * acceleration * time_Passed **2


#Final Position Output
print("Final position is", final_Position)
```
