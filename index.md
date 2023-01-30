# Servers and Bugs  
## Part 1: StringServer   
This is my code for StringServer:  
  
![Image](assets/StringServerCode.png)  
  
This is the page that pops up when I run StringServer with different queries:  
  
After /add-message?s=Hello    

![Image](assets/AddMessage1.png)  

- First, handleRequest is called. In this method, url.getPath() is called and is compared to "/add-message." Then, url.getQuery() is called and .split("=") is called on the returned string. Finally, the first element in the returned string array is compared to "s" through .equals("s"), and if it is, the queried value is added to the existing string with an escape character and returned. 
- 

After /add-message?s=Hello and /add-message?s=World    
  
![Image](assets/AddMessage2.png)  

## Part 2: Bugs  

## Part 3: Reflection  
  
I learned about how servers handle queries as well as the components of a URI. I also learned about various testing concepts such as the definitions of symptoms vs. bugs. I never conceptualized the difference between the two terms and how the same symptom might be caused by multiple bugs or how one bug can cause multiple symptoms.   
