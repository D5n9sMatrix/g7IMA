# welcome g7 IMA

Proof. Write T = det
and proceed by induction on k where A is k × k. If k = 1, it is the cofactor 0 B
expansion along column 1. In general let Si (T ) denote the matrix obtained from T by deleting row i and
column 1. Then the cofactor expansion of det T along the first column is
det T = a11 det (S1 (T )) − a21 det (S2 (T )) + · · · ± ak1 det (Sk (T ))
(3.2)
Si (A) Xi
where a11 , a21 , · · · , ak1 are the entries in the first column of A. But Si (T ) =
for each
0
B
i = 1, 2, · · · , k, so det (Si (T )) = det (Si (A)) · det B by induction. Hence, Equation 3.2 becomes
det T = {a11 det (S1 (T )) − a21 det (S2 (T )) + · · · ± ak1 det (Sk (T ))} det B
= { det A} det B
as required. The lower triangular case is similar
