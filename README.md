# Write-a-python-program-to-find-the-average-of-the-list-of-the-numbers-entered-through-keyboard.-
n=int(input("Enter the limit:"))
s=0
for i in range(1,n+1):
    print("Enter ",i,end='')
    a=int(input("The number:"))
    s=s+a
avg=s/n
print("The sum of entered numbers:",s)
print("The average of entered numberes:",avg)

OUTPUT:

Enter the limit:1
Enter  1The number:5
The sum of entered numbers: 5
The average of entered numbers: 5.0
