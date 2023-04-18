# Skymap



Get ra and dec from KY data, and plot the skymap.



#### KY data
 
FAST always observe more time to  note the KY file before the fits data, which is truly useful. So if we try to get the ra and dec range from KY file , we have to cut off these extra KY data. And we need a algorithm. 



the KY file always looks like this, with a sloping part and a nearly flat part, with some small fluctuations.