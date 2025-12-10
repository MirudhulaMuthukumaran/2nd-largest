n=int(input("Enter number of elements:"))
a=[]
for i in range(1,n+1):
    b=int(input("Enter element:"))
    a.append(b)
a.sort()
print("Second largest element is:",a[n-2])


OUTPUT:
Enter number of elements:5
Enter element:6
Enter element:9
Enter element:2
Enter element:4
Enter element:3
Second largest element is: 6

