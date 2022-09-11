# Refactored VBA Code and Measured Performance for Stocks In 2018 and 2017.
This project analyzed the performance of individual stocks against other stocks within a particular year and compared the overall stocks performance between two different years (2017 and 2018). Total Daily Volumes and Returns were the measurables.
## 2017 Stocks Analysis
Overall stocks performance in 2017 yielded positive returns for all with the exception of TERP that yielded a negative return of -7.2%.
#### Total Daily Volume versus Returns
SPWR recorded the most daily volume traded (782,187,000) but recorded a return of 23.1%.  DQ had the most return of (199.4%) but recorded the least total traded daily volume of 35, 796,800 in 2017. The refactored code run for the stocks in 2017 was 0.0625 seconds long.
 
 
 ![image](https://user-images.githubusercontent.com/112135658/189545027-3f51f6d3-1b16-4249-837b-6ed6e7f4a6be.png)

 
 
 
 
 ![image](https://user-images.githubusercontent.com/112135658/189544849-f7231d31-d2a8-48c4-8edb-54b135fdf7c0.png)

       
        
        
##  2018 Stocks Analysis 
Overall stocks performance in 2018 yielded negative returns for all with the exception of ENPH and RUN that yielded positive returns of 81.9% and 84.0% respectively.
#### Total Daily Volume versus Returns
ENPH recorded the most daily volume traded (607,473,500 and also yielded the 2nd most return of 81.9%.  RUN had the most return of (84.0%) and also recorded the second most total traded daily volume of 502,757,100. Both RUN and ENPH performed very well in 2018. The refactored code run for the stocks in 2018 was 5.078125E-02 seconds long.

![image](https://user-images.githubusercontent.com/112135658/189545062-b0c64da3-9158-4636-96f2-2001c592172d.png)




![image](https://user-images.githubusercontent.com/112135658/189544797-f055b41f-ed46-4854-8b04-875833126305.png)


#### Summary
The refactored code run for 2018 was 5.0781256 E-02 seconds as compared to 00625 seconds in 2017.
Refactoring made the code run faster by looping through all the data one time. It was successful because it was more efficient, it took fewer steps, used less memory. It definitely has an advantage over regular VBA as it can work through thousands of stocks efficiently in a very short time. Ovaerall, 2017 had the most total traded volumes and alos better returs.
