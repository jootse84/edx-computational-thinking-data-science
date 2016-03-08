##Q1

Consider the function below:  

def lotsOfParameters1(a,b,c,d,e):  
    print a  
    print b  
    print c  
    print d  
    print e  

Which of the following function calls will result in an error?  

V - lotsOfParameters1()  
V - lotsOfParameters1(1, 2)  
X - lotsOfParameters1(1,e=5,d=4,c=3,b=2)  
X - lotsOfParameters1(e=5,a=1,d=4,b=2,c=3)  
V - lotsOfParameters1(a=5,b=1,c=4,d=2,3)  

Which of the following function calls will produce the same output as calling lotsOfParameters1(1,2,3,4,5)?  

X - lotsOfParameters1()  
X - lotsOfParameters1(1,2)  
V - lotsOfParameters1(1,e=5,d=4,c=3,b=2)  
X - lotsOfParameters1(e=5,d=4,c=3,b=2,1)  
V - lotsOfParameters1(e=5,a=1,d=4,b=2,c=3)  

##Q2

Consider the function below:  

def lotsOfParameters2(a=1,b=2,c=3,d=4,e=5):  
    print a  
    print b  
    print c  
    print d  
    print e  

Which of the following function calls will result in an error?  

X - lotsOfParameters2()  
X - lotsOfParameters2(1,2)  
X - lotsOfParameters2(1,c=2)  
V - lotsOfParameters2(1,c=2,3)  
X - lotsOfParameters2(1,e=20,b=3)  
V - lotsOfParameters2(1,e=20,b=3,a=10)  

Which of the following function calls will produce the same output as calling lotsOfParameters2(1,2,3,4,5)?  

lotsOfParameters2() & lotsOfParameters2(1,2,3,4)  

##Q4

Consider the function below:  

def lotsOfParameters3(a,b,c=3,d=4,e=5):  
    print a  
    print b  
    print c  
    print d  
    print e  

Which of the following function calls will result in an error?  

V - lotsOfParameters3()  
X - lotsOfParameters3(1, 2)  
V - lotsOfParameters3(1, c=2)  
V - lotsOfParameters3(1, c=2, 3)  
X - lotsOfParameters3(1, c=2, b=3)  

Which of the following function calls will produce the same output as calling lotsOfParameters3(1,2,3,4,5)?  

X - lotsOfParameters3()  
V - lotsOfParameters3(1,2)  
V - lotsOfParameters3(1,e=5,d=4,c=3,b=2)  
V - lotsOfParameters3(e=5,d=4,c=3,b=2,1)  
V - lotsOfParameters3(e=5,a=1,d=4,b=2,c=3)  
