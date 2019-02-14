import numpy as np
import matplotlib.pyplot as plt
def A_(B,C):
    D = 2*C-B
    return D
def XX_vec(d,W):
    return np.matmul(d,W)
B = np.matrix('-1;2')
C = np.matrix('2;2')
P = np.matrix('1;-1')
A = np.matrix([np.roots((1,-10,20))])
W = np.transpose(A)
d = np.matrix('-1,1')
t = np.linspace(-np.pi,np.pi,100)
x = 5 + 3*np.cos(t)
y = 2 + 3*np.sin(t)
x1 = -1 + 3*np.cos(t)
y1 = 2 + 3*np.sin(t)
plt.plot(x,y)
plt.plot(x1,y1)
plt.grid()
plt.plot(B[0],B[1],'o')
plt.text(B[0]+0.1,B[1]+0.2,'(-1,2)')
plt.plot(C[0],C[1],'o')
plt.text(C[0]+0.1,C[1]+0.2,'(2,2)')
plt.plot(A_(B,C)[0],A_(B,C)[1],'o')
plt.text(A_(B,C)[0]+0.1,A_(B,C)[1]+0.1,'(5,2)')
plt.axis('equal')
plt.show()
print(XX_vec(d,W))
print(A)
print(A_(B,C))

