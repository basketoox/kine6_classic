# kine6_classic
forward and inverse kinematics (geometry approach) of classic 6 dof robot arm  
c example code

**the DH frame**  
![Alt text](Classic6dof_DH.PNG?raw=true)

**demo**  
execute program
```
./kine6_classic
```
home pose
> FK(q0)  :=< 0.020000, 0.000000, 0.900000, 0.000000, -0.000000, 0.000000 >

continue
> quit 'q' or continue 'c' ?c  
c

input joint angle q(deg)
> input q:=0 0 90 0 90 0

FK(q)
> q       :=< 0.000000, 0.000000, 1.570796, 0.000000, 1.570796, 0.000000 >  
FK      :=< 0.410000, -0.000000, 0.370000, -3.141593, -0.000000, 3.141593 >

IK 8 solutions 
> q[0]    :=< 0.000000, 0.000000, 1.570797, -0.000000, 1.570796, -0.000000 >  
FK(q[0]):=< 0.410000, -0.000000, 0.370000, -3.141593, -0.000000, -3.141593 >  
q[1]    :=< 0.000000, 0.000000, 1.570797, 3.141593, -1.570796, 3.141593 >  
FK(q[1]):=< 0.410000, 0.000000, 0.370000, -3.141593, -0.000000, -3.141593 >  
q[2]    :=< 0.000000, 1.543401, -1.404514, -0.000001, 3.002706, -0.000001 >  
FK(q[2]):=< 0.410000, -0.000000, 0.370000, -3.141593, -0.000000, -3.141593 >  
q[3]    :=< 0.000000, 1.543401, -1.404514, 3.141592, -3.002706, 3.141592 >  
FK(q[3]):=< 0.410000, 0.000000, 0.370000, -3.141593, -0.000000, -3.141593 >  
q[4]    :=< -3.141593, -0.303567, -1.057672, -0.000000, -1.780354, 3.141593 >  
FK(q[4]):=< 0.410000, -0.000000, 0.370000, -3.141593, -0.000000, -3.141593 >  
q[5]    :=< -3.141593, -0.303567, -1.057672, 3.141593, 1.780354, -0.000000 >  
FK(q[5]):=< 0.410000, -0.000000, 0.370000, -3.141593, -0.000000, -3.141593 >  
q[6]    :=< -3.141593, -1.483253, 1.223954, -0.000001, -2.882294, 3.141592 >  
FK(q[6]):=< 0.410000, -0.000000, 0.370000, -3.141593, -0.000000, 3.141593 >  
q[7]    :=< -3.141593, -1.483253, 1.223954, 3.141592, 2.882294, -0.000001 >  
FK(q[7]):=< 0.410000, -0.000000, 0.370000, -3.141593, -0.000000, -3.141593 >  

quit
> quit 'q' or continue 'c' ?q  
q
