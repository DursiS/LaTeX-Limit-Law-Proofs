Claim: lim f(x) - g(x) = M - N



Using the e-d definition that, we will directly prove that:

lim f(x) - g(x) = M - N



First let us recall the e-d definition:

For all e > 0, there exists d > 0 where if 0 < |x-c| < d, then |f(x) - L| < e.



Suppose 0 < |x-a| < delta. Let us first analyse the distance from the function and its limit point:

|(f(x) - g(x)) - (M - N)|

= |f(x) - g(x) - M + N|

= |f(x) - M - g(x) + N|

= |(f(x) - M) + (-g(x) + N)|

= |(f(x) - M) - (g(x) - N)|



Then using the reverse inequality to estimate (f(x) - M) and (g(x) - N):

|(f(x) - M) - (g(x) - N)| <= |f(x) - M| + |g(x) - N| < e



Since the whole is below epsilon, and the sum of its two parts is below epsilon. We can estimate each of their values by saying they're below e/2:

|f(x) - M| < e/2

|g(x) - N| < e/2

So let delta1 = e/2 and delta2 = e/2.



Now choose delta = e/2.

|(f(x) - g(x)) - (M - N)|

= |(f(x) - M) - (g(x) - N)|

< e/2 + e/2 = e



Hence, for every e > 0, there exists a delta > 0 where if 0 < |x-c| < d, then |f(x) - L| < e. Thus, we can conclude:

lim f(x) - g(x) = M - N

