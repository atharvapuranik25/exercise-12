def countfromrange(list, min, max):
    """retuns a list with elements within the range of min and max value"""
    count = 0
    list2 = []
    for x in list:
        if min < x < max:
            count += 1
            list2.append(x)
    print(list2)
    print("Range: ", count)

while True:
    try:
        list_length = int(input("Number of elements in list: "))
        list = []
        for i in range(0, list_length):
            element = int(input("Enter the element: "))
            list.append(element)
        min = int(input("Minimum value: "))
        max = int(input("Maximum value: "))
        print(list)
        break
    except:
        print("Enter integer value")

countfromrange(list, min, max)
