Nemesis PI is a Fork or picoThermal which is a fork off of picoReflow by [apollo-ng]. It is intended to make it more 
versatile (suited for ceramic Pottery kilns) by adding several features:
Some Functions below are work in progress see config.py

Not Limited by stages and or programs ,you can have Thousands depending on PI4 models memory 4Gb or 8Gb
* Automatic PID tuning
* Time and temperature units defined per profile
* Added a High Limit Emergency shut off     Heating will be turned off and program stopped
* Added a Thermocouple Offset     adjust if needed to calibrate
* Removed CSV Logging MAKES IT SAFE NOT WRITING TO THE DISK! ACCESS LOGGING DATA IN TERMINAL CONTROLLER IS RUNNING IN only in manual mode or graph screen shot       will move to cloud. 
* Use the Live logging graph to help diagnose loose thermocouple connections and kiln issues such as relays and element wear over time. 
* Logging will be moved to online logging with the new app! Logging currently in manual mode in terminal when not auto booting controller.

26/8/20
* added 2 key press Stop Button option also setting up 2 and 3 zone removed simulate function still on single zone

29/11/20
* added Talking Kiln Controller update and bungs in terminal notification!
Change the .wav files with your voice just name them exactly as is.
This software Perfect for controlling a electric kiln and is works reliably with full remote control if needed via Phone ,Tablet or PC etc.. 
The added options make it suitable for a much wider range of thermal control.

26/01/21 added Hot Links to make getting Help and Firing Profiles for your Nemesis PI controller easier and added multi configs for easy copy and paste for Heat Treatment kilns as they do long holds at many different temperatures easy as copying and pasting config then restart controller to take effect quicker than having to constantly auto tuning kilns like simple PID controllers takes just 1 minute instead of some times hours like older controllers

Has error codes and will stop on errors for "safety" for max 31855k current driver supported module more coming soon very soon type k , n , r ,s ,j ,t, etc
NO connection     Thermocouple sensor break
Short to ground   Thermocouple short to ground     Grounding on metal case of kiln
Short to Vcc      Thermocouple picking up voltage from elements,old insulation or thermoouple close to elements small voltage can make errors in temperature readings.

WE are
Working on a
New App!! for IOS and Android  Pushing email ,text messages, cloud logging and so much more!!!
Up to you if google home or alexa is added left out as a safety feature!
Adding a simple on/off pid controller

Much much more coming soon all avaliable via updating 

Just keep your controller software updated ,come back from time to time to see the advancements we are making!!!

Use "simplescreenrecorder" from the app store in Linux to record your firing logs or if in manual mode copy and paste out of Terminal into speadshhet and save
Rememeber share and  email your friends your working firing programs great to help out the Noobs

Great for Glass kilns pottery kilns distilleries and the list goes on and on

Watch this Space!!!

Special thanks for the auto tune function implementation it just works!!!
cheers to 
Peter Thompson
Petronator
Also Special Thanks To JBruce12000 for all his hard work in many other areas of the programming making it a way better controller

Updates will be maintained for ever for free by us and the community make it your own expand it!
Please send us a message to help make it better!






