# fabonacci-series
A programme to generate fibonacci series up to certain limit.
limit=int(input("enter the limit:"))
a,b=0,1
while a<=limit:
print(a,end=" ")
a,b=b , a=b
