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
| whyando | input-mattcl | 666.2 ± 173.3 | 0.0 | 1152.2 | 1.00 |
| whyando | input-lanjian | 668.8 ± 162.5 | 58.8 | 1091.7 | 1.00 ± 0.36 |
| whyando | input-whyando | 689.2 ± 176.5 | 0.0 | 1138.4 | 1.03 ± 0.38 |
| kcen | input-whyando | 842.6 ± 142.9 | 318.4 | 1347.3 | 1.26 ± 0.39 |
| kcen | input-mattcl | 890.3 ± 148.2 | 356.2 | 1448.5 | 1.34 ± 0.41 |
| kcen | input-lanjian | 892.3 ± 169.6 | 325.7 | 1432.9 | 1.34 ± 0.43 |
| mattcl | input-mattcl | 1171.9 ± 252.0 | 211.7 | 1913.0 | 1.76 ± 0.59 |
| mattcl | input-whyando | 1205.0 ± 214.9 | 555.1 | 1972.8 | 1.81 ± 0.57 |
| mattcl | input-lanjian | 1232.1 ± 212.2 | 573.1 | 1948.9 | 1.85 ± 0.58 |
| lanjian | input-whyando | 1294.9 ± 220.8 | 613.9 | 2066.0 | 1.94 ± 0.60 |
| lanjian | input-mattcl | 1347.2 ± 192.2 | 609.8 | 2091.8 | 2.02 ± 0.60 |
| lanjian | input-lanjian | 1358.0 ± 221.5 | 764.1 | 2418.5 | 2.04 ± 0.63 |
| mattcl-py | input-mattcl | 18070.5 ± 742.8 | 16810.1 | 21565.2 | 27.12 ± 7.15 |
| mattcl-py | input-whyando | 18158.8 ± 595.4 | 17053.5 | 21538.1 | 27.26 ± 7.15 |
| mattcl-py | input-lanjian | 18178.2 ± 700.5 | 17174.0 | 21242.4 | 27.29 ± 7.18 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|