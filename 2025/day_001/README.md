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
| whyando | input-mattcl | 687.2 ± 174.3 | 0.0 | 1086.6 | 1.00 |
| whyando | input-lanjian | 690.9 ± 165.3 | 0.0 | 1044.8 | 1.01 ± 0.35 |
| whyando | input-whyando | 691.6 ± 179.0 | 0.0 | 1113.9 | 1.01 ± 0.36 |
| kcen | input-lanjian | 790.8 ± 162.9 | 182.9 | 1033.1 | 1.15 ± 0.38 |
| kcen | input-whyando | 829.7 ± 165.8 | 0.0 | 1631.9 | 1.21 ± 0.39 |
| kcen | input-mattcl | 846.7 ± 162.0 | 0.0 | 1597.6 | 1.23 ± 0.39 |
| mattcl | input-whyando | 1007.7 ± 167.9 | 416.7 | 1679.0 | 1.47 ± 0.44 |
| mattcl | input-lanjian | 1010.8 ± 176.9 | 223.7 | 1691.3 | 1.47 ± 0.45 |
| mattcl | input-mattcl | 1068.8 ± 200.0 | 430.6 | 1715.9 | 1.56 ± 0.49 |
| lanjian | input-lanjian | 1308.7 ± 223.8 | 624.1 | 2526.6 | 1.90 ± 0.58 |
| lanjian | input-whyando | 1333.6 ± 215.0 | 486.3 | 2045.4 | 1.94 ± 0.58 |
| lanjian | input-mattcl | 1336.2 ± 201.1 | 684.6 | 2109.4 | 1.94 ± 0.57 |
| mattcl-py | input-whyando | 18195.1 ± 568.8 | 16871.3 | 21080.5 | 26.48 ± 6.77 |
| mattcl-py | input-mattcl | 18195.3 ± 719.4 | 16911.4 | 21130.0 | 26.48 ± 6.80 |
| mattcl-py | input-lanjian | 18224.1 ± 795.9 | 17044.6 | 21604.6 | 26.52 ± 6.82 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|