# 切り上げ・切り捨てと整数除算

```math
\left\lceil \frac{A}{B} \right\rceil
=
\left\lfloor \frac{A+B-1}{B} \right\rfloor
　　　(1)
```

整数Aを整数Bで割ったときの商をq、余りをrと定義する。
```math
A = qB + r \quad (0 \le r \le B-1)
　　　(2)
```
(1)の左辺について、
1. 割り切れる場合 (r = 0のとき)<br>
$\frac{A}{B} = q$ なので $\left\lceil \frac{A}{B} \right\rceil$

2. 割り切れない場合 $\quad (1 \le r \le B-1 \text{ のとき})$<br>
$\large{\frac{A}{B}}
=
q + \frac{r}{B}$
であり、0 < $\large\frac{r}{B}$ < 1 なので
$\large\left\lceil \frac{A}{B} \right\rceil
=
q + 1$

(1)の右辺に(2)を代入して
```math
\frac{A+B-1}{B}
= 
\frac{qB + r + B - 1}{B}
= 
q + \frac{r + B - 1}{B}
　　　(3)
```

(3)の第二項 $\large\frac{r + B - 1}{B}$ について
1. 割り切れる場合 (r = 0のとき)<br>
$\large\frac{0+B-1}{B} = \large\frac{B-1}{B}$ で商は0<br>
よって $q + 0 = q$

2. 割り切れない場合 $\quad (1 \le r \le B-1 \text{ のとき})$<br>
$r + B - 1$ の取りうる範囲は、
```math
1 + B - 1 \;\le\; r + B - 1 \;\le\; (B - 1) + B - 1
```
```math
B \;\le\; r + B - 1 \;\le\; 2B - 2
```
よって $q + 1$
# 合同式

a,bを整数，mを正の整数とする。

「a を m で割った余り」と「b を m で割った余り」が等しいことを



\[
a \equiv b \pmod{m}
\]


