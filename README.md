# PandasJ

Pandas (Python Data Analysis Library) for java


```
DataFrame df = new DataFrame({
    "a": {0, 2, -1, 3, 4, ...},
    "b": {5, 8, -2, 8, -1, ...},
    :
    :
});

df.describe()

// Output
//                a          b          c          d          e
// count  10.000000  10.000000  10.000000  10.000000  10.000000
// mean    0.321200  -0.331797  -0.030067   0.298881  -0.002687
// std     0.982764   0.782483   1.318384   0.774907   1.324976
// min    -1.571542  -1.374674  -1.682764  -0.573934  -2.005993
// 25%     0.144444  -0.842716  -0.969695  -0.274428  -1.205816
// 50%     0.399115  -0.626424  -0.130309   0.296615   0.237664
// 75%     0.714873   0.307824   0.365205   0.346391   0.938685
// max     1.742534   1.048565   2.725946   1.858966   1.657750

df.mean()

// Output
//                a          b          c          d          e
// mean    0.321200  -0.331797  -0.030067   0.298881  -0.002687
```
