The list method
============
````ruby
n = int(input())
list = []
for i in range(97, n + 97):
    s = [chr(i)]
    list += s
print(list)
````
````ruby
list = []
for i in range (26):
    list.append(chr(ord('a') + i)*(i+1))
print(list)
````
````ruby
list = []
n = int(input())
for i in range (n):
    s = input()
    list.append (s)
ind = int(input())
k = ''
for s in list:
    if len(s) >= ind:
        k += s[ind - 1]
print (k)
````
````ruby
list = []
list2 = []
n = int(input())
for i in range (1, n + 1):
    nx = int(input())
    list.append(nx)
    q = nx * nx + 2*nx +1
    list2.append(q)
print(*list, sep = '\n')
print()
print(*list, sep = '\n')
````
````ruby
n = int (input())
list = []
for i in range (n):
    num = int(input())
    list.append(num)
for j in list:
    if j != min(list) and j != max(list):
        print (j)
````
````ruby
n = int (input())
list = []
for i in range (n):
    s = input()
    list.append (s)
sch = input()
for s in list:
    if sch.lower() in s.lower():
        print(s)
````
````ruby
n = int (input())
list = []
lis = []
li = []
for i in range (n):
    list.append (input())
m = int(input())
for j in range (m):
    lis.append(input())
for h in range (len(list)):
    count = 0
    for g in range(len(lis)):
        if lis[g].lower() in list[h].lower():
            count +=1
        if count == len(lis):
            li.append(list[h])
print (*li, sep= "\n")
````
