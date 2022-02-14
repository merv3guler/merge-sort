# Veri Yapıları ve Algoritmalar

## Merge Sort Projesi

### [16,21,11,8,12,22]

`Soru` Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

```mermaid
graph LR
A((16,21,11)) --- B((8,12,22))
C((16,21)) --- D((11)) ---- E((8,12)) --- F((22))
G((11,16,21)) --- H((8,12,22))
I((8,11,16,21,22))
```

`Soru` Dizinin Big-O gösterimini yazınız.

    O(nlogn)
