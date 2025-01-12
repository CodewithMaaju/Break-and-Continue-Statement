# Break-and-Continue-Statement
Today we have completed the excercise on the break and continue statement. 
#Today we are going to learn about the break statement
#So lets get started
for i in range (1, 12, 3,):
  print(i)
  if i==4:
    print("This is the end")
    break
  #now dicuss about the continue statement. 
  #The continue statement is used to skip the current iteration and continue with the next iteration of the loop.
  #So lets get started
for i in (1, 3, 5, 6, 7, 8, 9, 10):
    if i!=9:
      print(i)
      continue
