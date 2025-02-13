# Rock-paper-scissors
Future create this game also


###Rock paper scissors
###Rock wins sciccor, scissor win paper, paper win rock

import random
user_choice = int(input("Choose 0 for rock, 1 for paper, 2 for scissors = \n"))
if user_choice >= 3 or user_choice < 0:    
  print("invalid number")
else:    
  computer_choice = random.randint(0, 2)    
  print(f"computer choose is {computer_choice}")        
  
  if user_choice == 0 and computer_choice == 2:        
    print("you win")    
  elif user_choice == 2 and computer_choice == 0:        
    print("you lose")    
  elif user_choice > computer_choice:        
    print ("you win")    
  elif user_choice < computer_choice:        
    print("you lose")    
  elif user_choice == computer_choice:        
    print("its draw")    
