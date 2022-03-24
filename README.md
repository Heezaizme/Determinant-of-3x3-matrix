# Determinant-of-3x3-matrix
a = int(input("enter the A's value : "))
b = int(input("enter the B's value : "))
c = int(input("enter the C's value : "))
d = int(input("enter the D's Value : "))
e = int(input("enter the E's value : "))
f = int(input("enter the F's value : "))
g = int(input("enter the G's value : "))
h = int(input("enter the H's Value : "))
i = int(input("enter the I's Value : "))
aa = (e*i-h*f)
bb = (d*i-g*f)
cc = (d*h-g*e)
aaa = aa*a
bbb = bb*b
ccc = cc*c
Det = aaa-bbb+ccc
print("Determinant of the given 3x3 matrix is : ", Det)
