# Core Python.
## Python Download.

    https://www.python.org/downloads/
    
## Pycharm Download.
    https://www.jetbrains.com/pycharm/download/#section=windows

## Basic Concepts of Python:
### Data types in python:
 * Integer:
            
       operation on integers:
        a=20;
        b=30;
        c=a+b;
        print(c);
       answer=50..
   ### To find the length of an String:
       Name="Shashikumar reddy"
       print(name[0:7]);
       Answer:Shashi
    ### To find the length of an String in rev (only single word) :
         Name="Shashikumar reddy"
         print(name[-4]);
         Answer:e
   ### How to comment in single line:
      
          #Shashi is too lazy.
          #Anand works hard.
   ### How to comment in multiline:
        """
        Work hard for better process.
        Otherwise its tough to survive 
        in the society.
        """
   ### How to convert the integer to float type:
         age=20;
         new_age=float(age)
         print(new_age)
         Answer:20.0
         
  ### To cancatinate a string:
  eg:1
  
     first='shashi';
     last='kumar';
     middle=first+last;
     print(middle)
     Answer:shashikumar
   eg:2:
   
        first='shashi';
        last='kumar';
        middle=f' {first} {last} is a coder';
        print(middle)
        Answer:shashikumar is a coder
     
   ### If you want to write in UPPER case of a given String :
   eg:
             
         shashi="Python for Beginers";
         print(shashi.upper());
         Answer:PYTHON FOR BEGINERS.
       
   ###  write in UPPER case of a given String :
         shashi="Python for Beginers";
         print(shashi.lower());
         Answer:python for beginers
         
   ### To find the length of a String:
        shashi="Python Developers has a Great Demand";
        print(len(shashi));
        Answer:36
   ### To Replace the String or  a words in it:
       shashi=("Python for web designing");
       print(shashi.replace("web designing","Machine Learning it has a great score until 2 decades");
       Answer:Python for Machine Learning it has a great scope until 2 decades.
   
   ### To find whether String is 'True' or 'False'.
   eg1:
   
       shashi=" Shashi want to work hard in one field."
       print(shashi.replace('in one field', 'in many fields'))
       print('Shashi want to work' in shashi)
       Answer:True.
       
   eg2:
   
       shashi=" Shashi want to work hard in one field."
       print(shashi.replace('in one field', 'in many fields'))
       print('shashi want to work' in shashi)
       Answer:False//because where  's' in small letter in 
       shashi where as original it has Shashi so the answer is false.
      
   ### Operators:
   #### Arthimetic Operations:
        
  * rules:
  
        1. parenthesis.
        2. exponential.eg:2**3///ans =8
        3. multiplication or division .
        4. addition or subtraction.
   eg1:
   
        a=2+5;
        print(a);
        Answer:7
   eg2:
   
        a=((4+5)+20*9);
        print(a);
        answer:189
   eg3:
        
        a = ((4 *5) * 20 + 9);
        print(a);
        Answer:409
  
  ### Assignment Operator: 
        Assignment operator is used to a assigning the value to the variable.
 
    eg:
         x=3;
         x=x+3; or x+=3 are both same.
         answer:6
      
   ### Comparision Operator:
        This operator compares two or many values and reply that true or false.
        
       eg1:
            x = 5
            y = 3
            print(x == y)
            Answer:False.
        eg:2
            x = 5
            y = 3
            print(x != y)
            Answer:True.
   ### Logical operators:
        Logical Operators used to combine two or many conditional statements:
        There are basic logical operators they are:
           1.AND (here both conditions should be true otherwise ans will be false)
           2.OR  (here any one condition should be true)
           3.NOT ( Reverse the result, returns False if the result is true )
        AND eg1:
           x = 5
           print(x > 3 and x < 10)
            
        OR eg1:
           x=5
           x < 5 or x < 4
           
         NOT eg1:
            x = 5
            print(not(x > 3 and x < 10))
            ans:False;
            
###  Identity Operators:
        Identitity Opertors are use to compare the two objects,
        not if they are equal,actully they are same object with the same memory location.
          Two types they are:
          1.is
          2.is not
        
          x = ["apple", "banana"]
          y = ["apple", "banana"]
          z = x
          print(x is z)
          returns True because z is the same object as x
          print(x is y)
          return False because x is not the same object as y, even if they have the same content
          print(x==y) 
          return True because this is comparison returns True because x is equal to y.

        
        
        
          
            

        
        
       
       
        
        
        
   
        
   
