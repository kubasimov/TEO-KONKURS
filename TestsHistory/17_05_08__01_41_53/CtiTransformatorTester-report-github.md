``` ini

BenchmarkDotNet=v0.10.5, OS=Windows 10.0.15063
Processor=Intel Core i7-4710MQ CPU 2.50GHz (Haswell), ProcessorCount=8
Frequency=2435773 Hz, Resolution=410.5473 ns, Timer=TSC
  [Host]            : Clr 4.0.30319.42000, 32bit LegacyJIT-v4.7.2046.0
  LegacyJit-Clr-X86 : Clr 4.0.30319.42000, 32bit LegacyJIT-v4.7.2046.0

Job=LegacyJit-Clr-X86  Jit=LegacyJit  Platform=X86  
Runtime=Clr  

```
 |                    Method |      Mean |     Error |    StdDev | Scaled |     Gen 0 | Allocated |
 |-------------------------- |----------:|----------:|----------:|-------:|----------:|----------:|
 |  Test_v_0_1_transformator | 37.493 ms | 0.1812 ms | 0.1695 ms |   1.00 | 4908.3333 |  16.31 MB |
 |  Test_v_0_2_transformator | 11.477 ms | 0.0319 ms | 0.0298 ms |   0.31 | 2421.8750 |   7.69 MB |
 |  Test_v_0_3_transformator |  9.740 ms | 0.0383 ms | 0.0358 ms |   0.26 | 1835.4167 |   5.91 MB |
 |  Test_v_0_4_transformator |  9.717 ms | 0.0351 ms | 0.0328 ms |   0.26 | 1827.0833 |   5.91 MB |
 |  Test_v_0_5_transformator |  5.558 ms | 0.0256 ms | 0.0240 ms |   0.15 | 1543.7500 |   4.88 MB |
 |  Test_v_0_6_transformator |  5.172 ms | 0.0154 ms | 0.0144 ms |   0.14 | 2027.0833 |   6.29 MB |
 |  Test_v_0_7_transformator |  3.787 ms | 0.0087 ms | 0.0081 ms |   0.10 | 1988.5417 |    6.1 MB |
 |  Test_v_0_8_transformator |  3.293 ms | 0.0156 ms | 0.0146 ms |   0.09 | 1401.8229 |   4.33 MB |
 |  Test_v_0_9_transformator |  2.462 ms | 0.0098 ms | 0.0091 ms |   0.07 | 1400.7813 |   4.33 MB |
 | Test_v_0_10_transformator |  2.432 ms | 0.0112 ms | 0.0100 ms |   0.06 | 1401.8229 |   4.33 MB |
 | Test_v_0_11_transformator |  2.433 ms | 0.0075 ms | 0.0071 ms |   0.06 | 1408.0729 |   4.33 MB |
 | Test_v_0_12_transformator |  2.565 ms | 0.0119 ms | 0.0111 ms |   0.07 | 1521.8750 |   4.69 MB |
 |  Test_v_1_1_transformator |  2.398 ms | 0.0137 ms | 0.0128 ms |   0.06 | 1401.8229 |   4.33 MB |
 |  Test_v_1_2_transformator |  2.422 ms | 0.0101 ms | 0.0094 ms |   0.06 | 1401.8229 |   4.33 MB |
 |  Test_v_2_0_transformator |  2.953 ms | 0.0142 ms | 0.0133 ms |   0.08 | 1404.9479 |   4.33 MB |
 |  Test_v_3_0_transformator |  3.422 ms | 0.0115 ms | 0.0096 ms |   0.09 | 1106.7708 |   3.46 MB |
 |  Test_v_4_0_transformator |  5.013 ms | 0.0158 ms | 0.0132 ms |   0.13 |  943.2292 |   3.04 MB |
 |  Test_v_4_1_transformator |  5.244 ms | 0.0182 ms | 0.0161 ms |   0.14 |  934.8958 |   3.04 MB |
 |  Test_v_4_2_transformator |  3.928 ms | 0.0170 ms | 0.0159 ms |   0.10 |  704.1667 |   2.35 MB |
