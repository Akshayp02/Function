# Function
"""
# functions = a block of code which is executed only when it is called 

"""
def hello(name, last_name):
    print("hello.......!"+name + last_name)
    print("have a nice day..!")
my_name ="bro"
hello(my_name,"akshay")# bro argument
"""
return Statement = Function send python values object back to the caller.
                  these value objects are known as the  function a return value 

"""

def multiply(num1,num2):
    return num1 * num2

print(multiply(7,4))
"""
Keywords arguments = arguments preceded by an indentifire when we pass them to a function 
                    the order of the arguments doesent matter unlike poitiantial receivers

"""
def hellos(fist,middle,last):
    print("hello "+fist +" "+middle+ " "+last)


hellos(last="code",middle="dude",fist="bro")# this are keyword args
