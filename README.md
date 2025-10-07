# My_First_Project
Simple Calculator with Python

print("Welcom To Simple Caculator :) \n")



oper =input("Please Choose The Operator ( + , - , * , / ,  // , ** , % ) : ") #input the operator


if oper not in ['+' , '-' , '*' , '/' , '//' ,'**' , '%']:

   print(" Invalid Input :( \n Please Enter Valid Operator")

else:

   num1=int(input("\nEnter The First Number : ")) #first num inputing

   num2=int(input("\nEnter The Second Number : ")) #second num inputing
 

    #condetion For Operation
   if (oper == "+" ):      # Add Operator

       print("Result :", num1 + num2 ) 

   elif (oper == '-'):     # Subtract Operator

        print("Result :", num1 - num2 )

   elif (oper == '*'):     # Product Operator
     
        print( "Result :",num1 * num2 )

   elif (oper == '/'):     # Devision Operator
       if (num2 !=0):

        print( "Result :",num1 / num2 )

       else:

           print("Error: Division By Zero")

   elif (oper == '//'):     # Floor Devision Operator
       if (num2 !=0):

         print("Result :",num1 // num2 )

       else:

           print("Error: Division By Zero")

   elif (oper == '**'):    # Exponent Operator

       print("Result :", num1 ** num2 )

   else:                   
       if (num2 !=0):

         print("Result :", num1 % num2 )  #Modulus Operator

       else:

           print("Error: Division By Zero")

    
       #End code >__<
                  






























