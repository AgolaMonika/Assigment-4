# Assigment-4
print("Enter number of element")
var arr : [Int] = [10,5,10] 
print(arr)
var first=arr[0]
var second=arr[0]
for i in arr{
  if first<i{
    second=first
    first=i
  }
  if(i > second && i != first){
    second=i
  }
}
if second==first{
  print("Not Found ",first,second)
}
else{
  print("second largest element is ",second)
}

