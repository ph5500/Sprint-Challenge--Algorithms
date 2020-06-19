#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) The runtime of this would be linear or O(n) considering that the size of the input affects the number of times it runs. In this example, the code will run "n" number of times

b) In this examples, the runtime would be O(n log n) because as the input size increases, the complexity will also gradually grow. An example of this is when "n" equals 2, the function only runs twice, however when the input is 10, it will run 40 times before the loop stops.

c) The runtime fo this would also be linear or O(n) because as the inputs increase, the runtime increases proportionally. This function should run twice for each input.

## Exercise II

To find the floor "f" I would first start by trying to determine the middle floor. If the egg doesn't break at the middle, I would then move up to the point halfway between current floor and the top floor. I would continue to move the midpoint based on if the egg broke or not to determine the safe dropping distance. If the egg broke at the middle floor, I would move to the floor that is halfway between the current floor and the ground floor and repeat the same process as above. For this problem, we would use a binary search tree with a runtime of O(log n)
