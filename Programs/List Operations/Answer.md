    def listup1():
        lst = []
        n = 5
        for i in range(0,n):
            ele = int(input())
            lst.append(ele)
        print(lst[1::2])
        print(lst[0::2])
        tup = tuple(lst)
        print(len(tup))
        lst = list(tup)
        lst[1] =5
        tup = tuple(lst)
        print(tup)
        
        Input : 1
                2
                3
                4
                5
        Output :    [2, 4]
                    [1, 3, 5]
                    5
                    (1, 5, 3, 4, 5)
