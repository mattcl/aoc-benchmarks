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
| mattcl | input-mattcl | 314.5 ± 257.5 | 0.0 | 1144.0 | 1.00 |
| whyando | input-mattcl | 468.7 ± 164.5 | 0.0 | 993.6 | 1.49 ± 1.33 |
| whyando | input-whyando | 478.5 ± 183.7 | 0.0 | 978.3 | 1.52 ± 1.38 |
| whyando | input-lanjian | 488.5 ± 157.4 | 0.0 | 873.6 | 1.55 ± 1.37 |
| mattcl | input-whyando | 500.2 ± 168.6 | 0.0 | 1077.2 | 1.59 ± 1.41 |
| mattcl | input-lanjian | 515.3 ± 157.1 | 0.0 | 1296.7 | 1.64 ± 1.43 |
| kcen | input-mattcl | 690.0 ± 296.2 | 0.0 | 1631.1 | 2.19 ± 2.03 |
| kcen | input-lanjian | 811.2 ± 159.7 | 0.0 | 1277.6 | 2.58 ± 2.17 |
| kcen | input-whyando | 829.6 ± 146.5 | 298.1 | 1514.1 | 2.64 ± 2.21 |
| lanjian | input-mattcl | 1071.0 ± 219.2 | 307.7 | 1812.9 | 3.41 ± 2.87 |
| lanjian | input-lanjian | 1114.3 ± 201.3 | 434.4 | 1814.3 | 3.54 ± 2.97 |
| lanjian | input-whyando | 1160.0 ± 228.8 | 533.0 | 2431.8 | 3.69 ± 3.11 |
| mattcl-py | input-lanjian | 18301.0 ± 609.1 | 16988.0 | 21343.2 | 58.19 ± 47.69 |
| mattcl-py | input-whyando | 18305.9 ± 646.0 | 17208.4 | 21330.8 | 58.21 ± 47.71 |
| mattcl-py | input-mattcl | 18429.5 ± 677.7 | 17193.0 | 21597.6 | 58.60 ± 48.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|