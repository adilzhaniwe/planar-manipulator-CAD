In this folder you can find files of 3D model of printed parts used in [the project](https://ieeexplore.ieee.org/document/8700392)

Parts of the planar manipulator:

* Servo motors (x5) – Dynamixel MX-28 CAD was taken from https://grabcad.com/library/dynamixel-servo-mx-28t-1


* Hip **"short_hip.sldprt"**(x4) that connect servo motors


* Base **"base_new.sldprt"** of the planar manipulator

One (upper) end of the base is like one of the ends of the hip to hold a servo motor. Another (bottom) end has holes (size M6) to be fixed on optical (mechanical) breadboard.


* Ending part **"new_end.sldprt"** which is connected to the last servo motor and holds Takksrtip (http://www.takktile.com/product:takkstrip)



All these parts were modelled in SOLIDWORKS and then converted to STL format in order to be 3D printed and used as a mesh in URDF file for ROS.

P.S. Depending on a model of 3D printer that you’ll use, always leave some space in your models (~0.5mm) on sides that will be connected to other objects. 

*Designed by Adilzhan Adilkhanov*
