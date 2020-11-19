# Entropy of the Romanian language
This project is based on [C.Shannon's paper](http://languagelog.ldc.upenn.edu/myl/Shannon1950.pdf)  on the entropy of the English language and does the calculation on an input of 2.2 million words.

# How it works
The program first calculates the frequency of each group of i letters (with i ranging from 1 to 6) using Shannon's formula for H (amount of information).
To get the conditional entropy for n-grams of letters, we use the formula Fn = Hn − Hn-1.

# Values
```
4.144, for i = 1
3.422, for i = 2
2.960, for i = 3
2.440, for i = 4
2.024, for i = 5
1.735, for i = 6
```

# Resources
[Shannon's paper](http://languagelog.ldc.upenn.edu/myl/Shannon1950.pdf)
[Entropy for n-gram](http://normal-extensions.com/2013/08/04/entropy-for-n-grams/)
[Older paper with the entropy of the romanian language](http://dspace.bcu-iasi.ro/static/web/viewer.html?file=http://dspace.bcu-iasi.ro/bitstream/handle/123456789/3388/Novak%2c%20L.%2c%20Experimentul%20de%20predictie%20si%20entropia%20limbii%20romane%2c%20SCL%2c1968%2c%20An%2019%2c%20Nr.3%2c%20p.209-236.pdf?sequence=1&isAllowed=y)

