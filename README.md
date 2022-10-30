import random 
x = 25 
while x < 50 and x > 0:
  u = (random.randrange(1,21))
  i = (random.randrange(1,21))
  print("tu jau gribēji zināt")
  y = (input("Davaj uzmini vairāk vai mazāk, varbūt vienāds :): "))
  if y == "<" and u < i:
    print("Uzvarēji")
    x = x + 2
    print("Credits:",x)
  elif y == ">" and u > i:
    print("Paveicas")
    x = x + 2
    print("Credits:",x)
  elif y == "=" and u == i:
    print("Tīrākā veiksme")
    x = x + 15
  else: x = x - 2
  print("Credits:",x)
    
