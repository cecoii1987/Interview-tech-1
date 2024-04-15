# Interview-tech-1

From a list of numbers, move zero to the end of the list
list = [1, 0, 2, 0, 4, 6]
for item in list:
    if item == 0:
      list.remove(item)
      list.append(item)
print(list)
Output
[1, 2, 4, 6, 0, 0]
