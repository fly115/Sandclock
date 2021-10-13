# Sandclock
Clock for Sisyphus style kinetic sand table 

Still working on this. Only tested on my one sandtable (not a Sisyphus table) running Octoprint. 

1.Open Clock Gcode Generator with excel.

2.fill out the dimensions of your sand table. 

3. Set start time to 12:00 Press 'Re-Sync' button
4. 
5. Press 'Save Gcode' Button. 
6. 
7. print with your sandtable. Take note of time to complete;
8. 
    - eraser

    - draw clock face
    
    - time to complete one full hour loop
    
    - time to complete the hour indicator time (note time per hour increment)
    
8. Adjust timers if needed per your observations
9. 
10. Re-sync and save new gcode file. 
11. 
12. Use Octprint playlist plugin (or scheduler plugin) to start the print at 12:00 or at the start time you set. put on repeat. Best have the print run slightly ahead of schedule and then use the plugin settings to start the next print at midnight each night. This way slight time variances do not accumulate. 

You can use the batch save button to save the print at multiple start times. for example, set increment to 15min, or 5min or 1min. batch save all files. upload them all  (use multipleupload octoprint plugin to make this faster) then just select the one you need based the current time. This means you can kick of the clock at whatever time you want. You could use the scheduler plugin to keep it going after that.

I have uploaded all 720 start times (1min increment) for my table incase these are helpful to anyone. Will only be suitable for 500x500 print area. 

To Do:
add support for .thr files. (not sure if dwell command will work?) so it will work with sisyphus tables. 
someone else may be able to get the generator spreadsheet to run on linux and create a plugin or program that generates the movement codes on the fly to check time and keep in sync.
