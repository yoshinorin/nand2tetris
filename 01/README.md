## Mux

```
a * !s + b * s

OR(AND(a, NOT(s)), AND(b, s))
```

## DMux

```
!s * !a * !b = 0
!s *  a * !b = 1
!s * !a *  b = 0
!s *  a *  b = 1

s * !a * !b = 0
s *  a * !b = 0
s * !a *  b = 1
s *  a *  b = 1
```