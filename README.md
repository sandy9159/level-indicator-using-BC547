# BC547-based-liquid-level-Indicator


# How-to-make-easy-Water-Level-Indicator


![maxresdefault (1)](https://user-images.githubusercontent.com/19898602/130759456-b564873a-a2e5-4aff-bfd5-a421a5d2e017.jpg)


How to make a water level indicator to save water from overflowing with Motor Dry run prevention.

A water level indicator is used to show the level of water in an over head tank. This keeps the user informed about the water level at all times and avoids the situation of water running out when it is most needed.

There are so many tutorials on net But this one is unique because this water level indicator circuit also has an water flow signal.

It not only indicates the amount of water present in the overhead tank but also gives the water inlet signal so that dry run can be prevented.



## COMPONENT REQUIRED

> 1. Transistor BC547 -- 4 no's

> 2. Led's - 4 no's

> 3. Resistor 330 ohm - 4 no's

> 4. Small PCB

> 5. 9V Battery with Clip - 1 no

> 6. Female connector - 1 no

> 7.Some Wires.


Basically the unit is made up of various sensors acting as a switch. Let me explain in a simple way. What happens is when you turn on you water pump, the water starts to get pumped from your underground reservoir  or from your underground water supply from the pipes to your water tank. In the tank there is a set of sensors( to be precise there are 7 sensors), in the water tank. Just think them as a switch, 

as the work of the sensor will be to connect a circuit. I will explain in details. So the water starts to get filled in the tank and when the water level in the tank starts to rise up, what happens is that the sensors that is installed in the tank 

starts to get activated one by one indicating the water level in the tank. And finally when it reaches to its top most sensor, there will be a visual display as well as a sound from the unit indicating that the water has filled in the tank and one can be alerted that the tank has been filled up and the water pump has to be switched off saving the electricity bill as well as over flow of water from the tank.



# CIRCUIT DIAGRAM

![image](https://user-images.githubusercontent.com/19898602/130768233-4ae007ba-78b4-4262-9403-5d3d56914481.png)


It has numerous transistors acting as a switch and the switch gets activated when the sensors tell them to. 

The heart of the circuit is the transistors BC 547. There are total 4 transistors in the circuit and each one will 
be sensing the level of water present in the overhead water tank. There is one extra power LED without a transistor and that is because this Red LED will be telling us two things. Firstly when you power the unit it will be monitoring the power present in the unit and secondly it is also the indicator telling you 

that there is no water at all present in the tank. As because the water level is below the No. 1 (as shown in the circuit) sensor, no LED's will be lighting up, but only for the one Red LED. Therefore when you switch on your unit if you see only one Red LED lighting up then you know that the is no water present in the tank and therefore you should make you water pump on.


Then as shown in the figure i have given all the LED's in various color. Starting from the beginning is 
 Red LED - 1 (Indicating no water in the tank as none of the sensors are getting contact with the water)
Red LED - 2 ( Level 1, indication very low water in the tank )
Red LED - 3 (Level 2, indication of half water level)
Red LED - 4 (Level 3, indication full water)



Now as the water starts to rise up the sensors starts to get in contact with the water and the transistors are activated and there is a 
flow of current in the transistors making the LED's light up. Here in between the transistor and the LED there is a current limiting resistor 470 ohms, 

the job of the resistor is to checks that the LED does not get over voltage and destroy the LED. The transistor is biased by a 470K resistor with the ground and the sensing part is taken from the collector with a 33 ohms resistor going directly to the tank. As i have shown in the diagram the signals are drawn in the Green color. 

There by you can follow the LED's as they light up from Red to Yellow and then Green and finally to Blue making a sound.  

Before moving further I would like to tell you something about PCB 

Yes PCB are the heart of the electronics based project usually we hesitate to try custom PCB and opt to homemade solutions

like breadboard or Zero PCB earlier I also was in the same boat, I hesitate to try custom PCB my belief was they are much expensive.

but then I came to know about [JLCPCB.com](https://jlcpcb.com/IAT) and I was totally surprised how low price PCB's are they offering 

there PCB quality is top to the mark now I always go with PCB for my project and [JLCPCB.com](https://jlcpcb.com/IAT) is my trusted 

PCB manufacturer, you can also try there PCB service for more details you can visit their website [JLCPCB.com](https://jlcpcb.com/IAT)


![image](https://user-images.githubusercontent.com/19898602/127161780-d9b742d8-fd97-4e1e-a35f-a6591f8c3411.png)![image](https://user-images.githubusercontent.com/19898602/127161903-d6753a2e-5242-4ab7-8406-29ac5a486a42.png)![image](https://user-images.githubusercontent.com/19898602/127162080-a4212957-1ebb-4e81-ad5e-bd3c1e0ecb87.png)




![image](https://user-images.githubusercontent.com/19898602/130768734-cabf7e53-764a-415a-bc35-197aa95646de.png)

Fold all pins of all BC547 transistors as picture.

BC547 Transistor (NPN ) -

> 1. First pin is Collector.

> 2. Second pin is base and

> 3. Third pin is emmiter.




![image](https://user-images.githubusercontent.com/19898602/130768936-ca9d4497-4963-49cd-a936-cdd2c5d0abcf.png)
![image](https://user-images.githubusercontent.com/19898602/130768968-a9787728-315b-4b28-ad52-986907a7b841.png)

![image](https://user-images.githubusercontent.com/19898602/130768890-f793c77e-ba6a-4706-894f-841c4e4cdbaf.png)



Next we have to solder LED in transistor.

Solder -ve pin of LED to the collector pin of transistor.

Connect all LEDs in transistors like as picture.

![image](https://user-images.githubusercontent.com/19898602/130769084-afa238b0-9ce6-419a-ac1a-72e48aa6f896.png)

Next connect all +ve pins of all LEDs as shown in picture.



![image](https://user-images.githubusercontent.com/19898602/130769209-c714f351-2758-4737-83e4-64990eb1db56.png)
![image](https://user-images.githubusercontent.com/19898602/130769273-45691cca-568c-47a4-b3ca-402c19091c36.png)


Connect battery to the circuit and put (hold) wires in level as you want.

In picture as you can see when water level in between +ve wire of battery and base wire of 1st transistor then only one LED is glowing.

In this type when water level increases then 2nd LED is also glowing and this type 3rd LED glowing.

This type we can make tank water level indicator.

Thank you


![MVI_5803](https://user-images.githubusercontent.com/19898602/130769868-d6d02174-e190-461e-812c-28d533d1afa0.gif)


