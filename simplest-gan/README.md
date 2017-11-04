### Results:

There's a ton of randomness, but it's approximately converging on the correct values of the distribution.

Thanks to `devnag` for the [tutorial](https://medium.com/@devnag/generative-adversarial-networks-gans-in-50-lines-of-code-pytorch-e81b79659e3f).

```
0: D loss: 0.53/0.69  G loss: 0.71  G μ: 0.00 (real: 3) G σ: 0.16 (real: 2)
500: D loss: 0.11/0.09  G loss: 2.52  G μ: 0.94 (real: 3) G σ: 0.68 (real: 2)
1000: D loss: 2.58/0.71 G loss: 1.98  G μ: 0.98 (real: 3) G σ: 0.84 (real: 2)
1500: D loss: 0.91/0.34 G loss: 1.96  G μ: 3.05 (real: 3) G σ: 1.72 (real: 2)
2000: D loss: 0.07/0.79 G loss: 0.83  G μ: 3.32 (real: 3) G σ: 1.71 (real: 2)
2500: D loss: 0.91/0.35 G loss: 1.90  G μ: 4.60 (real: 3) G σ: 1.75 (real: 2)
3000: D loss: 0.37/0.61 G loss: 1.40  G μ: 2.61 (real: 3) G σ: 1.33 (real: 2)
3500: D loss: 0.29/1.10 G loss: 0.58  G μ: 2.13 (real: 3) G σ: 1.19 (real: 2)
4000: D loss: 2.11/0.85 G loss: 0.63  G μ: 2.67 (real: 3) G σ: 1.11 (real: 2)
4500: D loss: 0.07/0.18 G loss: 1.87  G μ: 2.28 (real: 3) G σ: 1.26 (real: 2)
5000: D loss: 0.76/0.40 G loss: 1.20  G μ: 3.71 (real: 3) G σ: 1.07 (real: 2)
5500: D loss: 0.23/0.01 G loss: 5.00  G μ: 2.27 (real: 3) G σ: 3.82 (real: 2)
6000: D loss: 0.84/0.20 G loss: 2.37  G μ: 6.61 (real: 3) G σ: 2.82 (real: 2)
6500: D loss: 0.62/0.31 G loss: 1.41  G μ: 2.93 (real: 3) G σ: 1.30 (real: 2)
7000: D loss: 1.13/0.90 G loss: 0.67  G μ: 2.62 (real: 3) G σ: 1.24 (real: 2)
7500: D loss: 0.50/0.19 G loss: 2.45  G μ: 3.13 (real: 3) G σ: 1.41 (real: 2)
8000: D loss: 2.20/0.85 G loss: 0.61  G μ: 3.01 (real: 3) G σ: 1.37 (real: 2)
8500: D loss: 0.85/0.38 G loss: 1.52  G μ: 3.15 (real: 3) G σ: 1.36 (real: 2)
9000: D loss: 0.93/0.50 G loss: 1.15  G μ: 3.65 (real: 3) G σ: 1.38 (real: 2)
9500: D loss: 0.28/0.33 G loss: 1.33  G μ: 2.87 (real: 3) G σ: 1.42 (real: 2)
10000: D loss: 4.83/0.49  G loss: 1.23  G μ: 2.32 (real: 3) G σ: 1.87 (real: 2)
10500: D loss: 0.11/0.81  G loss: 0.79  G μ: 2.89 (real: 3) G σ: 1.08 (real: 2)
11000: D loss: 0.59/0.17  G loss: 1.89  G μ: 2.31 (real: 3) G σ: 1.41 (real: 2)
11500: D loss: 0.24/0.22  G loss: 2.02  G μ: 4.05 (real: 3) G σ: 1.84 (real: 2)
12000: D loss: 0.39/0.02  G loss: 5.12  G μ: 4.04 (real: 3) G σ: 1.81 (real: 2)
12500: D loss: 1.44/1.13  G loss: 0.67  G μ: 3.29 (real: 3) G σ: 1.37 (real: 2)
13000: D loss: 0.16/0.33  G loss: 1.60  G μ: 3.46 (real: 3) G σ: 1.63 (real: 2)
13500: D loss: 0.06/0.19  G loss: 2.21  G μ: 3.18 (real: 3) G σ: 1.63 (real: 2)
14000: D loss: 0.70/0.80  G loss: 0.71  G μ: 2.43 (real: 3) G σ: 1.19 (real: 2)
14500: D loss: 1.48/0.18  G loss: 2.64  G μ: 5.03 (real: 3) G σ: 2.59 (real: 2)
15000: D loss: 1.93/1.08  G loss: 4.77  G μ: 4.84 (real: 3) G σ: 2.95 (real: 2)
15500: D loss: 0.36/0.91  G loss: 2.76  G μ: 2.90 (real: 3) G σ: 1.96 (real: 2)
16000: D loss: 3.04/0.42  G loss: 1.62  G μ: 4.00 (real: 3) G σ: 1.87 (real: 2)
16500: D loss: 1.87/0.74  G loss: 0.50  G μ: 2.79 (real: 3) G σ: 1.97 (real: 2)
17000: D loss: 1.16/0.51  G loss: 1.15  G μ: 3.09 (real: 3) G σ: 2.30 (real: 2)
17500: D loss: 0.17/0.25  G loss: 2.88  G μ: 2.99 (real: 3) G σ: 2.08 (real: 2)
18000: D loss: 0.07/0.20  G loss: 3.01  G μ: 2.47 (real: 3) G σ: 2.04 (real: 2)
18500: D loss: 0.18/0.85  G loss: 1.23  G μ: 2.43 (real: 3) G σ: 2.01 (real: 2)
19000: D loss: 0.03/0.46  G loss: 1.29  G μ: 2.50 (real: 3) G σ: 2.08 (real: 2)
19500: D loss: 0.44/0.04  G loss: 3.67  G μ: 2.20 (real: 3) G σ: 1.76 (real: 2)
20000: D loss: 0.02/0.09  G loss: 3.46  G μ: 2.64 (real: 3) G σ: 2.26 (real: 2)
20500: D loss: 0.01/0.25  G loss: 1.63  G μ: 1.03 (real: 3) G σ: 1.91 (real: 2)
21000: D loss: 0.00/0.00  G loss: 7.32  G μ: 2.81 (real: 3) G σ: 4.17 (real: 2)
21500: D loss: 0.30/0.43  G loss: 1.71  G μ: 3.19 (real: 3) G σ: 2.86 (real: 2)
22000: D loss: 0.08/0.18  G loss: 4.18  G μ: 2.50 (real: 3) G σ: 1.70 (real: 2)
22500: D loss: 3.30/0.23  G loss: 1.57  G μ: 2.19 (real: 3) G σ: 1.70 (real: 2)
23000: D loss: 8.86/0.54  G loss: 3.56  G μ: 3.61 (real: 3) G σ: 2.40 (real: 2)
23500: D loss: 0.00/0.60  G loss: 1.02  G μ: 2.38 (real: 3) G σ: 2.02 (real: 2)
24000: D loss: 0.46/0.32  G loss: 2.38  G μ: 4.87 (real: 3) G σ: 3.21 (real: 2)
24500: D loss: 0.01/0.10  G loss: 3.01  G μ: 3.72 (real: 3) G σ: 2.36 (real: 2)
```