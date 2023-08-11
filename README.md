- 👋 Hi, I’m @kalpitkaushik
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
kalpitkaushik/kalpitkaushik is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->####
weight = float(input('weight: '))
unit = input('(L)bs or (K)g: ')
if unit.upper() == 'L':
    converted = weight * 0.45
    print(f"You are {converted} kilos")
else:
    converted = weight/0.45
    print(f"You are {converted} pounds")
####
secret_number = 8
guess_count = 0
guess_limit = 3
while guess_count < guess_limit:
    guess = int(input('Guess: '))
    guess_count += 1
    if guess == secret_number:
        print("you Won")
        break
else:
    print("Sorry You Failed")
    ######
ccommand = ""
started = False
while True:
    command = input("> ").lower()
    if command == "start":
        if started:
            print("Car is already started")
        else:
            started = True
            print("car started...")
    elif command == "stop":
        if not started:
            print("car is already stopped")
        else:
            started = False
            print("car stopped")
    elif command == 'help':
        print("""
        start - to start the car
        stop - to stop the car 
        quit - to quit""")
    elif command == "quit":
        break
    else:
        print('I do not understand')
        ####
        



  

