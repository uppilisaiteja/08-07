s=input()

x=" "

o=" "

for i in s:

    temp=True

    for j in x:

        if(i==j):

            temp=False

            break

    if(temp):

        x=x+i

for i in x:

    if i.isdigit():

        o=o+i

print(o)
