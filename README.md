def describe(**kwargs):
    for key,value in kwargs.items():
        print(f"{key},{value}")

describe(name="noorulhassan", age=23,city="mardan") 


fruits=["banana","apple","cherry","appricot"]
for i in fruits:
    if(i=="apple"):
        print("yes found")
        break
    print(i)

name=list(filter(lambda x: x=="apple",fruits)) 
print(name)  


numbers=[12,34.44,55,63,93,30,30,50,34,37,32,47]

for i in numbers:
    if (i <=50):
        continue
    elif (i>=49):
        break   

print(numbers)


number=[11,22,132,1,5,6,7,11,13,44,15,17,18,22]
def evenv(x):
    return x % 2 ==0



