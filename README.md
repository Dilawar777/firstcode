def show(n): #recursive function
    if n==0: #base case
        return
    print(n)
    show(n-1)
    print("end")   # stacklaw

show(5)
