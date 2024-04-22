print("Player Registration Program")

name = input("Enter the player's name :")
surname = input("Enter the player's surname :")
team = input("Enter the player's team :")

print("Information is being saved...")

Information = [name,surname,team]

print("Player's name : {}\nPlayer's surname : {}\nPlayer's team : {}\n".format(Information[0],Information[1],Information[2]))

print("Information saved.")
