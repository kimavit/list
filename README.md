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
