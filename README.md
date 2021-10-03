# Factorial-Trailing-Zeroes

<!--
Note - Any content mention below in `<!-- ->` blocks are just comments
to help you fill-up the issue. It won't be visible in the actual issue after
you click on submit.
-->



#### Code you used for Submit/Run operation


```
// Factorial Trailing Zeroes
class Solution {
    public int trailingZeroes(int n) {
      int base = 5;
        int count=0;
        while(n>=base){
            count+= n/base;
            base=base*5;
        }
        return count;
        
    }
}
```

#### Language used for code
java 


#### Expected behavior
<!-- A clear and concise description of what you expected to happen in
contrast with what actually happened. -->
this problem is based on maths if you know how to apply the math or logic to get the output then you are good to go :)

#### Screenshots

![count number of pairs](https://user-images.githubusercontent.com/53940939/135705418-3f7bcb40-ef0f-4979-b4ba-023a5980ac36.png)






Thankyou :)
