# ass-1-04-03-22
#write a program to count the duplicate elements in the list.
l=[]
n=int(input())
for i in range(n):
    x=int(input())
    l.append(x)
print(l)
res=[]
for i in l:
    if l.count(i)>1: 
        if i not in res:
          res.append(i)
print(i)

output:
5
1
2
5
2
1
[1,2,3,2,1]
2
