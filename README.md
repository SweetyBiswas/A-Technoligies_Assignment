# A-Technoligies_Assignment
li=[] 

def add(x,y):
    a=x+y
    print("addition of 2 no : ",a,'\n')
    li.append(a)
def sub(x,y):
    b=x-y
    print("Subtraction of 2 no : ",b,'\n')
    li.append(b)
def mul(x,y):
    c=x*y
    print("Multiplication of 2 no : ",c,'\n')
    li.append(c)
def div(x,y):
    d=x/y
    print("Division of 2 no : ",d,'\n')
    li.append(d)
    
def fd(x,y):
    e=x//y
    print("floor Division Of 2 No is : ",e,'\n')
    li.append(e)
    
def mod(x,y):
    f=x%y
    print("Remender is : ",f,'\n')
    li.append(f)
    
def exp(x,y):
    g=x**y
    print("Exponent Is : ",g,'\n')
    li.append(g)
    
def equal(x,y):
    if x==y:
        print('Given Numbers are Same','\n')
        h='Two Nos are Same'
        li.append(h)
    else:
        print('Given Numbers are Different','\n')
        i="Given Numbers are Different"
        li.append(i)
def com(x,y):
    if x>y:
        print('First No is Bigger','\n')
        j='First No is Bigger'
        li.append(j)
    else:
        print('Second No is Bigger','\n')
        k='Second No is Bigger'
        li.append(k)
        
def bitwise(x,y):
    print("Bitwise Operations : ",'\n')
    l=x & y
    m=x | y
    n=~x
    o=x ^ y
    p=x >> 2
    q=x << 2
    
    print(l)
    li.append(l)
    print(m)
    li.append(m)
    print(n)
    li.append(n)
    print(o) 
    li.append(o)
    print(p)
    li.append(p)
    print(q)
    li.append(q)
    
def logical(x,y):
    print("logical Operation : ",'\n')
    r=x>10 and x<100
    print('First no is greater than 10 but less than 100',r)
    li.append(r)
    s=x>10 or x<100
    print('First no in between 10 and 100',s)
    li.append(s)
    t=not(x>10 or x<100)
    print('First no not in between 10 and 100',t)
    li.append(t)
   
    
fn=int(input("enter 1st no : "))
sn=int(input("enter 2nd no : "))
print('\n')

add(fn,sn)
sub(fn,sn)
mul(fn,sn)
div(fn,sn)
fd(fn,sn)
mod(fn,sn)
exp(fn,sn)
equal(fn,sn)
com(fn,sn)
bitwise(fn,sn)
logical(fn,sn)


print('\n','Result Is : ',li)