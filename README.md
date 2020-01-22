def sherpa():
    print("I can guide you, but it will take a while")
    print("It will cost you time with family and friends")
    print("Are you ready to leave now?")

    choice = input("> ")

    if "yes" in choice:
        sherpa_path()
    elif "no" in choice:
        print("You took the blue pill and went back to a normal life.")


def sherpa_path():
    print("You can take one of 3 items, 2 days of food, 1gal of water, or 1 outfit")
    choice = input("> ")

    if choice == "food":
        print("You eat well, but never discover the meaning of life. You died not knowing your purpose")

    elif choice == "water":
        print("You have a moment of clarity invest in new tech")
        print("You gain wealth but don't discover life's meaning")
        print("You die not knowing you purpose")

    elif choice == "outfit":
        print("You have an existential moment and discover life's purpose")
        print("You die happy and knowing!")


def worker():
    print("I will definitely point you in the right direction.")
    print("It won't be dangerous at all!")
    print("Are you ready to leave now?")

    choice = input("> ")

    if "yes" in choice:
        worker_path()
    elif "no" in choice:
        print("You are condemned to life as a greeter at Walmart :-(.")


def worker_path():
    print("He points you towards the east")
    print("You immediately stub your foot and scream out in pain")
    print("Do you continue working with the worker?")

    choice = input("> ")

    if choice == "yes":
        print("He apologizes and you keep moving.")
    elif choice == "no":
        print("You try on your own but get lost in the mountains")
        print("2 days later you get eating by a Yeti!")


def mercenary():
    print("When you're ready let's do it!")
    print("But you gotta kill a few people!")
    print("Do you still want to discover the meaning of life?")

    choice = input("> ")

    if "yes" in choice:
        mercenary_path()
    elif "no" in choice:
        print("You were afraid to take a chance.")
        print("Ended up being a walmart greeter for 25 years!")
        print("You die lonely and broke")


def mercenary_path():
    print("If you want to discover life's purpose, listen to everything I say")
    print("He gives you a gun")
    print("Orders you to shoot an innocent puppy")
    print("Do you shoot the dog?")

    choice = input("> ")

    if "yes" in choice:
        print("You shoot the dog and move on with the mission.")

    elif choice == "no":
        print("He charges you $1mil for his services")
        print("You can't pay and end up working as a get away driver")
        print("Life is short and you die in car crash trying to get away")


def start():
    print("You decide to go on a quest to discover the meaning of life!")
    print("A sherpa, worker and mercenary offer to help you")
    print("Who do you want to guide you")

    choice = input("> ")

    if choice == "sherpa":
        sherpa()
    elif choice == "worker":
        worker()
    elif choice == "mercenary":
        mercenary()


start()
