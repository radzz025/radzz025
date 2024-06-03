#Operations on list
L1= [10,34,23,77,21]
print("list 1:", L1)
L1.append(31)
print("adding elements to the list:",L1)
L1.remove(10)
print("removing elements to the list:",L1)
L1[2] = 11
print("modifying elements to the list:n\n\n",L1)

#Operations on dictionary
sAge= {'ria': 10,'tia': 15,'dia': 17,'mia': 11,'nia': 18}
print("dictionary:", sAge)
sAge['kia']= 13
print("adding new elements to dictionary:",sAge)
del sAge ['tia']
print("deleting elements to dictionary:",sAge)
sAge ['dia']= 19
print("modifying elements to dictionary:\n\n\n",sAge)

#Operations on sets
set={2,3,4,5,6,7,8}
print("set:", set)
set.add(9)
print("adding elements to the set:",set)
set.remove(4)
print("removing elements to the set:",set)
set.discard(9)
print("another way of removing elements to the set:",set)
set.add(10)
print("adding elements to the set:",set)
