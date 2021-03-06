# J.O.B-Training-Network Commands Assignment

## You will now practice the network commands in Linux using the previously cloned repo that will track your work.

### Exercise 1 wget
In a terminal window practice the wget command. This command is used to download files from the internet without a browser.

1. In your terminal type the command ```man wget``` and read the documentation related to the command
  * press the Q button to quit out of the manual
2. Type the command ```wget https://techport.nasa.gov/api/items/11009``` 
  * Type the command ```ls -ltr``` and note that you now have a file called 11009 at was downloaded from nasa.gov
3. Now type ```less 11009``` and see that the header shows this as an xml file
  * press Q to exit less

### Exercise 2 curl
In a terminal window practice the curl command. This command is useful to extract data from API services.

1. Type the command ```man curl``` and read the documentation.
  * press the Q button to quit out of the manual
2. In your terminal type the command ```curl -L  -iH "Accept: application/vnd.crossref.unixsd+xml" http://dx.doi.org/10.5555/515151 > doi.txt```
  * note that the curl command went to doi.org to download metadata regarding the doi 10.5555/515151 and saved it into a file called doi.txt
3. Now type ```curl http://wttr.in/Moon > moon.txt``` and ```cat moon.txt``` to see that curl saved the output of wttr.in site with the moon phase information
4. Now type ```curl -Is http://www.ufl.edu -L | grep HTTP/``` and note that the website says ok. This can be used as a way to check if a website is online or not.
5. Now type ```curl -s http://artscene.textfiles\.com/vt100/wineglas.vt | pv -L9600 -q``` Cheers! 


## You have now completed the fifth and final online exercise for Linux commands. You will now be taken back to the Jump on Board website to take a quiz on the material covered in the online exercises. At the conclusion of the quiz you will have a face-to-face meeting with your trainer for a review session to discuss your experience with the content in this course. 

## Please return to the <a href="https://kevinhanson.github.io/J.O.B.-Jump-On-Board#quiz" target="_blank">Linux Commands Course Website</a> to start the quiz.
