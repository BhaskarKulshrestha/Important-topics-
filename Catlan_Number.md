# Catlan Numbers

    Catalan numbers are defined as a mathematical sequence that consists of positive integers, 
    which can be used to find the number of possibilities of various combinations. 
- Very useful to solve very complex problems.


## how many palinngdromic strings of length n if every element in the string can be taken from 'a' to 'z' ? 
 ```.py
 def t(n):
    if(n==0):
        return 1
    elif(n==1):
        return 26
    else:
        return 26*t(n-2)
    
n=4
print(t(n))
    
 ```
 
 ## Output
  - if n==0 : ans = 1
  - if n==1 : ans = 26
  - if n==2 : ans = 26
  - if n==3 : ans = 676
  - if n==4 : ans = 676 
