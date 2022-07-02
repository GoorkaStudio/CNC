# Bitmap to CNC - generate a gcode for cnc router in Inkscape (gcodetools)

In the Inkscape you have two options to generate cnc code (gcode) form bitmap:
1) Generate centerline trace (autotrace) - one single line for router
2) Generate outline 

Let's assume you have bitmap to run on CNC router:

![image](https://user-images.githubusercontent.com/54003204/176988302-4b01b540-366d-488d-9276-a80007bfd6f3.png)

Import bitmap to inkscape:
![image](https://user-images.githubusercontent.com/54003204/176988417-1a30752e-afaa-4005-b1f3-7289802db6aa.png)


## Option 1 - centerline trace

Select bitmap. From menu Path/Trace Bitmap

![image](https://user-images.githubusercontent.com/54003204/176988443-f55309a7-3c8e-47fa-b2c3-b214c8ab33e3.png)

![image](https://user-images.githubusercontent.com/54003204/176988486-706df445-4b6e-49de-a3db-1742ead8a2b1.png)

Incscape generate one line trace ( if generated pathe is fine, delete bitmap )

![image](https://user-images.githubusercontent.com/54003204/176988561-9dcb1f2a-872f-4235-9756-83995f825365.png)

If you need edit genereted path:

![image](https://user-images.githubusercontent.com/54003204/176988656-051c0379-16d9-4bb2-b7ad-54931a309270.png)


## Option 2 - outliner trace

Select bitmap. From menu Path/Trace Bitmap

![image](https://user-images.githubusercontent.com/54003204/176988443-f55309a7-3c8e-47fa-b2c3-b214c8ab33e3.png)

![image](https://user-images.githubusercontent.com/54003204/176989152-59e9f035-99ce-46d5-aac4-6cf7ca7fa16e.png)

![image](https://user-images.githubusercontent.com/54003204/176989180-219339a5-f120-47a7-9df5-b016adc53ca6.png)

If you need edit genereted path:

![image](https://user-images.githubusercontent.com/54003204/176989195-534be0b1-0ae9-461e-becb-7bbb0e77d9dc.png)


## Generate gcode

Select your path and from menu Extensions/Gcodetools/Path to Gcode...

![image](https://user-images.githubusercontent.com/54003204/176989280-7ceb78ce-06b7-41b6-8759-3714fb905900.png)

Set preferences

![image](https://user-images.githubusercontent.com/54003204/176989309-62401b4a-8df8-4381-a2d0-ef67e5463591.png)

Generate gcode

![image](https://user-images.githubusercontent.com/54003204/176989327-6e3ebac1-7ca1-4652-8f21-8dce95118057.png)

![image](https://user-images.githubusercontent.com/54003204/176989341-75dd607b-1d00-47fa-9aec-0d923a3201c2.png)

Get file in explorer

![image](https://user-images.githubusercontent.com/54003204/176989390-521fd0fb-7718-4069-b7d2-8d4381e7adbc.png)


## Preview
You can preview your's gcode in online viewer  https://ncviewer.com/ 

![image](https://user-images.githubusercontent.com/54003204/176989451-4bea763b-7641-42cb-b096-39d21d1af377.png)



