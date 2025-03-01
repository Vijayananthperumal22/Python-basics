```
#getting list
my_list = ["apple","banana","cherry"]
print(my_list)

#getting index of the list
item = my_list[0]
print(item)

#getting index in reverse
item = my_list[-1]
print(item)

#iteration
for i in my_list:
    print(i)
    
#check using if-else list
if "cherry" in my_list:
    print("Yes")
else:
    print("NO")
    
#check the length of the list
print(len(my_list))

#append item in list
my_list.append("dragon")
print(my_list)

#inseting in specific location
my_list.insert(1,"blueberry")
print(my_list)

#remove element from list
item = my_list.pop()
print(item)
print(my_list)

#remove specific elemt frm list
item = my_list.remove("banana")
print(my_list)

# #to get empty list
# item = my_list.clear()
# print(my_list)

#reverse the list
item = my_list.reverse()
print(my_list)

#sort the list
item = my_list.sort()
print(my_list)

#list contain for muliplication
new_list = [1] * 5
print(new_list)

#adding to list
adding = my_list + new_list
print(adding)

#slicing
slicing = [1,2,3,4,5,6,7,8,9]
a = slicing[1:5]
print(a)

#all from list
a=slicing[::1]
print(a)

#every secound or 3d frm list
c = slicing[::2]
print(c)

#revese using slicing
b = slicing[::-1]
print(b)

#coping list or [:] or list(list_org)
list_org = ["avacado","betroot","cucumber"]

list_cpy = list_org.copy()

#new element in copy list
list_cpy.append("watermellon")

print(list_org)
print(list_cpy)

#squaring unsing list 

squaring_list = [1,2,3,4,5,6,7,8,9]
a = [i*i for i in squaring_list]
print(squaring_list)
print(a)
```
