Project Overview 

The "Smart Wireless Seatbelt with Alcohol Detection System" is an innovative project designed to enhance vehicular safety. By integrating sensors and smart logic, this system ensures two critical safety measures: mandatory seatbelt usage and detection of alcohol consumption by the driver. It prevents the vehicle from starting if either of these safety conditions is not met, thereby reducing risks associated with drunk driving and non-compliance with seatbelt usage. 

Key Functionalities 

Mandatory Seatbelt Usage: 

The system is activated only when the seatbelt is worn, ensuring that this basic safety protocol is followed. 

If the seatbelt is not worn, the system remains inactive, and the motor will not start. A message, "Seatbelt: OFF," is displayed on the LCD. 

Alcohol Detection: 

An MQ-3 alcohol sensor continuously monitors the driver’s breath for alcohol levels. 

If the alcohol level exceeds a predefined threshold, the system immediately disables the motor, preventing the vehicle from starting. 

In this state, the red LED blinks, a buzzer sounds, and the LCD displays, "Alcohol Detected: Motor OFF." 

Motor State Control: 

When all conditions are met (seatbelt ON, alcohol level below the threshold, and car key ON), the green LED blinks, and the motor starts. The LCD displays, "All OK: Motor ON." 

If the car key is OFF while other conditions are satisfied, the orange LED blinks, indicating a normal state but with the motor OFF. The LCD displays, "Check: Motor OFF." 

User Feedback and Alerts: 

Real-time status updates are provided through the LCD, LEDs, and buzzer. 

Critical messages are logged via the Serial Monitor for debugging and tracking. 

System Components and Their Roles: 

Arduino UNO: Controls all operations by reading sensor inputs and driving outputs. 

MQ-3 Alcohol Sensor: Monitors alcohol concentration in the driver’s breath. 

LCD Display: Provides real-time updates about the system status and alcohol levels. 

LED Indicators: Visual feedback for system states (red for alcohol detection, green for motor ON, and orange for normal but motor OFF). 

Buzzer: Alerts the user when alcohol is detected. 

Seatbelt and Car Key Switches: Simulate critical conditions for starting the motor. 

Motor: Represents the vehicle engine and is controlled based on input conditions. 

This system combines practicality and functionality to ensure that only sober, seatbelted drivers can operate the vehicle, promoting safety and reducing accident risks. 
