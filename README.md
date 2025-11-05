# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
 # NAME: sanjai ganth.B
 # REG NO: 212224230244
```
 import pandas as pd
 import numpy as np
 import seaborn as sns
 import matplotlib.pyplot as plt
```
# Line Plot:
```
 marks=[13,45,63,78]
 student=['ABC','QOR','EFB','TOB']
 plt.plot(marks,student)
 plt.xlabel('Marks')
 plt.ylabel('Student name')
 plt.show()
 student=['A','B','C','D']
 attendence=[90,85,73,88]
 plt.plot(attendence,student)
 plt.xlabel('Attendence')
 plt.ylabel('Student name')
 plt.show()
```
<img width="733" height="556" alt="image" src="https://github.com/user-attachments/assets/38ccefb5-62f6-4c9f-afa1-03204b369dd1" />

<img width="776" height="546" alt="image" src="https://github.com/user-attachments/assets/fc5c5568-420c-493e-af30-ebf5c985e41e" />

# Scatter Plot:
```
 x=[10,20,30,40,50]
 y=[100,200,300,400,500]
 plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
 plt.show()
 x=np.arange(0,15)
 y=np.arange(0,15)
 x
 y
 plt.scatter(x,y,c='r')
 plt.xlabel('X axis')
 plt.ylabel('y axis')
 plt.title('Scatter plot')
 plt.show()
```

<img width="540" height="742" alt="image" src="https://github.com/user-attachments/assets/4eb396a3-a4b4-43c6-9224-f385105b1e03" />


# Pie Chart:
```
 act=['eat','sleep','work','play']
 slices=[3,7,8,6]
 color=['r','y','g','b']
 plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=  (0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
 feedback=['Good','excellent','Perfect','Ok']
 slices=[4,10,3,8]
 color=['y','r','b','g']
 plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
 ```

<img width="508" height="695" alt="image" src="https://github.com/user-attachments/assets/61e978cb-8c8b-47ca-8ff0-02595b6dca47" />

# Area Chart:
```
 x = [1, 2, 3, 4, 5]
 y1 = [10, 12, 14, 16, 18]
 y2 = [5, 7, 9, 11, 13]
 y3 = [2, 4, 6, 8, 10]
 plt.fill_between(x, y1, color='blue')
 plt.fill_between(x, y2, color='green')
 plt.plot(x, y1, color='red')
 plt.plot(x, y2, color='black')
 plt.legend(['y1','y2'])
 plt.show()
 ```

<img width="494" height="357" alt="image" src="https://github.com/user-attachments/assets/ff485481-5837-40d4-a12c-ca732066342d" />


 # Bar Chart:
 ```
 height = [10, 24, 36, 40, 5]
 names = ['one', 'two', 'three', 'four', 'five']
 c1=['red', 'green'] 
 c2=['b', 'g']
 plt.bar (names, height, width=0.8, color=c1)
 plt.xlabel('x - axis')
 plt.ylabel('y - axis')
 plt.title('My bar chart!')
 plt.show()
 ```
<img width="558" height="396" alt="image" src="https://github.com/user-attachments/assets/c2024377-0acc-4b9e-94b5-65d729632d91" />

 # Histogram:
 ```
 x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
 plt.hist(x, bins = 10, color='blue', alpha=0.5)
 plt.show()
```
<img width="509" height="354" alt="image" src="https://github.com/user-attachments/assets/049d738f-ea0a-4421-b5ab-a012574c6411" />

 # Box Plot:
 ```
 np.random.seed(0)
 data=np.random.normal(loc=0, scale=1, size=100)
 data

```
<img width="545" height="312" alt="image" src="https://github.com/user-attachments/assets/a38b41c9-c3f0-4444-bc38-1f73d1cb9838" />

```
 fig, ax= plt.subplots()
 ax.boxplot(data)
 ax.set_xlabel('Data')
 ax.set_ylabel('Values')
 ax.set_title('Box Plot')
```
<img width="524" height="403" alt="image" src="https://github.com/user-attachments/assets/f7eb45f8-93d4-40e6-a1b5-12424420e351" />


# Result:
  Thus, all the data visualization techniques of matplotlib has been implemented.
