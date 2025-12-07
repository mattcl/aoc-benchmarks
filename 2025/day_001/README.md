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
| whyando | input-mattcl | 478.3 ± 198.4 | 0.0 | 1284.2 | 1.00 |
| mattcl | input-lanjian | 481.4 ± 192.6 | 0.0 | 1007.4 | 1.01 ± 0.58 |
| whyando | input-lanjian | 492.4 ± 171.6 | 0.0 | 880.9 | 1.03 ± 0.56 |
| whyando | input-whyando | 511.5 ± 123.8 | 0.0 | 903.2 | 1.07 ± 0.51 |
| mattcl | input-mattcl | 516.7 ± 152.9 | 0.0 | 906.2 | 1.08 ± 0.55 |
| mattcl | input-whyando | 527.2 ± 138.6 | 6.1 | 989.7 | 1.10 ± 0.54 |
| kcen | input-whyando | 829.5 ± 151.5 | 0.0 | 1303.4 | 1.73 ± 0.79 |
| kcen | input-mattcl | 834.2 ± 151.5 | 252.4 | 1361.4 | 1.74 ± 0.79 |
| kcen | input-lanjian | 839.4 ± 164.5 | 143.8 | 1344.3 | 1.75 ± 0.81 |
| lanjian | input-whyando | 1129.8 ± 175.3 | 675.1 | 1805.2 | 2.36 ± 1.05 |
| lanjian | input-mattcl | 1143.2 ± 210.1 | 468.4 | 1921.5 | 2.39 ± 1.08 |
| lanjian | input-lanjian | 1160.8 ± 236.2 | 139.2 | 1936.4 | 2.43 ± 1.12 |
| mattcl-py | input-mattcl | 18242.2 ± 627.5 | 17250.7 | 21894.4 | 38.14 ± 15.88 |
| mattcl-py | input-lanjian | 18258.9 ± 459.6 | 17201.9 | 20949.2 | 38.17 ± 15.86 |
| mattcl-py | input-whyando | 18333.7 ± 628.5 | 17218.3 | 21340.3 | 38.33 ± 15.95 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|