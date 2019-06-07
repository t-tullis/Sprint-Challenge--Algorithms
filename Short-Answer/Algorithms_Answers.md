Add your answers to the Algorithms exercises here.
## Exercise I

```
A)  a = 0
    while (a < n * n * n):
      a = a + n * n
```

#### Analysis - A
 - I believe the above code would result in O(N) because depending on input n, this will determine how many times the while loop is run which would give it a linear time complexity. O(N)

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

#### Analysis - B

- I think that the above code results to O(N^4). I would say this because of the nested for loops. While the nested for loops run the input increases and all together they would result in O(N^4)

```
C)  def bunnyEars(bunnies):
      if bunnies == 0:
        return 0

      return 2 + bunnyEars(bunnies-1)
```

#### Analysis - C
- I Think the above code is O(n) beacuse it is a recursive function. As we move towards the base case, the number of bunnies decreases every time the function loops, which would tell me that there is a linear complexity of O(N).

