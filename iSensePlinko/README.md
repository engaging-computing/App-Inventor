iSENSE Plinko
------------
This is an application that goes along with the ongoing iSense [Plinko](https://en.wikipedia.org/wiki/List_of_The_Price_Is_Right_pricing_games#Plinko) project.  We have a plinko board with places to drop a bal labeled A-I, and slots where the ball can land after filtering through the pegs, labeled 1-9.  We have an [iSense project](https://isenseproject.org/projects/2156) setup where the user uploats the place they dropped their ball, and where it landed.  Since we took this demo to USASEF, we have well over 1000 data points for this project.

The theory behind the demo is that for every dropsite, the graph of the landsites should form a rough probability curve centered about the dropsite.  This theory seems to be confirmed by the data.

If the app is not connected to the internet or cannot publish to iSense fo4r some reason, it puts the pending upload into a queue and uploads them all when it can.
