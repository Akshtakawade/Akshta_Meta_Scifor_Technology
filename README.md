#Find sum of list elements
list1 = [1,2,5,7,9,10]
sum=0
for i in list1:
sum=sum+i
print("sum of list is :",sum)

#Largest element in a list
list1 = [1,2,5,7,9,10]
print(max(list))

#Remove Duplicates in a list
list1 = [1,2,5,7,9,10,2,9,1]
print(list1(set(list1)))

#Check if all elements in a list are unique
list1 = [1,2,5,7,9,10]
unique = []
for num in a:
if num not in unique:
unique.append(num)
print(unique)

#Program to reverse list
list1 = [1,2,5,7,9,10]
print(list1[::-1])

#Count no of odd n even numbers in a list
list1 = [1,2,3,4,5,6,8,9,10,13,14,15,16]
even=0
odd=0
for i in list1:
if i %2 ==0:
even +=1
else:
odd +=1
print("even number",even)
print=("odd number",odd)

#Check if a list is subset of another list
list1 =[1,2,3,4,5]
list2 = [3,5]
is_subset = all(item in list1 for item in list2)
print(is_subset)

#Max diff btw two consecutive elements in a list
def max_diff(lst):
return max(abs(lst[i] - lst[i - 1]) for i in range(1, len(lst)))
numbers = [1, 6, 8, 10, 4]
print(max_diff(numbers))

#Merge Multiple dictionaries
d1 = {1:"a",2:"b"}
d2 = {3:"c",4:"d"}
d3 = {5:"e",6:"f"}
d = {**d1,**d2,**d3}
print(d)

#Find words frequency in a sentence
string = "Data science is the study of data analysis"
str = {i: string.count(i) for i in set(string)}
print(str)
