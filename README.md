# Ascending-Order in python
n = int(input())
arr = [int(input()) for i in range(n)]
arr.sort()
print("The Sorted array is:")
for i in range(0,n,1):
    print(arr[i])
