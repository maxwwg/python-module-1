# python-module-1
Module 1 of Python couse

# grading app chapter 3
score = input("Enter score between 0.0 and 1.0\n")

try:
    sc = float(score)
except:
    print("Error: Score has to be a number between 0.0 and 1.0")
    quit()

if type(sc) == float and 0.0 <= sc <= 1.0 :
        if sc >= 0.9 :
            print("A")
        elif sc >= 0.8 :
            print("B")
        elif sc >= 0.7 :
            print("C")
        elif sc >= 0.6 :
            print("D")
        else:
            print("F")
else:
    print("Error: Score has to be a number between 0.0 and 1.0")
    quit()
