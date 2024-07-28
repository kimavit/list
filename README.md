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
