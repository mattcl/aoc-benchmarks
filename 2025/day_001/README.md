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
| whyando | input-mattcl | 633.8 ± 153.3 | 17.3 | 1131.2 | 1.00 |
| whyando | input-lanjian | 637.8 ± 141.5 | 6.3 | 1107.2 | 1.01 ± 0.33 |
| whyando | input-whyando | 683.3 ± 188.8 | 0.0 | 1437.4 | 1.08 ± 0.40 |
| kcen | input-whyando | 815.3 ± 185.7 | 158.1 | 1384.3 | 1.29 ± 0.43 |
| kcen | input-mattcl | 840.8 ± 171.9 | 0.0 | 1588.0 | 1.33 ± 0.42 |
| kcen | input-lanjian | 866.7 ± 125.8 | 300.8 | 1495.8 | 1.37 ± 0.39 |
| mattcl | input-whyando | 934.0 ± 268.1 | 0.0 | 1597.4 | 1.47 ± 0.55 |
| mattcl | input-lanjian | 1051.3 ± 188.0 | 498.3 | 1778.6 | 1.66 ± 0.50 |
| mattcl | input-mattcl | 1085.0 ± 187.4 | 561.9 | 1806.3 | 1.71 ± 0.51 |
| lanjian | input-whyando | 1342.7 ± 197.5 | 446.1 | 2062.9 | 2.12 ± 0.60 |
| lanjian | input-mattcl | 1346.7 ± 181.4 | 619.0 | 2133.4 | 2.12 ± 0.59 |
| lanjian | input-lanjian | 1364.7 ± 214.1 | 702.5 | 2635.4 | 2.15 ± 0.62 |
| mattcl-py | input-lanjian | 18202.8 ± 635.3 | 17160.6 | 21600.7 | 28.72 ± 7.02 |
| mattcl-py | input-whyando | 18231.1 ± 609.6 | 16998.6 | 21747.8 | 28.77 ± 7.02 |
| mattcl-py | input-mattcl | 18262.8 ± 650.0 | 17248.0 | 21345.4 | 28.82 ± 7.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|