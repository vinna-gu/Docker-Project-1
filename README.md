# CS1660 Project Option 2

NOTE: I've only tested this on a Mac.
## Steps to run:

1) Clone or Download this repository
2) Open up the terminal/command prompt and `cd` into the location of where you downloaded it _example: cd Desktop/CS1660_P2_
3) In the terminal, enter `docker-compose build`
4) Once it is done, enter `docker-compose up -d` for a cleaner output on the terminal of what services are loaded and ready to go. 
5) Open up your preferred web browser and navigate to _http:/localhost:5000/_
6) From there, you should be able to open each link listed on the web page. Some links may not work because they were not implemented. 

## To stop containers:
1) In the terminal, enter `docker-compose down` and that should stop all the containers. 

## Possible issue(s) you may run into:
When implementing SonarQube, I had encountered an error saying I was running out of memory. 

To fix that:
1) Open up the docker application
2) Navigate to settings > resources
3) Set memory to 4GB and if this memory issue occurs again, try increasing it.
