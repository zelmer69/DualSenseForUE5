# DualSenseForUE5
UnrealEngine Function library for creation DSX instruction 




#installation 
* install https://github.com/getnamo/UDP-Unreal 
* unpack the archive to yourprojectname/plugins/
Done plugin should be on on next engine startup




Documentation 


Establishing connetion:
![image](https://user-images.githubusercontent.com/62244963/230760460-d3793615-e489-4be3-b2c8-dd1877c7a954.png)

Make sure UDP is on and you remeber the port 

![image](https://user-images.githubusercontent.com/62244963/230760525-fb42bd98-773b-4591-83d2-aad5760e8173.png)

Add UDP component to your BP. Then call function from that component "open recive scoket" and enter port number same as in DSX

![image](https://user-images.githubusercontent.com/62244963/230760563-c404c985-bc4e-4901-b52f-1b0e198a3aca.png)

make sure your settings in componnent is same exept for port- use number from DSX 

![image](https://user-images.githubusercontent.com/62244963/230760663-0892ade4-45e3-4b88-8fdd-bc01796dd0aa.png)

use "Send instruction " to send instructions to DSX 
To create instructions use "make array" and many of functions provided by plugin 
![image](https://user-images.githubusercontent.com/62244963/230760767-0006fc99-5155-4c61-9f61-fec98de61ea4.png)



![image](https://user-images.githubusercontent.com/62244963/230760802-dc88d037-4bba-4152-aaac-6afea3409e50.png)

Old controller revisions will require you to use specific funtion. 

