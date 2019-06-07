Add your answers to the Algorithms exercises here.
## Exercise I

#### Analysis - A
 - I believe the code below would result in O(N) because depending on input n, this will determine how many times the while loop is run which would give it a linear time complexity. O(N)

```
A)  a = 0
    while (a < n * n * n):
      a = a + n * n
```

#### Analysis - B

- I think that the code below results to O(N^4). I would say this because of the nested for loops. While the nested for loops run the input increases and all together they would result in O(N^4)

 ```
B)  sum = 0
    for i in range(n):
      i += 1
      for j in range(i + 1, n):
        j += 1
        for k in range(j + 1, n):
          k += 1
          for l in range(k + 1, 10 + k):
            l += 1
            sum += 1
```

#### Analysis - C
- I think the code below is O(n) beacuse it is a recursive function. As we move towards the base case, the number of bunnies decreases every time the function loops, which would tell me that there is a linear complexity of O(N).

```
C)  def bunnyEars(bunnies):
      if bunnies == 0:
        return 0

      return 2 + bunnyEars(bunnies-1)
```

## Exercise II
- I think this is best solved with a Binary Search Function which has a time complexity of O(log N).

- I could start on the middle floor of the building (n / 2). Then drop an egg if the egg breaks, then I would divide the floors under me by two again and repeat until I found f which would be a safe dropping distance. 

