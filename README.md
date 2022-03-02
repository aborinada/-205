import funk 
# Множественное присваивание 
print ("Hello void") 
a,b = 0,1 
a = 0 
b = 1 
a,b = b,a 
print (a,b) 
a = b = c = 1 
print (a,b,c) 
 
print(int(4.5)) 
print(int('4')) 
print(float(4)) 
print(float('4.5')) 
x = 1.787645 
print(round(x)) 
print(round(x,a)) 
 
# Ситсемы счисления 
print(int('11111111',2)) 
 
y=7 
print(bin(y)) 
print(hex(y)) 
print(oct(y)) 
 
#Вывод чисел 
a=6 
print('a=',a) 
print('a='+str(a)) 
 
a = 0.1+0.1+0.1-0.28 
print(a) 
print('{:.2f}'.format(a))
