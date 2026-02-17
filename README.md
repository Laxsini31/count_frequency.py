numbers=list(map(int,input("Enter numbers: ").split()))
x=int(input("Enter element: "))
count=0
for i in numbers:
    if i==x:
        count+=1
print("Frequency:",count)
Output
Enter numbers: 1 2 2 3 2 4
Enter element: 2
Frequency: 3
