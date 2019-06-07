## Exercise I

a)
The loop multiplies n with each loop ==> O(n) 


b)
Three of the loops run n times ==> O(n^3)

c)
Using a recursive function makes it linear ==> O(n)



## Exercise II
break_floor = f
top_floor = n

while loop: while x in range(n - 1)
    x is the floor you are on
    if x is greather than or equal to break_floor:
        print a warning "Eggs will break from this height, DO NOT DROP"
    if x in less than break_floor:
        print "Eggs are safe to drop from this height"

Could also break the function when x is greater than or equal to break_floor to prevent eggs from going up to an unsafe floor.

This would be linear since it loops through n one time with each loop ==> O(n)


