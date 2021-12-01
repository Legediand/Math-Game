# Math-Game
Fun math challenge, grade 6-8 math
name = input("What is your name?: ")
print("Hello " + name+ "!" )
print("This is a simple math challenge")
print("This challenge has 4 levels of basic math, with a bonus question at the end")
print("Answer questions correctly to move on to more advanced levels")
print("If you get one question wrong, you lose, GOOD LUCK!!!")


e1 = input("What is 2+2?: ")
if e1 == "4":
    print('Correct!')
    e2 = input("What is 4+4?: ")
    if e2 == "8":
        print('Correct!')
        e3 = input("What is 8+8?: ")
        if e3 == "16":
            print('Correct!, Level Passed')
            print('Level 2, Subtraction')
            e4 = input("What is 100 - 26?: ")
            if e4 == "74":
                print('Correct!')
                e5 = input("What is 86-25?: ")
                if e5 == "61":
                    print('Correct!')
                    e6 = input("What is 78 - 150?: ")
                    if e6 == "-72":
                        print('Correct!, Level PASSED')
                        print('Level 3, Multiplacation')
                        e7 = input("What is 15 x 2?: ")
                        if e7 == "30":
                            print('Correct!')
                            e8 = input("What is 11 x 12:")
                            if e8 == "132":
                                print('Correct!')
                                e9 = input("What is 100 x 100?: ")
                                if e9 == "10000":
                                    print("Correct!, Level PASSED")
                                    print("Level 4, Divison")
                                    e10 = input("What is  81/9?: ")
                                    if e10 == "9":
                                        print('Correct!')
                                        e11 = input("What is 144/2?: ")
                                        if e11 == "72":
                                            print("Correct!")
                                            e12 = input("What is 270/5?: ")
                                            if e12 == "54":
                                                print('Correct, Level PASSED')
                                                print("Congratulations you have completed the challege!")
                                                print("If you would like solve this bonus question you may")
                                                print("If you don't want to just press stop(this is 6th - 7th grade math")
                                                c1 = input("Do you want to answer the bonus question?(type yes or no): ")
                                                if c1 == "yes":
                                                    BONUS = input('What is 2(5+3)72+91?: ')
                                                    if BONUS == "1243":
                                                        print("Congratulations, you have reached the end of this challenge!")
                                                    else:
                                                        print('Nice try, but unfortunately you were wrong')
                                                else:
                                                    print('Congrats you have completed the base challenge!')
                                            else:
                                                print("Incorrect, GAMEOVER")
                                        else:
                                            print("Incorrect, GAMEOVER")
                                    else:
                                        print("Incorrect, GAMEOVER")
                                else:
                                    ("Incorrect, GAME OVER")
                            else:
                                print("Incorrect, GAMEOVER")
                        else:
                            print('Incorrect, GAMEOVER')
                    else:
                        ("Incorrect, GAMEOVER")
                else:
                    print("Incorrect, GAMEOVER")
            else:
                print("Incorrect, GAMEOVER")
            
        else:
            print('Incorrect, GAMEOVER')
            
    else:
        print('Incorrect, GAMEOVER')
else:
    print('Incorrect, GAMEOVER')
