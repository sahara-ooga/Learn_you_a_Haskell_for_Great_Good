# 第一章
## 1.1 関数呼び出し

```
ghci> succ succ 8

<interactive>:8:1: error:
    • Non type-variable argument in the constraint: Enum (a -> a)
      (Use FlexibleContexts to permit this)
    • When checking the inferred type
        it :: forall a. (Num a, Enum (a -> a), Enum a) => a
ghci> succ (succ 8)
10
```

`succ succ 8`は通らない。`succ (succ 8)`はOK。