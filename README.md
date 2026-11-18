
# list-comprehension
=A concise way to create lists in python 
compact and easier to read than traditional loops
[expression for value in iterable if condition]


traditional loops:

doubles =[]
for x in range(1,11):
    doubles.append(X*2)

print(doubles)

output:[2,4,6,8,10,12,14,16,18,20]



list comprehension:
examples for list comprehension 

doubles = [X*2 for X in range(1,11)]
triples = [X*3 for X in range(1,11)]

print(doubles)
print(triples)

output:
[2,4,6,8,10,12,14,16,18,20]
[3,6,9,12,15,18,21,24,27,30]



numbers = [1,-2,3,-4,5,-6]
positive_nums = [num for num in numbers if num>=0]
negative_nums = [num for num in numbers if num<0]
even_nums = [num for num in numbers in if num%2==0]
odd_nums = [num for num in numbers if num%2==1]

print(positive_nums)
print(negative_nums)
print(even_nums)
print(odd_nums)

output:
[1,3,5]
[-2,-4,-6]
[-2,-4,-6]
[1,3,5]

