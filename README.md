# Average-Pulse-Width-Algorithm-
Given a wave or any data consisting of pulses, the code will identify the edges of the pulses and give you the average pulse width.

# The data used:
The data used is from [here](https://mast.stsci.edu/portal/Mashup/Clients/Mast/Portal.html)

![pulse wave](https://user-images.githubusercontent.com/63223240/137790411-d6dfbe6f-72d8-4b94-9738-249d463ce226.png)

# What we need to calculate:

![pulse in wave](https://user-images.githubusercontent.com/63223240/137790792-caca34bd-d089-449b-8f5c-313fbbdd9e88.png)
(*Sorry for bad sketch*)

The idea is to take the points where the change in slope is maximum as the edges of the pulses. We then see how the slope of the data is distributed.

![slope distribution](https://user-images.githubusercontent.com/63223240/137791129-57aa84d9-69a7-480e-883f-1909c7b7dc14.png)

We now take the plot the point where the slope change is maximum.

![final points for detecting pulse edges](https://user-images.githubusercontent.com/63223240/137791311-732dada1-51e4-40b0-bb21-d878927090f3.png)

Last but not the least.
Taking the average difference between each pulse.

That's it!!

Feel free to drop suggestions. 

Thank you
