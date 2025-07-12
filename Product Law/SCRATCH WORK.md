Claim: lim x->a \[f(x) ⋅ g(x)] = M ⋅ N

Proof.



We will prove using the e-d definition that:

lim x->a \[f(x) ⋅ g(x)] = M ⋅ N



First let us recall the e-d definition:

For all e > 0, there exists d > 0 where if 0 < |x-c| < d, then |f(x) - L| < e.



Then let's consider that:

| f(x)g(x) - MN | < e



Then let us re-arrange this into more manageable factors:

| f(x)g(x) - f(x)N + f(x)N - MN | < e

| f(x)(g(x)-N) + N(f(x)-M) | < e

|f(x)||g(x) - N| + |N||f(x) - M| < e



With two distinct factors let us use the triangle inequality:

|f(x)g(x) - MN| <= |f(x)||g(x) - N| + |N||f(x) - M|



Now let

|f(x)||g(x) - N| < e/2

|N||f(x) - M| < e/2



Such that:

|g(x) - N| < e/2|f(x)|

|f(x) - M| < e/2|N|



Then let delta = min(e/2|f(x)| , e/2|N|). Such that:



|f(x)||g(x) - N| < e/2|f(x)| < e|f(x)|/2|f(x)| = e/2

|N||f(x) - M| < e/2|N| < e|N|2/|N| = e/2



Then we have found there exists a delta such that both factors |x-c| are below.

It follows:

| f(x)g(x) - MN | < e/2 + e/2 = e

| f(x)g(x) - MN | < e.



Hence, for every e > 0, there exists a delta > 0 where if 0 < |x-c| < d, then | f(x)g(x) - MN | < e.

Thus, we can conclude: 

lim x->a \[f(x) ⋅ g(x)] = M ⋅ N

