import sympy
x = 0
def g_b_f(i):
    b = i
    x = 0
    listy_list=[]
    while b >= 1 and x == 0:
        print('step 0')
        if b == 0:
            x = 1
        if i % b == 0 and b != 0:           
            if sympy.isprime(b) == True and b != 0:
                print('step 1')
                listy_list.append(b)
                if len(listy_list) >= 6:
                    x= 1
                else:
                    b -= 1
                    x = 0

            if sympy.isprime(b) == False and b != 0:
                b -= 1
                print('step 2')
                x=0 
        if b!= 0 and i % b!= 0:
            print('step 3')
            b -= 1
            x = 0
    print(listy_list)



g_b_f(2620)
print(listy_list)