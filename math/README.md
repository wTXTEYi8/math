# 切り上げ・切り捨てと整数除算

```math
\left\lceil \frac{B}{A} \right\rceil
=
\left\lfloor \frac{B}{A+B-1} \right\rfloor
```
整数Aを整数Bで割ったときの商をq、余りをrと定義する。
```math
A = qB + r \quad (0 \le r \le B-1)
```

# 合同式

a,bを整数，mを正の整数とする。

「a を m で割った余り」と「b を m で割った余り」が等しいことを

```math
a \equiv b \pmod{m}
```
