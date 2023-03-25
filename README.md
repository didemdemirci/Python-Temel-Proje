"# Python Temel >> Proje" 

Proje1:


l = [[1,'a',['cat'],2],[[[3]],'dog'],4,5]
l1 = []
def flatten(n):
    for i in n :
        if isinstance(i,list):
            flatten(i)
        else:
            l1.append(i)
flatten(l)
print(l1)

--------------------------------------------


Proje2:

def reverse(n):
 n = n[::-1]
 n = [i[::-1] for i in n]
 return n

liste=[[1, 2], [3, 4], [5, 6, 7]]


print(reverse(liste))


