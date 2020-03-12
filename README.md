# help-Deja-Brew
help for a backwood forest/ Deja Brew /py
Hi, I've been trying for a while to get Deja Brew out of the Blackwood Forest without success. Will someone tell me where the error is in my code?

def potionsOnTheWall():
    potionsOnTheWall = 10

def numToTakeDown():
    numToTakeDown = 1
    

while True:
     
    
    hero.say("Take" + potionsOnTheWall + " potions of health on the wall!")
    # Chantez la ligne suivante:
    hero.say(potionsOnTheWall + "potions of health!")
    # Chantez la ligne suivante:
    
    potionsOnTheWall -= numToTakeDown
    hero.say("Take" + numToTakeDown + "down, pass it around!")
    # Chantez la dernière ligne:
    hero.say("Take" + potionsOnTheWall + "potions of health on the wall!")
    hero.say
