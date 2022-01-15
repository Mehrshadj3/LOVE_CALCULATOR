# LOVE_CALCULATOR



print("Welcome to the Love Calculator!")
name1 = input("What is your name? \n")
name2 = input("What is their name? \n")



a = name1.count("t")
b = name1.count("r")
c = name1.count("u")
d = name1.count("e")

a1 = name1.count("l")
b1 = name1.count("o")
c1 = name1.count("v")
d1 = name1.count("e")

a2 = name2.count("t")
b2 = name2.count("r")
c2 = name2.count("u")
d2 = name2.count("e")

a3 = name2.count("l")
b3 = name2.count("o")
c3 = name2.count("v")
d3 = name2.count("e")

sum1 = a + b + c + d + a1 + b1 + c1 + d1
sum2 = a2 + b2 + c2 + d2 + a3 + b3 + c3 + d3

love_score = str(sum1) + str(sum2)
lovescore = int(love_score)

if lovescore <= 10 and lovescore >= 90:
  print(f"Your score is {lovescore}, you go together like coke and mentos." )
elif lovescore >= 40 and lovescore <= 50:
  print(f"Your score is {lovescore}, you are alright together.")
else:
  print(f"Your score is {lovescore}.")
