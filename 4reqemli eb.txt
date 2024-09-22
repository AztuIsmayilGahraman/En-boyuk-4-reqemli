# En boyuk
print("4 reqemli eded daxil edin")

abcd = int(input())

if(999 < abcd < 10000):
    abc = abcd // 10
    ab = abc // 10
    c = abc % 10
    b = ab % 10
    a = ab // 10
    d = abcd % 10
    
    A = max(a, b, c, d)
    # --------------------------------------------------------------------------------------------------------------------
    if(A == a):
        B = max(b, c, d)
        if(B == b):
            C = max(c, d)
            
            if(C == c):
                D = d
                print(A, B, C, D, sep='')
            else:
                D = c
                print(A, B, C, D, sep='')
        elif(B == c):
            C = max(b, d)
            
            if(C == b):
                D = d
                print(A, B, C, D, sep='')
                
            else:
                D = b
                print(A, B, C, D, sep='')
            
        else:
            C = max(b, c)
            
            if(C == b):
                D = c
                print(A, B, C, D, sep='')
                
            else:
                D = b
                print(A, B, C, D, sep='')
                
# --------------------------------------------------------------------------------------------------------------------
                
    elif(A == b):
        B = max(a, c, d)
        
        if(B == a):
            C = max(c, d)
            
            if(C == d):
                D = c
                print(A, B, C, D, sep='')
                
            else:
                D = d
                print(A, B, C, D, sep='')
            
        elif(B == c):
            C = max(a, d)
            
            if(C == a):
                D =d
                print(A, B, C, D, sep='')
                
            else:
                D = a
                print(A, B, C, D, sep='')
            
        else:
            C = max(a, c)
            
            if(C == a):
                D = c
                print(A, B, C, D, sep='')
                
            else:
                D = a
                print(A, B, C, D, sep='')
            
# --------------------------------------------------------------------------------------------------------------------
        
    elif(A == c):
        B = max(a, b, d)
        
        if(B == a):
            C = max(b, d)
            
            if(C == b):
                D = d
                print(A, B, C, D, sep='')
                
            else:
                D = b
                print(A, B, C, D, sep='')
            
        elif(B == b):
            C = max(a, d)
            
            if(C == a):
                D = d
                print(A, B, C, D, sep='')
                
            else:
                D = a
                print(A, B, C, D, sep='')
            
        else:
            C = max(a, b)
            
            if(C == b):
                D = a
                print(A, B, C, D, sep='')
                
            else:
                D = b
                print(A, B, C, D, sep='')
            
# --------------------------------------------------------------------------------------------------------------------
        
    else:
        B = max(a, b, c)
        
        if(B == a):
            C = max(b, c)
            
            if(C == b):
                D = c
                print(A, B, C, D, sep='')
                
            else:
                D = b
                print(A, B, C, D, sep='')
            
        elif(B == c):
            C = max(a, b)
            
            if(C == b):
                D = a
                print(A, B, C, D, sep='')
                
            else:
                D = b
                print(A, B, C, D, sep='')
            
        else:
            C = max(a, c)
            
            if(C == a):
                D = c
                print(A, B, C, D, sep='')
                
            else:
                D = a
                print(A, B, C, D, sep='')
# --------------------------------------------------------------------------------------------------------------------
    
else:
    print("daxil etdiyiniz reqem 4 reqemli deyil")