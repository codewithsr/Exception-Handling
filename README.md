# Exception-Handling
#Use of Exception Handling
''' We use exception because think of a situation in which an error comes at line 
200(out of the 2000 line code program). This way the whole code(exception) stops there
 and not goes any further.
        But if we throw exception at that 200 line, then the code will continue to 
execute leaving that(line 200)

Ex: try:
       open("this.txt")
    except Exception as e:
        print(e)  (or pass)--> (Note: print(e) will show that exception handling 
occured while pass will not show anythig as such)

   So, if there does not exist the file("this.txt"), then the program will throw 
exception and continue the rest code(if exists further)
   Hence, in lamen terms, if I know that any code can give error then to bypass the
 situation, we use try, except or Exception handling in general.       
'''



#Finally
'''
    This is used to print the code in it whether or not the exception occurs i.e,
 finlally mei rakha hua code execute hoga hi hoga.
Ex: (Multiple execution handling with finally and else)
    try:
        print("I will try this code and will throw exception if there is any problem")
    exccept Exception as e:
        print("I will only run if try block fails")
    else:
        print("I will run only if there is no exception")
    finally:
        print("This will be printed in every case")

    Note: try and except are mutually exclusive. So only either try runs or exception
 runs.  

'''


