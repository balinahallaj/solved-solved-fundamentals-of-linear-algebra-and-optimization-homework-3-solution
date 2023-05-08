Download Link: https://assignmentchef.com/product/solved-solved-fundamentals-of-linear-algebra-and-optimization-homework-3-solution
<br>
Problem B1 (20 pts). Let U1, . . . , Up be any p ≥ 2 subspaces of some vector space E.Prove that U1 + · · · + Up is a direct sum iffUi ∩Xi−1j=1Uj

= (0), i = 2, . . . , p.Problem B2 (50 pts). Given any vector space E, a linear map f : E → E is an involutionif f ◦ f = id.(1) Prove that an involution f is invertible. What is its inverse?(2) Let E1 and E−1 be the subspaces of E defined as follows:E1 = {u ∈ E | f(u) = u}E−1 = {u ∈ E | f(u) = −u}.Prove that we have a direct sumE = E1 ⊕ E−1.Hint. For every u ∈ E, writeu =u + f(u)2+u − f(u)2.(3) If E is finite-dimensional and f is an involution, prove that there is some basis of Eover which the matrix of f is of the formIk,n−k =

Ik 00 −In−k

,where Ik is the k × k identity matrix (similarly for In−k) and k = dim(E1). Can you give ageometric interpretation of the action of f (especially when k = n − 1)?1Problem B3 (50 pts). A rotation Rθ in the plane R2is given by the matrixRθ =

cos θ − sin θsin θ cos θ

.(1) Use Matlab to show the action of a rotation Rθ on a simple figure such as a triangleor a rectangle, for various values of θ, including θ = π/6, π/4, π/3, π/2.(2) Prove that Rθ is invertible and that its inverse is R−θ.(3) For any two rotations Rα and Rβ, prove thatRβ ◦ Rα = Rα ◦ Rβ = Rα+β.Use (2)-(3) to prove that the rotations in the plane form a commutative group denotedSO(2).Problem B4 (110 pts). Consider the affine map Rθ,(a1,a2)in R2 given by

y1y2

=

cos θ − sin θsin θ cos θx1x2




a1a2

.(1) Prove that if θ 6= k2π, with k ∈ Z, then Rθ,(a1,a2) has a unique fixed point (c1, c2),that is, there is a unique point (c1, c2) such that

c1c2

= Rθ,(a1,a2)

c1c2

,and this fixed point is given by

c1c2

=12 sin(θ/2)cos(π/2 − θ/2) − sin(π/2 − θ/2)sin(π/2 − θ/2) cos(π/2 − θ/2) a1a2

.(2) In this question, we still assume that θ 6= k2π, with k ∈ Z. By translating thecoordinate system with origin (0, 0) to the new coordinate system with origin (c1, c2), whichmeans that if (x1, x2) are the coordinates with respect to the standard origin (0, 0) and if(x01, x02) are the coordinates with respect to the new origin (c1, c2), we havex1 = x01 + c1x2 = x02 + c2and similarly for (y1, y2) and (y01, y02), then show that

y1y2

= Rθ,(a1,a2)

x1x2

2becomes

y01y02

= Rθ

x01x02

