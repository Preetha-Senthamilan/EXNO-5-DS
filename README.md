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

![image](https://github.com/Preetha-Senthamilan/EXNO-5-DS/assets/119390282/0d5ed8ba-f862-424d-9d6a-032781766af1)


![image](https://github.com/Preetha-Senthamilan/EXNO-5-DS/assets/119390282/5fa17750-9965-4afd-9f37-832a496447e6)


x=[10,20,30,40,50]
names=['A','B','C','D','E']
plt.bar(x,y,color='blue')
plt.show()

x=[14,30,25,6,20]
names=['A','B','C','D','E']
plt.bar(x,y,color='blue')
plt.show()



![image](https://github.com/Preetha-Senthamilan/EXNO-5-DS/assets/119390282/b23269fd-bb73-4571-9415-f14a470114e7)


![image](https://github.com/Preetha-Senthamilan/EXNO-5-DS/assets/119390282/4b2ec009-6dc7-4723-ab24-2adb8c56c53b)


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


![image](https://github.com/Preetha-Senthamilan/EXNO-5-DS/assets/119390282/d0f50b4a-0492-40db-baf3-a1ebff3c2550)

![image](https://github.com/Preetha-Senthamilan/EXNO-5-DS/assets/119390282/31e0a021-509b-4722-860a-6ede20576c3a)

ages=[2,5,70,40,30,45,50,45,43,40]
range=(0,80)
bin=10
plt.hist(ages,bin,range,color='green',histtype='bar',rwidht=0.8)
plt.xlabel('ages')
plt.ylabel('No of people')
plt.legend()
plt.title('Histogram')
plt.show()

x=[2,1,6,4,2,4,8,9,4,2,10]
plt.hist(x,bins=10,color='blue',alpha=0.5)
plt.show()


![image](https://github.com/Preetha-Senthamilan/EXNO-5-DS/assets/119390282/8fb4a798-e9ca-46c7-9a22-ed52737d4043)

![image](https://github.com/Preetha-Senthamilan/EXNO-5-DS/assets/119390282/75962f3a-2745-44fb-950b-c0813f7f42b0)


act=['eat','sleep','work','play']
slices=[3,7,8,6]
color=['r','y','g','b']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()

feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()


![image](https://github.com/Preetha-Senthamilan/EXNO-5-DS/assets/119390282/3dbed989-e29a-4059-b227-4749e8142b2a)


![image](https://github.com/Preetha-Senthamilan/EXNO-5-DS/assets/119390282/ddcbbe68-a956-45da-95b0-d90cce6ecf56)


# Result:
Thus, all the data visualization techniques of matplotlib has been implemented.
