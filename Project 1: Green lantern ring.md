__Project 1: Green lantern ring__

__Problem statement:__
To design a simple ring which emits green light when worn and doesn't when not worn.

__Design:__
The basic mechanism must be a trigger, i.e., some sort of an interaction is induced when worn. So I thought of using an LED-LDR trigger for this purpose. An LED-LDR combination is a sort of a trigger where an LDR(Light dependent resistor) and a sufficiently bright LED are placed in parallel. An LDR has a resitance which is inversely proportional to the intensity of light falling on it. Using this principle, we can use this combination as a trigger. 

We must place an LDR and a load resistor in series across a 3V coin battery. Also, the LED is placed in front of the LDR and this LED is also connected to the 3V coin battery in series with a load resistor in order to prevent it from burning due to high currents. The volage drop across the LDR is:

V.D = VR/(R+Rl)

where V.D = voltage drop across LDR
        R = Resistance of LDR
       Rl = Resistance of load in series with LDR
        V = Voltage of the battery connected to these series resistors
        
From the formula, we can see that V.D increases as R increases. This means V.D increases as intensity of light falling on the LDR decreases. Hence, So if we use this voltage drop as the source voltage for the appropriately loaded green LED, we can basically control its switching by just placing an obstacle in between, namely '__Wearing__' in this case. Also, we can have a switch across the brightness inducing LED for switching it off when the ring is not worn. This switch will be outside the ring's interior and hence, won't cause any irritation to the finger.

Tinkercad simulation image:

![img](https://github.com/Ruban-VP/Electronics-club-mini-task-3/blob/master/Brave%20Waasa-Hillar.png?raw=true)

Tinkercad simulation link: [Web link](https://www.tinkercad.com/things/g9umWpZAEXY-brave-waasa-hillar/editel?tenant=circuits?sharecode=LrNU6fSPrm9PLwGul8CrZp7oOIiafZzpptvUjarqxHY)

__(The Tinkercad environment can't process this trigger and has a brightness level meter near the LDR. So, we can't expect the exact real-life result of the circuit in the simulation but at least get a feel of how the circuit exactly behaves. Moreover, the circuit is designed in a circular shape to exactly mimic the ring's structure. The multimeter is just for illustration purposes.)__
