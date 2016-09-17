# exercise-1

##`Abstract`
>
This home work is mainly about how to print my english name on the screen using python.Here, I show 2 methods.The first one is printing my name with the help of 'print()', the second way is using matplotlib and numpy to form the name with several scatter points.

##`Background`
###1.using [How to think like a computer scientist – Learning with Python: Interactive Edition 2.0](http://interactivepython.org/runestone/static/thinkcspy/index.html) to learn python language and do exercise
###2.spelling english name on the screen

##`exercise2 method 1`
* using print() to show name 
![name1](https://github.com/LuxAsteria/test3/blob/master/method1.png)

##`exercise2 method 2`
* drawing the scatter piont of a function
![name2](https://github.com/LuxAsteria/test3/blob/master/屏幕快照%202016-09-16%20下午12.19.04.png)

**here is the code**

```
x1=[0,2,2.3,3.5,5,6,6.5,7.5,9]
y1=[3,3,3,3,3,3,3,3,3]
x2=[0.5,1.5,2.3,3,3.5,4,5,5.5,6,6.5,7,7.5,8.5,9,9.5]
y2=[2,2,2,2,2,2,2,2,2,2,2,2,2,2,2]
x3=[1,2.3,2.5,4.5,5,6,6.5,7.5,8,10]
y3=[1,1,1,1,1,1,1,1,1,1]
from numpy import*
import matplotlib 
import matplotlib.pyplot as plt
f=plt.figure(1)
plt.subplot(211)
p1=plt.scatter(x1,y1,marker='+',color='m',label='1',s=10)
p2=plt.scatter(x2,y2,marker='x',color='g',label='2',s=20)
p3=plt.scatter(x3,y3,marker='o',color='c',label='3',s=30)
plt.show()
```
  
##`Conclusion`
In this article,I've showed 2 simple methods to achieve my goal.If anyone has got some other execellent ideas, welcome to discuss with me.


#ps:All Rights Reserved
