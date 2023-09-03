# Rock-paper-scissor
result1 = 0
result= 0

print('Rock! paper! scissors!!')
l1=['rock','paper','scissors']
import random

r1=int(input('How many rounds do you want to play?'))
while True:
    p1=input("Enter your choice:")
    if p1 not in l1:
        break
        print('Invalid')
    p2=random.choice(l1)
    print(p2)
    if p1 == p2:
        result1==0 and result==0
        print("Tie!")
    elif p1=='rock':
        if p2=="paper":
            result+=1
            print('Computer scores')
        else:
             result1+=1
             print('You scores')
    elif p1=='scissors':
         if p2 =="rock":
             result+=1
             print('Computer scores')
         else:
             result1+=1
             print('You scores')
    elif p1=='paper':
        if p2=='rock':
            result1+=1
            print('You scores')
        else:
            result+=1
            print('Computer scores')
    print('Your score:',result1,'\nComputer score:',result)
    if result>result1:
       print('\nCOMPUTER WINS!!!')
       break
    elif result1>result:
        print('\nYOU WIN!!!')
        break
  
    nxt_round=r1
    if nxt_round==(r1+1):
        break
print('Game Over!!')
