# C,D が今週のゴミ当番だった場合

## C,D の部屋がどちらも存在していた場合

```
0 A
1 B
2 C
3 D
4 E
5 F
6 G
7 H
8 I
9 J
10 K
11 L
12 M
13 N
14 O
15 P
16 Q
17 L
18 S
19 T
```

-> C,D

## C の部屋が存在し，D の部屋が存在していない場合

```
0 A
1 B
2 C
3
4 E
5 F
6 G
7 H
8 I
9 J
10 K
11 L
12 M
13 N
14 O
15 P
16 Q
17 L
18 S
19 T
```

-> C,E

## D の部屋が存在し，C の部屋が存在していない場合

```
0 A
1 B
2
3 D
4 E
5 F
6 G
7 H
8 I
9 J
10 K
11 L
12 M
13 N
14 O
15 P
16 Q
17 L
18 S
19 T
```

-> D,E

## どちらの部屋も存在していない場合

```
0 A
1 B
2
3
4 E
5 F
6 G
7 H
8 I
9 J
10 K
11 L
12 M
13 N
14 O
15 P
16 Q
17 L
18 S
19 T
```

-> E,F
