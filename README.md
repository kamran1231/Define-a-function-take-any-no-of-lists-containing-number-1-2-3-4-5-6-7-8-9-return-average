# Define-a-function-take-any-no-of-lists-containing-number-1-2-3-4-5-6-7-8-9-return-average


average = []

def average_finder(l1,l2,l3):
    for i in zip(l1,l2,l3):
        average.append(sum(i)/len(i))
    return average


l1 = [1,2,3]
l2 = [4,5,6]
l3 = [7,8,9]

print(average_finder(l1,l2,l3))
