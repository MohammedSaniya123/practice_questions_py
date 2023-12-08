# practice_questions_py
'''converting real numbers into  complex numbers
inbuilt  real for a  and b for imag means i value'''
import cmath
x = 7
y = 3
a = 8
b = 6
z1 = complex(x,y)
z2 = complex(a,b)
print("adding complex numbers",z1 + z2)
print("sub complex numbers",z1 - z2)
print("mul complex numbers",z1 * z2)
print("div complex numbers",z1 / z2)

    
   
#     multiple = (a1*a2+b1*b2,a2*b1-a1*b2)

# z1 = complex(a1 ,b1)
# z2 = complex(a2,b2)
  
  # x = 5
# y = 7
# z = complex(x,y)
# z = 2 + 3j

# print("real part of a complex number is: ",end =  "")
# print(z.real)

# print("imaginary part of a complex number is: ",end = "")
# print(z.imag)

      

'''Explanation: Phase of complex number Geometrically, the phase of a complex number is the angle between the positive real axis and the vector representing a complex number. This is also known as the argument of a complex number. Phase is returned using phase(), which takes a complex number as an argument. The range of phase lies from -pi to +pi. i.e from -3.14 to +3.14.'''
# x = -1
# y = 0
# z = complex(x , y)
# print("The phase ofcomplex number is: ",end = "")
# print(cmath.phase(z))
