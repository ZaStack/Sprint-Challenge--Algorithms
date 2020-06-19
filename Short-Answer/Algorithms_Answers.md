#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)O(n) - Linear because there is no loop. The whole algorithm is dependent on n, setting variables while a certain condition is met, but not repeating..


b)O(n^2) - Still runs a constant number of times which can be determined by the size of n. Each iteration will process in the same time and the runtime is only dependent on how many times the inner loop runs, thus the value of n sets the number of iterations. 

c)O(n) - Also linear. The iterations are dependent on n, but all it does is take n, perform an action till it can't anymore then give you what is left. It will run the exact amount of times as the value of n. You could determine how many ears there will be by just multiplying n by 2.

## Exercise II
Set an array to however many floors there are in the building. building = [1, 2, 3, 4, 5, .....] Starting at the midpoint, start tossing eggs. If the egg breaks, remove that floor and every floor higher than it and move to the middle of the remainder. If the egg doesn't break, toss out every floor lower than that but keep that floor. After a few iterations the remaining f should be the highest floor you can throw an egg from without breaking it. This is a binary search, so O(logn). The size of the building is n, and because the final f is more dependant on the egg than the building, a larger building will probably increase the number of passes it takes to eliminate the possibilities, a larger n doesn't increase complexity. The whole process will take longer, but each pass will take the exact same amount of time.


