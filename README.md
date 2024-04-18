# Rock-paper-Scissors
import random
def play():
    l=["rock","paper","scissor"]
    p1=input("Enter player1 name:")
    p2=input("Enter player2 name:")
    while(1):
        ch=input("Enter a value")
        pp1=random.choice(l)
        pp2=random.choice(l) 
        print(pp1)
        print(pp2)
        if(pp1==pp2):
            print("Draw")
            continue
        elif pp1=="rock" and pp2=="scissor":
            print(p1,"Wins")
        elif pp1=="paper" and pp2=="rock":
            print(p1,"Wins")
        elif pp1=="scissor" and pp2=="paper":
            print(p1,"Wins")
        elif pp1=="rock" and pp2=="paper":
            print(p2,"Wins")    
        elif pp1=="paper" and pp2=="scissor":
            print(p2,"Wins")
        elif pp1=="scissor" and pp2=="rock":
            print(p2,"Wins")
play()        
