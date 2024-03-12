# storing-elements-in-lists
'''
# approach1
n=int(input())
a=[]
for i in range(n):
  x = int(input())
  a.append(x)
print(a)
'''

# approach2
n=int(input())
a=[]
for i in range(n):
  x = int(input())
  a.insert(0,x)
print(a)

# approach3
n=int(input())
a=list(map(int,input().split()))
print(a)

# approach4
n=int(input())
a=list(map(int,input().split()))
x = int(input())
res=None
for i in range(n):
  if x == a[i]:
    res = i
if res == None:
  print("Element not found")
else:
  print(res)

# approach5
n=int(input())
a=list(map(int,input().split()))
x = int(input())
for i in range(n):
  if x == a[i]:
    print(i)
    break# storing-elements-in-lists
