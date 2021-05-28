# prime-number

num=int(input("enter the number")) 
if num>1:
   for i in range(2,num) :
       if(num%i)==0:
       Print(num, "is not a prime number") 
       Break
     else:
       Print(num, "is a prime number") 
   else:
     Print (num, " is not a prime number") 
 

Output:
enter the number 13
13 is a prime number
   

