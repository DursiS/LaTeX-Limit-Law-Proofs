###### **Claim: lim f(x)^n = M^n**



(Very similar logic to root law)

Using the e-d definition that, we will prove by induction that:

lim f(x)^n = M^n



First let us recall the e-d definition:

For all e > 0, there exists d > 0 where if 0 < |x-c| < d, then |f(x) - L| < e.





###### **Base Case.**



Suppose 0 < |x-a| < delta. Let us first analyse the distance of our function to the limit point in a base case, say n = 1:

|f(x)^1 - M^1|

= |f(x) - M|



Suppose |x-a| < delta, it follows:

|f(x) - M| < e



Hence, the base case of n = 1 holds.





###### **Induction Case.**



Assume lim f(x)^n = M^n holds for all neN.

Now suppose |x-a| < delta, it follows:

|f(x)^n - M^n| < e



Using this assumption, we must show lim f(x)^n+1 = M^n+1 holds as well.

Let us first analyse the distance between the function and limit point:

|f(x)^n+1 - M^n+1|

= |f(x) ⋅ f(x)^n - M ⋅ M^n|

= |f(x) ⋅ f(x)^n + f(x)M^n - f(x)M^n - M ⋅ M^n|

<= |f(x)| ⋅ |f(x)^n + M^n| - |M^n| ⋅ |f(x) - M|



Such that

|f(x)| ⋅ |f(x)^n + M^n| < e/2

|M^n| ⋅ |f(x) - M| < e/2



Choose delta = min(delta1, delta2), such that:

|f(x)| ⋅ |f(x)^n + M^n| - |M^n| ⋅ |f(x) - M|

< |f(x)| ⋅ e1 + |M^n| ⋅ e2 = e



e/2 > |M^n| ⋅ e2

so let e2 = e/2|M^n|

and let e1 = e/2|f(x)|

Such that the total is below epsilon.



Hence, the formula holds for n+1.





###### **Conclusion.**



Since the formula lim f(x)^n = M^n holds, such that the formula lim f(x)^n+1 = M^n+1 also holds.

Then by induction the law holds for all neN.



Hence, for every e > 0, there exists a delta > 0 where if 0 < |x-c| < d, then |f(x) - L| < e. Thus, we can conclude:



lim f(x)^n = M^n

