# my-calculatrice-from-python
Pyhton coding
print("hello, what calculation do you want to do?")
h=input("calculation :")
if h=="division":
    print("Okay, give me each part of your fraction")
    a = float(input("the numerator :"))
    b = float(input("the denominator :"))
    if b==0:
        print("undefined form")
    else:
        print(a/b)
elif h=="addition":
    print("Okay, give me your calculation")
    c=float(input("First term :"))
    d=float(input("Second term :"))
    print(c+d)
elif h=="subtraction":
    print("Okay, give me your calculation")
    e=float(input("First term :"))
    f=float(input("Second term :"))
    print(e-f)
elif h=="multiplication":
    print("Okay, give me your calculation")
    g=float(input("First term :"))
    i=float(input("Second term :"))
    print(g*i)
else:
    print("But what are you doing there nigga?")
