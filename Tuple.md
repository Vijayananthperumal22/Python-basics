```
my_tuple = ("apple",1,"cherry")
print(my_tuple)

#convert tuple into list
my_tuple = tuple(["pineapple","ooty apple",22])
print(my_tuple)

#access elemnt from tuple
item = my_tuple[1]
print(item)

#iteration in tuple
for x in my_tuple:
    print(x)
    
#check using if-else
if "pineapple" in my_tuple:
    print("yes")
else:
    print("no")
    
#check length of tuple
item = len(my_tuple)
print(item)

#count elemnt
print(my_tuple.count("pineapple"))

#indexing
print(my_tuple.index(22))

#tuple to list
my_list = list(my_tuple)
print(my_list)

#slicing
my_tuple_for_slicing = [1,2,3,4,5,6,7,8,9]
slicing = my_tuple_for_slicing[2:7]
print(slicing)

#reveese
slicing = my_tuple_for_slicing[::-1]
print(slicing)
```
