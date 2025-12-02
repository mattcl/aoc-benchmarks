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
| whyando | input-lanjian | 642.9 ± 174.5 | 0.0 | 1158.8 | 1.00 |
| whyando | input-mattcl | 678.5 ± 205.3 | 0.0 | 1314.5 | 1.06 ± 0.43 |
| whyando | input-whyando | 684.7 ± 161.1 | 0.0 | 1165.5 | 1.06 ± 0.38 |
| kcen | input-whyando | 820.7 ± 190.9 | 0.0 | 1608.0 | 1.28 ± 0.46 |
| kcen | input-mattcl | 866.9 ± 183.8 | 0.0 | 1466.7 | 1.35 ± 0.46 |
| kcen | input-lanjian | 893.4 ± 171.5 | 257.1 | 1549.7 | 1.39 ± 0.46 |
| mattcl | input-whyando | 1151.3 ± 228.2 | 452.8 | 2093.8 | 1.79 ± 0.60 |
| mattcl | input-mattcl | 1216.0 ± 202.6 | 621.4 | 1931.4 | 1.89 ± 0.60 |
| mattcl | input-lanjian | 1223.1 ± 204.0 | 631.7 | 1904.6 | 1.90 ± 0.61 |
| lanjian | input-whyando | 1277.3 ± 196.6 | 623.3 | 1987.0 | 1.99 ± 0.62 |
| lanjian | input-mattcl | 1292.3 ± 210.7 | 649.4 | 1979.2 | 2.01 ± 0.64 |
| lanjian | input-lanjian | 1335.3 ± 206.6 | 398.1 | 2076.6 | 2.08 ± 0.65 |
| mattcl-py | input-whyando | 18262.8 ± 622.1 | 17285.5 | 21331.9 | 28.41 ± 7.77 |
| mattcl-py | input-mattcl | 18279.5 ± 588.0 | 17178.6 | 21058.7 | 28.43 ± 7.77 |
| mattcl-py | input-lanjian | 18287.7 ± 692.5 | 17305.4 | 21586.4 | 28.44 ± 7.79 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|