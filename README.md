# Flight-Checkin
log in to SW airline flight


IN ORDER TO BEST UTILIZE THIS FILE, ONE CAN FILL OUT THE 4 FIELDS BELOW AND THEN
SET UP CRONJOB TO RUN AT SPECIFIED TIME. THE USERS COULD THEN SET UP A .VBS FILE WITH THE BELOW CODE
  
  CreateObject("Wscript.Shell").Run "C:\..\SouthwestCheckIn.py", 0, True

THIS CRONJOB SHOULD RUN THE NEWLY CREATED .VBS FILE FROM ABOVE WHEN CHECKIN PERIOD OPENS AND 
USER SHOULD RECEIVE AN EMAIL CONFIRMATION THAT THEY ARE THEN CHECKED IN.
