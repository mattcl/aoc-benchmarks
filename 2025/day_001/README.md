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
| whyando | input-mattcl | 598.8 ± 166.5 | 0.0 | 1194.0 | 1.00 |
| whyando | input-lanjian | 610.2 ± 153.3 | 46.2 | 1149.6 | 1.02 ± 0.38 |
| whyando | input-whyando | 614.7 ± 158.9 | 0.0 | 1122.7 | 1.03 ± 0.39 |
| kcen | input-whyando | 855.4 ± 138.9 | 303.0 | 1335.2 | 1.43 ± 0.46 |
| kcen | input-lanjian | 864.1 ± 143.2 | 350.4 | 1473.2 | 1.44 ± 0.47 |
| kcen | input-mattcl | 867.3 ± 137.9 | 337.6 | 1405.8 | 1.45 ± 0.46 |
| mattcl | input-mattcl | 1030.7 ± 191.2 | 101.7 | 1748.6 | 1.72 ± 0.58 |
| mattcl | input-whyando | 1059.9 ± 183.9 | 645.2 | 1773.9 | 1.77 ± 0.58 |
| mattcl | input-lanjian | 1115.2 ± 247.0 | 442.2 | 2082.3 | 1.86 ± 0.66 |
| lanjian | input-whyando | 1333.5 ± 184.8 | 572.6 | 1735.8 | 2.23 ± 0.69 |
| lanjian | input-lanjian | 1341.0 ± 194.3 | 677.8 | 2063.7 | 2.24 ± 0.70 |
| lanjian | input-mattcl | 1364.7 ± 176.7 | 707.6 | 2186.6 | 2.28 ± 0.70 |
| mattcl-py | input-whyando | 18288.9 ± 608.6 | 17199.5 | 21667.1 | 30.54 ± 8.55 |
| mattcl-py | input-lanjian | 18359.5 ± 759.4 | 17069.7 | 21955.0 | 30.66 ± 8.62 |
| mattcl-py | input-mattcl | 18389.1 ± 765.2 | 17463.4 | 21772.7 | 30.71 ± 8.63 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|