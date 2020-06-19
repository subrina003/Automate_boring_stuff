# Automate_boring_stuff
This is my repository of trying problems from the book "automate boring stuff with python". I am a beginner in programming world. 

#A flowchart to tell you what to do if it is raining


start=input("is it raining?enter yes or no: ")
if start.upper()=="YES":
    ask=input("have umbrella?enter yes or no: ")
    if ask.upper()=="YES":
        print("go outside!")
    else:
        print ("wait a while")
        count=0
        while count<=1000:
            ask_again=input("still raining? ")
            if ask_again.upper()=="YES":
                print ("wait a while")
                count+=1
            elif ask_again.upper()=="NO":
                break
    print("go outside!")
                
else:
    print("go outside!")
