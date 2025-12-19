# Search-for-an-Item-in-a-List-and-Report-Its-Position

l=[2,58,95,999,65,32,15,1,7,45]
n=int(input("enter the number to be searched:"))
found=0
for x in l:
    if x==n:
        print("item found at position:",l.index(n)+1)
        found=1
    if found==0:
        print("item not found")











output:
enter the number to be searched:5
item not found



enter the number to be searched:58
item not found
item found at position: 2

