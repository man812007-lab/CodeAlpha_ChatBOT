
def AIchaBot():
    print("ChatBot: You're Welcome to AI ChatBot type 'bye' to exit")

    
while True:
    user_input = input("You:").lower()

    if user_input in ["hi","hello"]:
        print("Hi")    
    
    
    elif user_input in ["how are you","how are you doing"]:
        print("I am fine. Thanks!")
    
    elif user_input in ["see you" , "take care" , "bye"]:
        print("Goodbye!")

    else: 
        print("Please Try something new!")
    
AIchaBot()
