# AALIYAh
main_game.py
#Aaliyah Sulton
# 11/29/2022

#Main Character and files
import MainCharacter #imports the MainCharacter file and all global variables
import Section_1
#Introduction to the game
print("Jeremiah Game Night")
print("Press any button to begin the game")
print("Jeremiah and his friends Alex,maddy,jay are having a conversation about who's gonna beat who in a bowling match")
print("Alex thinks he going to win the match so he insults Jeremiah and calls him a loser and Jeremiah gets offended")
response=input("How does Alex feel? B is Happy A is nervous C is Angry")
if response.upper()=="A":
    print("Alex is going to feel overwhelmed but is going have a few strikes in the game")
    MainCharacter.alexmood="nervous"
if response.upper() == "B":
    print("Alex is going to feel excited but hopes he makes atleast one strike in the game")
    MainCharacter.alexmood="happy"
if response.upper() == "C":
    print("Alex is going to feel Angry but has good luck he is going to beat all of his friends in the game")
    MainCharacter.alexmood="Angry"
Section_1.start()

#Alex tries to argue with jeremiah because he thinks he is going to lose.
print("Press the * Key if jeremiah should ignore alex ")
#Jeremiah ignores Alex and continues to play bowling
print("Press the W key if Alex should talk it out with jeremiah")
# Section_1

import Section_2
#Section_1.py
#Jeremiah main character
#import MainCharacter
def start():
    print("Group of friends decided to go bowling on a friday night")
#Press the U button if Jeremiah should pick up the bowling ball or press the Q key if Jeremiah should stay still.
    name=    input("Press the U button if Jeremiah should pick up the bowling ball or press the Q key if Jeremiah should stay still.")
    if name.upper()=="U":
        print("Jeremiah picked up the bowling ball")
    else:
        print("Jeremiah stayed still")
    #if MainCharacter.score == 10:
        #print("You got a strike!")
    #elif MainCharacter.score > 0:
        print("You didn't clear the lane!")

 Section_2.start()
 
 #import Statements
import Section_3

def start():
    #Take user input and check it with an if/else statement
 if response.upper()=="A":
     print("Maddy is going to feel nervous but feels confident that she's going to make a strike in the game")
print("Maddy takes a turn into the game and see if she could strike bowling pins" )
input ("Press the R key if Maddy should strike 3 bowling pins into the gutter")
input("Press the T key if Jeremiah should strike 2 bowling pins into the gutter")
input("Press the M key if Jay should strike 1 bowling pins into the gutter")
input("Press the W key if Alex should strike 4 bowling pins into the gutter")

#Section_3.py
#Aaliyah Sulton
#12/9/2022
#This section is the final part of the game
def start():
    print("Group of friends go bowling on a friday night")
    input("Press the O key if Jeremiah should go home or stay with his friends")
    print("Maddy makes a strike in the bowling match")
    print("Maddy tells jay that she will beat him in the bowling match")
    response=input("How does Maddy feel about making a strike? E is happy J is angry L is nervous")
    MainCharacter.maddymood="happy"
    if response.upper()=="E":
        print("Maddy is going to feel excited but scared she is going to lose")
        input("Press the H key if maddy should strike 4 bowling pins")
        print("Maddy scores and she ends the game with 50 points")
print("Jeremiah and his friends are done with the bowling match")
print("Jeremiah and his friends leave the bowling alley")
input("Press the * key to see each player scoreboard")
print("Maddy has a score of 50")
print("Jeremiah has a score of 30")
print("Jay has a score of 80")
print("Alex has a score of 40")


global alexmood3
global maddymood
global jaymood
global jeremiahmood

print("Alex has conversation with his friend maddy about who is going to win the bowling match")
print("Alex thinks he gonna lose the match but has confidence that he's going to win")
print("alexmood3 he is confident that he will win the game")
print("maddymood she is nervous that she will lose the game")
print("jaymood he is angry that everyone will beat him")
print("jeremiahmood he is excited to win or lose the game")

