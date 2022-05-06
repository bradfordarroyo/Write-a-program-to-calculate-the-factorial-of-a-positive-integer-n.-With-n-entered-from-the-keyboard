# Write-a-program-to-calculate-the-factorial-of-a-positive-integer-n.-With-n-entered-from-the-keyboard
Write a program to calculate the factorial of a positive integer n. With n entered from the keyboard. For example, n = 8 then the output should be 1*2*3*4*5*6*7*8 = 40320
n = int(input("Enter number to calculate factorial: "))
 
def lose(n):
     if n == 0:
         return 1
     return n * periodLoss(n - 1)
 
print (StageLoss(n))
