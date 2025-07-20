Claim: lim x->a \[f(x) ⋅ g(x)] = M ⋅ N

Proof.



We will prove using the e-d definition that:

lim x->a \[f(x) ⋅ g(x)] = M ⋅ N



First let us recall the e-d definition:

For all e > 0, there exists d > 0 where if 0 < |x-c| < d, then |f(x) - L| < e.



Suppose 0 < |x-a| < delta. Let us analyse the distance from the limit point:

| f(x)g(x) - MN |



Then let us re-arrange this into more manageable factors:

| f(x)g(x) - f(x)N + f(x)N - MN |

| f(x)(g(x)-N) + N(f(x)-M) |

|f(x)||g(x) - N| + |N||f(x) - M|



Since we know the sum of both parts must be below epsilon, let us find some delta when each part individually is below e/2:

|f(x)||g(x) - N| < e/2

|N||f(x) - M| < e/2



Then first:

|f(x) - M| < e/2|N|

Let delta1 = e/2|N|



Let us bound |f(x)| since its not a constant. Since we already know |f(x) - M| < e/2|N|, we can use the triangle equality to estimate some bound:

|f(x)| <= |f(x) - M| + |M| < e/2|N| + |M|

|f(x)| < e/2|N| + |M|

Let delta2 = (e + 2|N||M|)/2|N|



Let us control |f(x)||g(x) - N| < e/2 now that we have tamed |f(x)|:

|f(x)||g(x) - N| < e/2

(e + 2|N||M|) ⋅ |g(x) - N| < e2|N|/2

(e + 2|N||M|) ⋅ |g(x) - N| < e|N|

|g(x) - N| < e|N|/(e + 2|N||M|)

Let delta3 = e|N|/(e + 2|N||M|)





Choose delta = min(e/2|N| , (e + 2|N||M|)/2|N| , e|N|/(e + 2|N||M|)), then:

| f(x)g(x) - MN |

|f(x)||g(x) - N| + |N||f(x) - M|

< \[(e + 2|N||M|)/2|N| ⋅ \[e|N|/(e + 2|N||M|)]  + |N| ⋅ e/2|N|

<= e/2 + e/2 = e



Hence, for every e > 0, there exists a delta > 0 where if 0 < |x-c| < d, then |f(x) - L| < e. Thus, we can conclude:

lim x->a \[f(x) ⋅ g(x)] = M ⋅ N

