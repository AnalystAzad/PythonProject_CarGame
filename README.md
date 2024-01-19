# PythonProject_CarGame
command =""
started = False
while True:
    command = input (">").lower()
    if command == "start":
        if started:
            print ("car is already started!")
        else:
            started = True
            print ("Car Started....")
    elif command == "stop":
        if not started:
            print ("Car is already stopped")
        else:
            started = False
            print ("Car stopped.")
    elif command == "help":
        print ("""
start - to start the car
stop - to stop the car
quit - to quit
        """)
    elif command == "quit":
        break
    else:
        print ("Sorry! I don't understand")



This is a besic Python Car Game Projcet. You can see the start, stop and help output of a car from this programm. As a beginner this project was very nice and enjoyable to me. Hope you can try also. Thank you. 
