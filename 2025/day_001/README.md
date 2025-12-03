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
| whyando | input-whyando | 740.8 ± 160.3 | 0.0 | 1244.2 | 1.00 |
| whyando | input-lanjian | 749.2 ± 145.6 | 184.3 | 1152.3 | 1.01 ± 0.29 |
| whyando | input-mattcl | 787.7 ± 148.5 | 309.2 | 1405.1 | 1.06 ± 0.31 |
| kcen | input-whyando | 835.4 ± 177.5 | 120.4 | 1452.8 | 1.13 ± 0.34 |
| kcen | input-mattcl | 855.7 ± 153.0 | 318.1 | 1333.2 | 1.16 ± 0.32 |
| kcen | input-lanjian | 859.9 ± 148.3 | 0.0 | 1379.5 | 1.16 ± 0.32 |
| mattcl | input-mattcl | 1027.4 ± 187.1 | 199.5 | 1645.5 | 1.39 ± 0.39 |
| mattcl | input-whyando | 1035.4 ± 136.5 | 436.2 | 1730.8 | 1.40 ± 0.35 |
| mattcl | input-lanjian | 1075.3 ± 179.2 | 477.6 | 1708.4 | 1.45 ± 0.40 |
| lanjian | input-whyando | 1340.7 ± 211.7 | 709.0 | 2135.8 | 1.81 ± 0.48 |
| lanjian | input-mattcl | 1349.1 ± 233.4 | 285.8 | 2051.1 | 1.82 ± 0.50 |
| lanjian | input-lanjian | 1353.3 ± 226.0 | 486.3 | 2136.7 | 1.83 ± 0.50 |
| mattcl-py | input-whyando | 18119.2 ± 496.6 | 17428.4 | 20964.9 | 24.46 ± 5.33 |
| mattcl-py | input-lanjian | 18168.8 ± 623.2 | 16848.8 | 21520.1 | 24.52 ± 5.37 |
| mattcl-py | input-mattcl | 18349.4 ± 671.1 | 16761.4 | 21561.1 | 24.77 ± 5.44 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|