.Conclude that with respect to the new origin (c1, c2), the affine map Rθ,(a1,a2) becomesthe rotation Rθ. We say that Rθ,(a1,a2)is a rotation of center (c1, c2).(3) Use Matlab to show the action of the affine map Rθ,(a1,a2) on a simple figure such as atriangle or a rectangle, for θ = π/3 and various values of (a1, a2). Display the center (c1, c2)of the rotation.What kind of transformations correspond to θ = k2π, with k ∈ Z?(4) Prove that the inverse of Rθ,(a1,a2)is of the form R−θ,(b1,b2), and find (b1, b2) in termsof θ and (a1, a2).(5) Given two affine maps Rα,(a1,a2) and Rβ,(b1,b2), prove thatRβ,(b1,b2) ◦ Rα,(a1,a2) = Rα+β,(t1,t2)for some (t1, t2), and find (t1, t2) in terms of β, (a1, a2) and (b1, b2).Even in the case where (a1, a2) = (0, 0), prove that in generalRβ,(b1,b2) ◦ Rα 6= Rα ◦ Rβ,(b1,b2).Use (4)-(5) to show that the affine maps of the plane defined in this problem form anonabelian group denoted SE(2).Prove that Rβ,(b1,b2) ◦Rα,(a1,a2)is not a translation (possibly the identity) iff α+β 6= k2π,for all k ∈ Z. Find its center of rotation when (a1, a2) = (0, 0).If α+β = k2π, then Rβ,(b1,b2) ◦Rα,(a1,a2)is a pure translation. Find the translation vectorof Rβ,(b1,b2) ◦ Rα,(a1,a2).Problem B5 (80 pts). A subset A of Rnis called an affine subspace if either A = ∅, orthere is some vector a ∈ Rn and some subspace U of Rnsuch thatA = a + U = {a + u | u ∈ U}.We define the dimension dim(A) of A as the dimension dim(U) of U.(1) If A = a + U, why is a ∈ A?What are affine subspaces of dimension 0? What are affine subspaces of dimension 1(begin with R2)? What are affine subspaces of dimension 2 (begin with R3)?Prove that any nonempty affine subspace is closed under affine combinations.(2) Prove that if A = a + U is any nonempty affine subspace, then A = b + U for anyb ∈ A.3(3) Let A be any nonempty subset of Rnclosed under affine combinations. For anya ∈ A, prove thatUa = {x − a ∈ Rn| x ∈ A}is a (linear) subspace of Rnsuch thatA = a + Ua.Prove that Ua does not depend on the choice of a ∈ A; that is, Ua = Ub for all a, b ∈ A. Infact, prove thatUa = U = {y − x ∈ Rn| x, y ∈ A}, for all a ∈ A,and soA = a + U, for any a ∈ A.Remark: The subspace U is called the direction of A.(4) Two nonempty affine subspaces A and B are said to be parallel iff they have the samedirection. Prove that that if A 6= B and A and B are parallel, then A ∩ B = ∅.Remark: The above shows that affine subspaces behave quite differently from linear subspaces.Problem B6 (120 pts). (Affine frames and affine maps) For any vector v = (v1, . . . , vn) ∈Rn, let vb ∈ Rn+1 be the vector vb = (v1, . . . , vn, 1). Equivalently, vb = (vb1, . . . , vbn+1) ∈ Rn+1 isthe vector defined byvbi =(viif 1 ≤ i ≤ n,1 if i = n + 1.(1) For any m + 1 vectors (u0, u1, . . . , um) with ui ∈ Rn and m ≤ n, prove that if the mvectors (u1 − u0, . . . , um − u0) are linearly independent, then the m + 1 vectors (ub0, . . . , ubm)are linearly independent.(2) Prove that if the m + 1 vectors (ub0, . . . , ubm) are linearly independent, then for anychoice of i, with 0 ≤ i ≤ m, the m vectors uj − uifor j ∈ {0, . . . , m} with j − i 6= 0 arelinearly independent.Any m + 1 vectors (u0, u1, . . . , um) such that the m + 1 vectors (ub0, . . . , ubm) are linearlyindependent are said to be affinely independent.From (1) and (2), the vector (u0, u1, . . . , um) are affinely independent iff for any any choiceof i, with 0 ≤ i ≤ m, the m vectors uj − uifor j ∈ {0, . . . , m} with j − i 6= 0 are linearlyindependent. If m = n, we say that n + 1 affinely independent vectors (u0, u1, . . . , un) forman affine frame of Rn.4(3) if (u0, u1, . . . , un) is an affine frame of Rn, then prove that for every vector v ∈ Rn,there is a unique (n+ 1)-tuple (λ0, λ1, . . . , λn) ∈ Rn+1, with λ0 +λ1 +· · ·+λn = 1, such thatv = λ0u0 + λ1u1 + · · · + λnun.The scalars (λ0, λ1, . . . , λn) are called the barycentric (or affine) coordinates of v w.r.t. theaffine frame (u0, u1, . . . , un).If we write ei = ui − u0, for i = 1, . . . , n, then prove that we havev = u0 + λ1e1 + · · · + λnen,and since (e1, . . . , en) is a basis of Rn(by (1) &amp; (2)), the n-tuple (λ1, . . . , λn) consists of thestandard coordinates of v − u0 over the basis (e1, . . . , en).Conversely, for any vector u0 ∈ Rn and for any basis (e1, . . . , en) of Rn, let ui = u0 + eifor i = 1, . . . , n. Prove that (u0, u1, . . . , un) is an affine frame of Rn, and for any v ∈ Rn, ifv = u0 + x1e1 + · · · + xnen,with (x1, . . . , xn) ∈ Rn(unique), thenv = (1 − (x1 + · · · + xx))u0 + x1u1 + · · · + xnun,so that (1−(x1 +· · ·+xx)), x1, · · · , xn), are the barycentric coordinates of v w.r.t. the affineframe (u0, u1, . . . , un).The above shows that there is a one-to-one correspondence between affine frames (u0, . . .,un) and pairs (u0,(e1, . . . , en)), with (e1, . . . , en) a basis. Given an affine frame (u0, . . . , un),we obtain the basis (e1, . . . , en) with ei = ui −u0, for i = 1, . . . , n; given the pair (u0,(e1, . . .,en)) where (e1, . . . , en) is a basis, we obtain the affine frame (u0, . . . , un), with ui = u0 + ei,for i = 1, . . . , n. There is also a one-to-one correspondence between barycentric coordinatesw.r.t. the affine frame (u0, . . . , un) and standard coordinates w.r.t. the basis (e1, . . . , en).The barycentric cordinates (λ0, λ1, . . . , λn) of v (with λ0 + λ1 + · · · + λn = 1) yield thestandard coordinates (λ1, . . . , λn) of v − u0; the standard coordinates (x1, . . . , xn) of v − u0yield the barycentric coordinates (1 − (x1 + · · · + xn), x1, . . . , xn) of v.(4) Let (u0, . . . , un) be any affine frame in Rn and let (v0, . . . , vn) be any vectors in Rm.Prove that there is a unique affine map f : Rn → Rm such thatf(ui) = vi, i = 0, . . . , n.(5) Let (a0, . . . , an) be any affine frame in Rn and let (b0, . . . , bn) be any n + 1 points inRn. Prove that the (n + 1) × (n + 1) matrix A corresponding to the unique affine map fsuch thatf(ai) = bi, i = 0, . . . , n,5is given byA =

