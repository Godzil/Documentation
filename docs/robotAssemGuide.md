### <font size=40>__The Robot kit Assembly Guide__</font>

![Image](/img/robotAssemGuide/robotAssem1.png)

Like the picture shows, the Livera Robot kit comes with several components that you need you assemble and make it to a fully functional robot. This tutorial would get you through all the process of `physical building and wiring,` it might take around `25 minutes` to make the robot alive. Clear up your desk, unpack the Robot kit and let begin the journey.

#### __Step 1: Base panel build__

![Image](img/robotAssemGuide/robotAssem2.jpg)

Unpack the Livera Robot kit package, Find out the following components in order to build the base panel of the Robot:

- __Robot Base Acrylic Panel x1__
- __DC Motor + Motor Carrier x2__
- __Omni-directional Wheel Set x1__
- __M2x15(+6)mm Nylon Stud x4__
- __M2x6mm Nylon Stud x4__
- __M2x6(+6)mm Nylon Stud x4__
- __M2 Nylon Nut x4__

__Notice:__ All the Stud could be install by hand, you don't require any tools for them.
__`Caution:`__ Don't make it too tight while screwing with the `Livera and Livera Motor Driver`, as you may might have a small chance to cause damage to the board if you screw it too hard. 
 

![Image](img/robotAssemGuide/robotAssem3.jpg)

Assemble up the `Omni-direction Wheel Set` like the picture shows, then close up with the `Cover bit`, waiting for screw on the `Base Panel.` 

![Image](img/robotAssemGuide/robotAssem4.jpg)

![Image](img/robotAssemGuide/robotAssem5.jpg)

- __Install the motor on the base panel:__ carefully place the `M2 Nut` onto the `Motor Carrier's slot`, then catch the `DC Motor` and match to the hole on the `Base Panel`, pay attention to keep the `+` sign on top as on the top left of the pic shows, using `M2x6(+6) Stud` to screw through from the other side of the panel.
- __Install the Structure bit:__ place the `M2x15(+6) Stud` on top of the `Base panel`, then let the `6mm screw bit` through the hole and screw into the `M2x6mm Stud.`

#### __Step 2: Body build__

![Image](img/robotAssemGuide/robotAssem6.jpg)

- __Install the Livera Motor Driver:__ simply place by matching with the `Stud.`
- __Install the Structure bit:__ Screw `M2x10(+6)mm Stud` on top.

__`Caution:`__ Don't make it too tight while screwing with the `Livera and Livera Motor Driver`, as you may might have a small chance to cause damage to the board if you screw it too hard. 


![Image](img/robotAssemGuide/robotAssem7.jpg)

- __Install HICAT.Livera with Extend Cable:__ carefully stack the `Livera` on top of the `Livera Motor Driver,` do check for the `I/O ports` and the `outline` to check it is correctly aligned with the `Livera Motor Driver.`
- __Install the Structure bit:__ Screw `M2x10(+6)mm Stud` on top of Livera.

__`Caution:`__ Don't make it too tight while screwing with the `Livera and Livera Motor Driver`, as you may might have a small chance to cause damage to the board if you screw it too hard.

#### __Step 3: Top build__

![Image](img/robotAssemGuide/robotAssem8.jpg)

- __Install the top Acrylic Panel:__ place the `Top Acrylic Panel`, the fix it by screw the `M2x6(+6)mm Stud` on top.
- __Stick the Power case and Servo:__ unpack the `3M Sticker`, then stick them as the image shows.
- __Connect Power:__ connect the 2.54mm Power connector from the `Power case` to the `Livera Motor Driver.`


![Image](img/robotAssemGuide/robotAssem9.jpg)

- __Install the Camera pan-tilt:__ screw the Servo Arm Set form the `EMAX Servo set` on the `Camera Pan-tilt.`
- __Install Camera Module:__ carefully place the camera module on the `Acrylic Camera Pan-tilt`, and use `M2 Rivet` to fix it.
- __Install Camera Extend Cable and Laser Beam:__ install the components as the picture shows, please notice that the `direction` of the camera module should be `match together` according to the `indicate drawings.`

#### __Step 4: Wiring__

![Image](img/robotAssemGuide/robotAssem10.jpg)

- __Wiring:__ wire up all the electronics, Motors, Laser and Servo, as the picture shows. For the `DC Motor` wiring, you would need to use the screwdriver to fix the wire into the adapter.
- __Install SD card:__ put the `SD card` into the SD slot.

![Image](img/robotAssemGuide/robotAssem11.jpg)

- __Install Battery:__ put the `9v chargeable battery` into the `Power Case.`
- __Power up to init the Servo:__ switch on the `Power Switch` From the Motor Driver, wait until heard `two movement` from the `Servo,` then put the `Camera Pan-tilt` on the `Servo` in a `horizontal position,` screw it up using the smallest screw from the Servo Box.
- __Enjoy:__ take your cell phone, and connect to the `Livera's wifi`:

```
ssid:hicat_xxxxxx
passward:88888888
```

 then open `chrome browser`, go to the web page:

```
http://192.168.1.1/mmc/webapp/index.html
``` 


- Switch the top video switcher to `MJPG MODE`, click `LiveView`, if the image flipped, you could change it within `QUALITY,` we suggest you to chose `240p/15fps.`

- Click `ROBOT` to open the control panel, Try press forward button, if you see the robot `spinning` or `move back,` you could adjust the wiring by switch the `DC motor` wire from the adapter.