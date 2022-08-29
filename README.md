# remove-negative-elements-in-array-and-print-middle-elment in python
def removeNegative(arr):
    newArr = []
 
    for x in range(0, len(arr)):
        if (arr[x] >= 0):
            newArr.append(arr[x])
      # print(newArr)
    for x in range(0, len(newArr)):
        l=int(len(newArr)/2)
    #if new array size is even:
    if(len(newArr)%2==0):
        print(newArr[l-1])
    #if newarray size is odd:
    else:
        print(newArr[l])
    
    
        
    
 
# Driver Code
arr = []
for i in range(int(input())):
    arr.append(int(input()))
removeNegative(arr)