bb0bb1 · · · bbn

ba0 ba1 · · · ban−1.In the special case where (a0, . . . , an) is the canonical affine frame with ai = ei+1 fori = 0, . . . , n − 1 and an = (0, . . . , 0) (where eiis the ith canonical basis vector), show that

ba0 ba1 · · · ban

=1 0 · · · 0 00 1 · · · 0 0......... 0 00 0 · · · 1 01 1 · · · 1 1and

ba0 ba1 · · · ban−1=1 0 · · · 0 00 1 · · · 0 0......... 0 00 0 · · · 1 0−1 −1 · · · −1 1.For example, when n = 2, if we write bi = (xi, yi), then we haveA =x1 x2 x3y1 y2 y31 1 11 0 00 1 0−1 −1 1 =x1 − x3 x2 − x3 x3y1 − y3 y2 − y3 y30 0 1 .(6) Recall that a nonempty affine subspace A of Rnis any nonempty subset of Rnclosedunder affine combinations. For any affine map f : Rn → Rm, for any affine subspace A ofRn, and any affine subspace B of Rm, prove that f(A) is an affine subspace of Rm, and thatf−1(B) is an affine subspace of Rn.Problem B7 (30 pts). Let A be any n × k matrix(1) Prove that the k × k matrix AA and the matrix A have the same nullspace. Usethis to prove that rank(AA) = rank(A). Similarly, prove that the n × n matrix AA andthe matrix A have the same nullspace, and conclude that rank(AA) = rank(A).We will prove later that rank(A) = rank(A).(2) Let a1, . . . , ak be k linearly independent vectors in Rn(1 ≤ k ≤ n), and let A be then × k matrix whose ith column is ai. Prove that AA has rank k, and that it is invertible.Let P = A(AA)−1A (an n × n matrix). Prove thatP2 = PP= P.What is the matrix P when k = 1?6(3) Prove that the image of P is the subspace V spanned by a1, . . . , ak, or equivalentlythe set of all vectors in Rn of the form Ax, with x ∈ Rk. Prove that the nullspace U of P isthe set of vectors u ∈ Rnsuch that Au = 0. Can you give a geometric interpretation of U?Conclude that P is a projection of Rn onto the subspace V spanned by a1, . . . , ak, andthatRn = U ⊕ V.Hint. You may use results from HW2.TOTAL: 460 points.7