Claim: lim \[ f(x) / g(x) ] = lim f(x) / lim g(x)

Proof



We will prove using the e-d definition that:

lim \[ f(x) / g(x) ] = lim f(x) / lim g(x) = L/M





First let us recall the e-d definition:

For all e > 0, there exists d > 0 where if 0 < |x-c| < d, then |f(x) - L| < e.





Since we already know Lim f(x) = L and Lim g(x) = M. Then we know lim f(x) / lim g(x) = L/M, hence:

lim \[ f(x) / g(x) ] = L/M





Then in our case, we must find some delta which satisfies 0 < |x-c| < d such that:

| f(x)/g(x) - L/M | < e




To find a delta which satisfies that, let us re-arrange our equation to be more manageable:

| f(x)/g(x) - L/M | < e

| f(x)M - g(x)L /g(x)M | < e

|f(x)M - g(x)L| / |g(x)M| < e

|f(x)M - f(x)L + f(x)L - g(x)L| / |g(x)M| < e

|f(x)(M - L)| + |L(f(x) - g(x)| / |g(x)M| < e





First, let us bound the denominator from above, ensuring its something positive above 0:

|g(x)||M| > |M|^2/2 

|g(x)| > |M|/2





Second, let us give a upper bound to f(x) since its not a constant. Since I previously stated we know Lim f(x) = L, it follows |f(x) - L| < e. Let that epsilon range be lets say 1, then:

**|f(x) - L| < 1**

**|f(x)| < |L| + 1**




Now let us control the size of the nominator using the triangle inequality:

|f(x)M - g(x)L| <= |f(x)(M - L)| + |L(f(x) - g(x)| < e

|f(x)||(M - L)| + |L||f(x) - g(x)| < e





Such that each piece is a bit below e/2, and to ensure they vibe with the lower bound of the denominator, so let each piece < e|M|^2/4:

1\.

|f(x)||M - L| < e|M|^2/4

(|L| + 1)|M - L| < e|M|^2/4

|M - L| < **e|M|^2/4(|L| + 1)**

2\.

|L||f(x) - g(x)| < e|M|^2/4

|f(x) - g(x)| < **e|M|^2/|L|4**





Let delta = min(e|M|^2/4, e|M|^2/|L|4) such that:

|f(x)M - f(x)L + f(x)L - g(x)L| <= |f(x)(M - L)| + |L(f(x) - g(x)| < e

< \[ (|L| + 1) ⋅ e|M|^2/4(|L| + 1) + |L| ⋅ e|M|^2/|L|4 ] / |M|^2/2 

< \[ e|M|^2/4 + e|M|^2/4 ] ⋅ 1/|M|^2/2 

< \[ e|M|^2/2 ] ⋅ 1/|M|^2/2

< e





Thus, for every e>0, there exists some delta1 and delta2 where 0 < |x - a| < delta therefore | f(x)/g(x) - L/M | < e. Hence, we have proven that the limit of a quotient is the same as the quotient of two limits:

lim \[ f(x) / g(x) ] = lim f(x) / lim g(x)













