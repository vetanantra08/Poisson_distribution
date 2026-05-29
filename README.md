# Fitting Poisson  distribution
# Aim : 

To fit poisson distribution for the arrival of objects per minute from the feeder

# Software required :  

Python and Visual component tool

# Theory:

The Poisson distribution is the discrete probability distribution of the number of events occurring in a given time period, given the average number of times the event occurs over that time period.

![image](https://user-images.githubusercontent.com/104613195/166248326-fd042076-8b0b-40c4-8b11-1d8e8fcb74db.png)

 Conditions for Poisson Distribution:

1. An event can occur any number of times during a time period.
2. Events occur independently. I
3. The rate of occurrence is constant.
4. The probability of an event occurring is proportional to the length of the time period. 
 
# Procedure :

![image](https://user-images.githubusercontent.com/104613195/166251988-d0c53205-6080-4f7b-ae4c-398178586637.png)

# Experiment :

![image](https://user-images.githubusercontent.com/103921593/230282876-f4a5afbf-cac1-4648-a1b0-c78840638a8e.png)

# Program :
<img width="1011" height="1405" alt="image" src="https://github.com/user-attachments/assets/d41835c5-08cf-448d-98db-63a1c1793eb6" />

#output:
X	P(X=x)	Obs.Freq	Exp.Freq	Chi^2
--------------------------------------------------
0	0.0213	       1	     0.43	   0.78
1	0.0819	       2	     1.64	   0.08
2	0.1577	       2	     3.15	   0.42
3	0.2024	       5	     4.05	   0.22
4	0.1948	       1	     3.90	   2.15
5	0.1500	       5	     3.00	   1.33
6	0.0962	       1	     1.92	   0.44
7	0.0529	       3	     1.06	   3.56
--------------------------------------------------
Calculated Chi-square value: 8.9913  
Critical Chi-square value (1% LOS, df=7): 18.4753  
The data *fits* the Poisson distribution at 1% level of significance.



# Results

The Poisson distribution is fitted for the objects arrived from feeder per minute and the data is tested using Chi-square test. 
 
