# Assignment 5


Direction=input()
x=0
y=0

for letter in Direction:
    if letter=='L' or letter=='l':
        x-=1
    elif letter=='R' or letter=='r':
        x+=1
    elif letter=='U' or letter=='u':
        y+=1
    elif letter=='D' or letter=='d':
        y-=1
print(x,y)
