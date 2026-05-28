print("welcome to quiz")
name=input("enter your name:")
print("hello",name,",let's start with the quiz..!")
score=0
print("question no.1")
print("what is the capital city of india?")
print("(a). mumbai ")
print("(b). new delhi")
print("(c). hydrabad")
ans1=input("enter your answer:")
if ans1 == "b":
    print("Correct!")
    score += 1
else:
    print("Wrong!")

print("question no.2")
print("what planet do we live on?")
print("(a). earth")
print("(b). mars")
print("(c). jupiter")
ans2=input("enter your answer:")
if ans2 == "a":
    print("Correct!")
    score += 1
else:
    print("Wrong!")

print("question no.3")
print("what is the colour of sky?")
print("(a). red")
print("(b). blue")
print("(c). purple")
ans3=input("enter your answer:")
if ans3 == "b":
    print("Correct!")
    score += 1
else:
    print("Wrong!")

print("question no.4")
print("7 + 5 = ?")
print("(a). 12")
print("(b). 11")
print("(c). 18")
ans4=input("enter your answer:")
if ans4 == "a":
    print("Correct!")
    score += 1
else:
    print("Wrong!")


print(name,"your final score:",score,"/4")
