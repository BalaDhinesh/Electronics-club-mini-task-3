__Project 1: Green lantern ring__

__Problem statement:__
To design a simple ring which emits green light when worn and doesn't when not worn.

__Design:__
The basic mechanism must be a trigger, i.e., some sort of an interaction is induced when worn. So I thought of using an LED-LDR trigger for this purpose. An LED-LDR combination is a sort of a trigger where an LDR (Light dependent resistor) and a sufficiently bright LED are placed in parallel. An LDR has a resitance which is inversely proportional to the intensity of light falling on it. Using this principle, we can use this combination as a trigger. 

Tinkercad simulation image:

![img](https://github.com/Ruban-VP/Electronics-club-mini-task-3/blob/master/Brave%20Waasa-Hillar.png?raw=true)

Tinkercad simulation link: [Web link](https://www.tinkercad.com/things/g9umWpZAEXY-brave-waasa-hillar/editel?tenant=circuits?sharecode=LrNU6fSPrm9PLwGul8CrZp7oOIiafZzpptvUjarqxHY)

We must place an LDR and a load resistor in series across a 3V coin battery. Also, a red LED is placed in front of the LDR to irradiate it and this LED is also connected to the 3V coin battery in series with a load resistor in order to prevent it from burning due to high currents. The current across the green LED is (Assuming LED resistances are negligible):

I = VR/(R.r1+R.r2+r1.r2)

where :
      
      I  = Current across the green LED

      R  = Resistance of LDR

      r1 = Resistance of load in series with freen LDR
       
      r2 = Resistance of load in series with the parallel combination of R and r1 (Refer diagram for better understanding) 
      
      V  = Voltage of the battery connected to these series resistors
        
From the formula, we can see that the current increases as R increases. This means current increases as intensity of light falling on the LDR decreases. Hence, we can basically control the __Brightness of the green LED__ or __SWITCHING__ by just placing an opaque obstacle in between, namely '__Wearing__' in this case. Also, we can have a slideswitch across the other LED (used to irradiate the LDR) for switching it off when the ring is not worn. This switch will be outside the ring's interior and hence, won't cause any irritation to the finger.

__(The Tinkercad environment can't process this trigger and has a brightness level meter near the LDR. So, we can't expect the exact real-life result of the circuit in the simulation but at least get a feel of how the circuit exactly behaves. Moreover, the circuit is designed in a circular shape to exactly mimic the ring's structure. The multimeter is just for illustration purposes.)__
