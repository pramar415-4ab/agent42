
try:
    a = 10
    b = 27 
except ZeroDivisionError:
    print("You can't divide by zero!")
    
except ValueError:
    print("Enter a valid number!")
    
else:
    print("Result is", b)
    
finally:
    print("Execution complete.")
