try:
  d={}
  n=int(input())
  for i in range(n):
    k,v=input().split()
    d[k]=v
  while True:
    x=input()
    if x in d:
      print(f"{x}={d[x]}")
    else:
      print("Not found") 
except:
  pass
