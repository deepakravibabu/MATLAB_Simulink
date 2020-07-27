# Traffic Light Controller using Simulink Stateflow in Arduino
- Stateflow logic which detects a input trigger from the pushbuttons, makes a transition from idle to pedestrian_cross state.
- The traffic signals changes in a sequence to stop the traffic in the road and to make pedestrian signal green 
- The transition of the signals for car (R -> Y -> G -> RY) and pedestrian (R -> G) is based on the number of reference clock signal (making it a generic factor)
- If there is need to give more importance for the road (highway) then high wait time for pedestrian can be kept low by simply decreasing the pedestrian state transition value in the stateflow without changing the logic.
- The pushbutton press is indicated by the pedestrian light indicator.
 
 
![Alt text](/Traffic_light_controller/tf_light_arduino.gif)

![Alt text](/Traffic_light_controller/tf_light.gif)
