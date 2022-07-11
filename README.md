# rock-scissor-paper
#python


import random

a={1:"scissors",2:"rock",3:"paper"}


com=a[random.randint(1,3)]

you=input("input(scissors,rock,paper):")

b={"scissors":"paper","rock":"scissors","paper":"rock"}

print("com:",com)

def aaa(com,you):

    if you==com:

        print("draw.")

    elif  b[com]==you:

        print("lose.")

    else :

        print("win.")


aaa(com,you)
    
