# Exercise 2.5
The expression `x&(x-1)` clears the rightmost non-zero bit of `x`. Write a version of `PopCount` that counts bits by using this fact, and assess its performance.

---
# 練習問題 2.5
式`x&(x-1)`は`x`で1が設定されている最下位ビットをクリアします。この事実を使用してビット数を数える`PopCount`のバージョンを作成し、その性能を評価しなさい。

---

# Result of benchmark test

```sh
BenchmarkPopCount-4       	200000000	         6.62 ns/op
BenchmarkPopCountByClear-4	50000000	        28.1 ns/op
ok  	github.com/budougumi0617/GoTraining/ch02/ex05	3.432s
```
