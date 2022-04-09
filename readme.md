UE4、UNITY、WT901C，XYZ轴欧拉角旋转方式不同。

UE4不能使用WT901C的欧拉角。

UNITY可以使用欧拉角，但是需要变换。

x = unity_z

y = -unity_x

z = -unity_y


四元数可以使用，但是需要变换。

q0 = unity_w = ue4_w

q1 = unity_z = -ue4_y

q2 = -unity_x = -ue4_x

q3= -unity_y = -ue4_z
