# python-week-two-assignment
my_list = []
for value in [10, 20, 30, 40]:
my_list.append(value)          # append() adds an element to the end of the list :contentReference[oaicite:0]{index=0}
my_list.insert(1, 15)              # insert(index, value) adds value at the given index :contentReference[oaicite:1]{index=1}
my_list.extend([50, 60, 70])       # extend(iterable) appends all elements from the iterable :contentReference[oaicite:2]{index=2}
my_list.pop()                      # pop() with no index removes and returns the last item :contentReference[oaicite:3]{index=3}
my_list.sort()                     # sort() sorts the list in place :contentReference[oaicite:4]{index=4}
index_of_30 = my_list.index(30)    # index(value) returns the first index of value :contentReference[oaicite:5]{index=5}
print("Final list:", my_list)
print("Index of 30:", index_of_30)
