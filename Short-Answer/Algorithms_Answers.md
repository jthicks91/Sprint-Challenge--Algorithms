#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) The running time for this block of psuedcode will be O(n) as the number of times it will run increases linerally with the size of n. 
    -When n is 1, it will run once, when n is 2 it will run twice, when n is 3... etc.

b) This block will be O(n^2). The block inside of the loops is O(1). both loops would be O(n) which resolves to being O(n^2).


c) O(n). The function recursively passes bunnies to itself and is decremented by one through each pass. The first case will exit when bunnies equals zero and thus it runs n times. 

## Exercise II


O(log(n)). Using binary search we will be splitting the amount of values to search through each time. 

Top floor is n and bottom would be O, if this eggs breaks, set this as the dummy top floor. If it doesnt, set this as the dummy bottom floor. If borth are 1, return the dummy top floor as the first floor and the egg breaks.

If it doesnt equal one, find halfway point between both top and bottom floor and repeat until it does.

