def prime(n):
 key = 0
 for i in range(2,n):
   if (n%i == 0):
       key = 1
 if(key==1):
   return False 
 return True

n = int(input("enter number"))
print(prime(n))
