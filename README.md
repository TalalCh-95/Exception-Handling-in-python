# Exception-Handling-in-python
a = input("enter the number :")
print(f"multiplication table of {a} is :")
try:
    for i in range(1,11):
      print(f"{int(a)} x {i} = {int(a)*i}")
except:
       print("Invalid Input!")
       
  
