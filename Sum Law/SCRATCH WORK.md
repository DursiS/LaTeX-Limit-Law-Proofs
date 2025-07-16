Claim: lim f(x) + g(x) = M + N



Using the e-d definition that, we will directly prove that:

lim f(x) + g(x) = M + N



First let us recall the e-d definition:

For all e > 0, there exists d > 0 where if 0 < |x-c| < d, then |f(x) - L| < e.



Suppose 0 < |x-a| < delta. Let us analyse the distance from the function and its limit point:

|(f(x) + g(x)) - (M + N)|

= |f(x) - M + g(x) - N|

= |f(x) - M| + |g(x) - N|



Since we know the whole must be below epsilon. Lets analyse to find some delta1 and delta2 when each part is below say e/2, so the whole is below epsilon.

|f(x) - M| < e/2

|g(x) - N| < e/2



They're already below e/2.

So let delta 1 = e/2 and delta 2 = e/2.



Choose delta = e/2:

|(f(x) + g(x)) - (M + N)|

= |f(x) - M| + |g(x) - N|

< e/2 + e/2 = e



Hence, for every e > 0, there exists a delta > 0 where if 0 < |x-c| < d, then |f(x) - L| < e. Thus, we can conclude:

lim f(x) + g(x) = M + N

