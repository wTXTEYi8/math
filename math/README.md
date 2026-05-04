# 切り上げ・切り捨てと整数除算

```math
\left\lceil \frac{A}{B} \right\rceil
=
\left\lfloor \frac{A+B-1}{B} \right\rfloor
```

整数Aを整数Bで割ったときの商をq、余りをrと定義する。
```math
A = qB + r \quad (0 \le r \le B-1)
```
切り上げ $\left\lceil \frac{A}{B} \right\rceil$ について、
1. 割り切れる場合 (r = 0のとき)<br>
$frac{A}{B}$ = q なので $\left\lceil A/B \right\rceil$ = q
2. 割り切れない場合 $\quad (1 \le r \le B-1 \text{ のとき})$

# 合同式

a,bを整数，mを正の整数とする。

「a を m で割った余り」と「b を m で割った余り」が等しいことを



\[
a \equiv b \pmod{m}
\]


