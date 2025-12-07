# Day 1 benchmarks

[link to problem](https://adventofcode.com/2025/day/1)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 1)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-whyando | 486.4 ± 168.4 | 0.0 | 1075.5 | 1.00 |
| mattcl | input-whyando | 498.8 ± 183.7 | 0.0 | 1062.5 | 1.03 ± 0.52 |
| whyando | input-mattcl | 529.3 ± 170.6 | 0.0 | 1159.3 | 1.09 ± 0.51 |
| whyando | input-lanjian | 548.3 ± 148.8 | 0.0 | 960.2 | 1.13 ± 0.50 |
| mattcl | input-lanjian | 553.9 ± 143.7 | 0.0 | 1058.8 | 1.14 ± 0.49 |
| mattcl | input-mattcl | 556.5 ± 138.0 | 133.0 | 1140.3 | 1.14 ± 0.49 |
| kcen | input-whyando | 860.4 ± 161.0 | 0.6 | 1356.4 | 1.77 ± 0.70 |
| kcen | input-lanjian | 884.9 ± 159.8 | 319.6 | 1523.5 | 1.82 ± 0.71 |
| kcen | input-mattcl | 954.1 ± 186.1 | 178.8 | 1546.9 | 1.96 ± 0.78 |
| lanjian | input-whyando | 1351.0 ± 202.7 | 574.1 | 2041.8 | 2.78 ± 1.05 |
| lanjian | input-mattcl | 1378.0 ± 175.1 | 292.2 | 1957.4 | 2.83 ± 1.04 |
| lanjian | input-lanjian | 1386.6 ± 183.5 | 585.6 | 2345.0 | 2.85 ± 1.06 |
| mattcl-py | input-whyando | 18259.1 ± 593.0 | 17332.6 | 22174.5 | 37.54 ± 13.05 |
| mattcl-py | input-mattcl | 18259.2 ± 680.6 | 17362.7 | 21277.9 | 37.54 ± 13.07 |
| mattcl-py | input-lanjian | 18363.3 ± 727.7 | 17373.6 | 22006.6 | 37.75 ± 13.16 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|