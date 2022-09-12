    from math import sqrt
    def lists():
        lst =  []
        n = 5
        for i in range(0,n):
            ele = float(input())
            lst.append(round(math.sqrt(ele),2))  


        print(lst)
        print(type(ele))
        
        Input : 25
                36
                47
                64
                72
        Output: [5.0,6.0,7.0,8.0,9.0]
                <class 'float'>
