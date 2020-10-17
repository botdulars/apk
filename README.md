# apk
Mobile App for Bluetooth testing

Please note - The TX and RX jumpers have to be turned OFF before the code can be uploaded on Arduino. 

This APK was created using the MIT app inventor. We have therefore included the MIT license along with this. This is to be used ONLY with the botdulars kit for levels 1 and 2 to test each of the sensors/ actuators. 

Every input from the bluetooth app button corresponds to a particular number and consequently a corresponding function call. 

>> Input 1 : Show Potentiometer value ; 
>> Input 2 : Show Joystick readings ; 
>> Input 3 : Show distance to nearest object using Ultrasonic sensor; 
>> Input 4 : Show Temperature and Resistance; 
>> Input 5 : Show Luminance ; 
>> Input 6 : turn On the green LED ; 
>> Input 7 : test the Servo with a small sweep ; 
>> Input 8 : spin the 2 wheels forward and backwards for a couple of seconds; 

The Car app however is very specific to directions for turning left, going forward, turning right and a reverse call. Each of them are invoked by an integer value from the App Inventor, viz., 1, 2, 3 and 4 for respective image clicks. 
