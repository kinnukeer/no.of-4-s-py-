# no.of-4-s-py-
t=int(input())
a=[]
for i in range(t):
  x=int(input())
  a.append(x)
for x in a:
  c=0
  while x>0:
    r=x%10
    if r==4:
      c=c+1
    x=x//10
  print(c)
