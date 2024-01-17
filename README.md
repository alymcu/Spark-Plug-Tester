2-Channel Spark Plug Tester Hardware

Tested Conditions:
500Hz - 20%      Transistors not getting warm
300Hz - 20%      OK
100Hz - 20%      Transistors Getting hot but for 5%, plugs getting spark and not getting hot.

The Parts i used are:

PWM Generator
![image](https://github.com/alymcu/Spark-Plug-Tester/assets/17362162/cb005e10-2707-4edf-8391-865b181cbacc)
- The board I received did not have capacitor 3, I installed a capacitor of 1µF-50V
- I also connected a 5.1V zener diode for 5V power supply and pulse outputsو (I put the zener diode on the back of the board)
- I applied the board input voltage of 12 volts
  
- I connected the two output pulses of the pulse generator to the two inputs of the two channels of the board below

4-Channel MOSFET Module
![image](https://github.com/alymcu/Spark-Plug-Tester/assets/17362162/2379051f-85d2-4763-a66e-26597f2910cb)
- I put a 4001 diode in the output of the board, which unfortunately did not work, so it was connected to the output coil without a diode and there was no problem.
- Continuity test was done for more than 1 hour at 500 Hz frequency with 20% pulse width and there was no problem
- I used two Renault coils for testing

- The image of the coil can be seen in the figure below

Renault Coil

![image](https://github.com/alymcu/Spark-Plug-Tester/assets/17362162/c663b73f-b4a3-4ecf-b5fa-af4ed3f20cba)

- The input voltage of both boards is provided with a 12V 2A power supply

- The figure below shows the initial test with a coil at a frequency of 200 Hz with a pulse width of 30%

Initial Test Photo
![IMG_A08DB735E6F6-1](https://github.com/alymcu/Spark-Plug-Tester/assets/17362162/9b066943-5364-4dda-935a-bb6160bf6eb8)
