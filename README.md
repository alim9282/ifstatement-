# ifstatement-
a = int(input("what is your age:"))
if a >= 18:
    b = int(input("you are wlecome what about your friend, how old is she?,is she older than 18 also:"))
    if b >=18:
        print("nice you are both welcome")
    elif b<18:
        c =input("are his/her legal parent")
        if c== "yes":
            d = input("can you show some id?")
            if d == "yes":
                print("nice you are both welcome")
            else:
                print("sorry i can not tlet him/her in")
        else: 
            print("sorry i can not tlet him/her in")
    else:
        print("you are both welcome")
else:
    print ("comon man don't you know age requirments stop wasting my time here get off")
