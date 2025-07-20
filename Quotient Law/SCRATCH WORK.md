Claim: lim \[ f(x) / g(x) ] = M / N



We will prove using the e-d definition that:

lim \[ f(x) / g(x) ] = L/M



First let us recall the e-d definition:

For all e > 0, there exists d > 0 where if 0 < |x-c| < d, then |f(x) - L| < e.



Suppose 0 < |x-a| < delta. Let us first analyse the distance from the function and its limit point:

|f(x)/g(x) - M/N|

= |f(x)N - g(x)M| / |g(x)N|

= |f(x)N - f(x)M + f(x)M - g(x)M| / |g(x)N|

= |f(x)(N - M) + M(f(x) - g(x)| / |g(x)N|

= |f(x)||(N - M)| + |M||(f(x) - g(x)| / |g(x)N|



Then, we bound |g(x)| on the denominator to be sufficiently big but stay positive.

|g(x)| < |N|^2/2

|g(x)||N| < |N|/2

=>

1/|g(x)||N| < 2/|N|

So let delta1 = 2/|N|



Since we know the whole must be below epsilon. Let each part be the quotient of e/2 and the denominator 2/|N| so the sum of both is epsilon. So lets analyse when they're below e|N|/4

|f(x)||(N - M)| < e|N|/4

|M||(f(x) - g(x)| < e|N|/4



We can start with the easy enough to analyse |M||(f(x) - g(x)| because of the constant:

|M||(f(x) - g(x)| < e|N|/4

|(f(x) - g(x)| < e|N|/|M|4

So let delta2 = e|N|/|M|4



Now bound |f(x)| since its not a constant, making it sufficiently big. Let us use the reverse triangle inequality:

|f(x)| - |L| <= |f(x) - L| < 1

|f(x)| < 1 + |L|

So let delta3 = 1 + |L|



Then using that bound:

|f(x)||(N - M)| < e|N|/4

|(N - M)| < e|N|/(1 + |L|)4

So let delta4 = e|N|/(1 + |L|)4



Now choose delta = min (2/|N|, e|N|/|M|4, 1 + |L|, e|N|/(1 + |L|)4), such that:

|f(x)||(N - M)| + |M||(f(x) - g(x)| / |g(x)N|

< \[(1 + |L|) ⋅ e|N|/(1 + |L|)4   +   |M| ⋅  e|N|/|M|4] ⋅ 2|N|

< \[e|N|/4 + e|N|/4] ⋅ 2/|N|

<= e|N|/2 ⋅ 2/|N| = e



Hence, for every e > 0, there exists a delta > 0 where if 0 < |x-c| < d, then |f(x) - L| < e. Thus, we can conclude:

lim \[ f(x) / g(x) ] = L/M

