###### **Claim: lim f(x)^1/n = M^1/n**



(Very similar logic to power law)

Using the e-d definition that, we will prove by induction that:

lim f(x)^1/n = M^1/n



First let us recall the e-d definition:

For all e > 0, there exists d > 0 where if 0 < |x-c| < d, then |f(x) - L| < e.





###### **Base Case.**



Suppose 0 < |x-a| < delta. Let us first analyse the distance of our function to the limit point in a base case, say n = 1:

|f(x)^1/1 - M^1/1|

= |f(x) - M|



Suppose |x-a| < delta, it follows:

|f(x) - M| < e



Hence, the base case of n = 1 holds.



###### **Induction Case.**



Induction hypothesis.

Assume lim f(x)^1/n = M^1/n holds for all neN.

Now suppose |x-a| < delta, it follows:

|f(x)^1/n - M^1/n| < e



Using this assumption, we must show lim f(x)^1/n+1 = M^1/n+1 holds as well.

Let us first analyse the distance between the function and limit point:

|f(x)^1/n+1 - M^1/n+1|

= |f(x)^1/1 ⋅ f(x)^1/n - M^1/1 ⋅ M^1/n|

= |f(x) ⋅ f(x)^1/n + f(x)M^1/n - f(x)M^1/n - M ⋅ M^1/n|

<= |f(x)| ⋅ |f(x)^1/n + M^1/n| - |M^1/n| ⋅ |f(x) - M|



Such that

|f(x)| ⋅ |f(x)^1/n + M^1/n| < e/2

|M^1/n| ⋅ |f(x) - M| < e/2



Choose delta = min(delta1, delta2), such that:

|f(x)| ⋅ |f(x)^1/n + M^1/n| - |M^1/n| ⋅ |f(x) - M|

< |f(x)| ⋅ e1 + |M^1/n| ⋅ e2 = e



|f(x)| ⋅ e1 < e/2

Then delta1 < e/2|f(x)|

|M^1/n| ⋅ e2 < e/2

Then delta2 < e/2|M^1/n|

Such that the total is below epsilon.



Hence, the formula holds for n+1.





###### **Conclusion.**



Since the formula lim f(x)^1/n = M^1/n holds, such that the formula lim f(x)^n+1 = M^n+1 also holds.

Then by induction the law holds for all neN.



Hence, for every e > 0, there exists a delta > 0 where if 0 < |x-c| < d, then |f(x)^1/n - L^1/n| < e. Thus, we can conclude:



lim f(x)^1/n = M^1/n









