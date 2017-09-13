# python-module-1
Module 1 of Python couse

# modified version of exercise from Chapter 3 (Overtime pay calculation)
sh = input("Enter Hours:")
try:
    fh = float(sh)
except:
    print("Error, please enter numeric input")
    sh = input("Enter Hours:")
    fh = float(sh)

sr = input("Enter Rate:")
try:
    fr = float(sr)
except:
    print("Error, please enter numeric input")
    sr = input("Enter Rate:")
    fr = float(sr)

if  fh > 40 :
    reg = fr * fh
    otp = (fh - 40.0) * (fr * 0.5)
    xp = reg + otp
else:
    xp = fh * fr
print("Pay:",xp)
