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
| whyando | input-lanjian | 414.5 ± 245.8 | 0.0 | 890.9 | 1.00 |
| whyando | input-whyando | 535.2 ± 154.3 | 0.0 | 1171.2 | 1.29 ± 0.85 |
| whyando | input-mattcl | 537.8 ± 190.8 | 0.0 | 1268.1 | 1.30 ± 0.90 |
| mattcl | input-mattcl | 560.2 ± 141.9 | 0.0 | 960.7 | 1.35 ± 0.87 |
| mattcl | input-whyando | 567.1 ± 133.3 | 73.5 | 1039.7 | 1.37 ± 0.87 |
| mattcl | input-lanjian | 580.2 ± 130.2 | 95.8 | 1064.7 | 1.40 ± 0.89 |
| kcen | input-mattcl | 845.4 ± 135.5 | 332.2 | 1313.5 | 2.04 ± 1.25 |
| kcen | input-whyando | 857.3 ± 143.3 | 152.4 | 1287.3 | 2.07 ± 1.27 |
| kcen | input-lanjian | 860.7 ± 145.4 | 312.4 | 1366.5 | 2.08 ± 1.28 |
| lanjian | input-mattcl | 870.1 ± 143.3 | 391.6 | 1429.9 | 2.10 ± 1.29 |
| lanjian | input-lanjian | 888.0 ± 157.3 | 382.4 | 1437.9 | 2.14 ± 1.33 |
| lanjian | input-whyando | 964.3 ± 196.8 | 289.1 | 1851.1 | 2.33 ± 1.46 |
| mattcl-py | input-whyando | 18295.1 ± 526.2 | 17222.3 | 21010.4 | 44.14 ± 26.21 |
| mattcl-py | input-lanjian | 18326.2 ± 588.9 | 17006.4 | 21632.2 | 44.21 ± 26.26 |
| mattcl-py | input-mattcl | 18343.9 ± 612.4 | 17339.7 | 21664.4 | 44.26 ± 26.29 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|