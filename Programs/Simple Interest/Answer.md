import math

    def sim_int(p,n,r): 
        p= int(input())
        n= int(input())
        r= int(input())      
        si = (p*n*r)/100    
        print("The Simple Interest is",si)
        return [p,n,r,si]
      
    Input : 3000
            5
            1
    Output : The Simple Interest is 150.0
             [3000,5,1,150.0]
        
