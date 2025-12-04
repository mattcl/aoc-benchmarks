# Day 3 benchmarks

[link to problem](https://adventofcode.com/2025/day/3)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 3)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-whyando | 668.2 ± 149.8 | 0.0 | 1135.1 | 1.00 |
| whyando | input-lanjian | 668.9 ± 131.7 | 231.3 | 1127.1 | 1.00 ± 0.30 |
| whyando | input-mattcl | 677.8 ± 119.8 | 139.7 | 1013.5 | 1.01 ± 0.29 |
| kcen | input-whyando | 954.5 ± 151.0 | 200.3 | 1474.8 | 1.43 ± 0.39 |
| kcen | input-lanjian | 971.3 ± 166.8 | 380.5 | 1651.4 | 1.45 ± 0.41 |
| kcen | input-mattcl | 998.5 ± 181.8 | 367.7 | 2120.9 | 1.49 ± 0.43 |
| mattcl | input-mattcl | 1035.3 ± 145.5 | 468.5 | 1682.1 | 1.55 ± 0.41 |
| mattcl | input-whyando | 1039.4 ± 154.8 | 24.0 | 1664.7 | 1.56 ± 0.42 |
| mattcl | input-lanjian | 1126.7 ± 232.2 | 388.5 | 2034.7 | 1.69 ± 0.51 |
| lanjian | input-lanjian | 1370.8 ± 305.8 | 834.3 | 2625.3 | 2.05 ± 0.65 |
| lanjian | input-mattcl | 1376.1 ± 304.1 | 827.4 | 2542.0 | 2.06 ± 0.65 |
| lanjian | input-whyando | 1417.3 ± 294.5 | 837.0 | 2471.8 | 2.12 ± 0.65 |
| mattcl-py | input-mattcl | 20819.0 ± 479.7 | 19970.3 | 23149.4 | 31.16 ± 7.02 |
| mattcl-py | input-lanjian | 20906.5 ± 663.5 | 19998.3 | 24249.5 | 31.29 ± 7.09 |
| mattcl-py | input-whyando | 20994.5 ± 603.4 | 19880.4 | 24256.7 | 31.42 ± 7.10 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|