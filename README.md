# new
try:
    a=int(input())
    b=int(input())
    c=a+b
    d=a-b
    e=a/b
    print(c)
    print(d)
    print(e)

except ZeroDivisionError:
    print("galat hai bro")
except ValueError:
    print("galat value")
except TypeError:
    print("galat type hai")
except:
    print("value dalo")
else:
    print("shabas bete")
finally:
    print("chal ja **")
