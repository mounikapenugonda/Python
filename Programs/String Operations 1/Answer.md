    def stringopss2():
        a= str(input())    
        position = 4
        count =0
        for i in range(len(a)):        
            if a[i] == a[position]:
                count = count+1
        print("Enter a string:",count)
        print(a.encode())
        print(a.isdigit())
        print(a.find('l',2,5))
        print(a.rfind('W'))
        
        Input : Hello World
        Output :    Hello World
                    Enter a string: 2
                    b'Hello World'
                    False
                    2
                    6
