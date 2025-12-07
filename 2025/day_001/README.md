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
| whyando | input-lanjian | 461.8 ± 190.3 | 0.0 | 1347.4 | 1.00 |
| whyando | input-whyando | 470.8 ± 186.1 | 0.0 | 1066.6 | 1.02 ± 0.58 |
| mattcl | input-mattcl | 491.3 ± 178.3 | 0.0 | 1220.3 | 1.06 ± 0.58 |
| whyando | input-mattcl | 495.5 ± 223.0 | 0.0 | 1784.7 | 1.07 ± 0.65 |
| mattcl | input-whyando | 523.6 ± 158.2 | 0.0 | 981.5 | 1.13 ± 0.58 |
| mattcl | input-lanjian | 523.9 ± 143.0 | 12.3 | 917.8 | 1.13 ± 0.56 |
| kcen | input-whyando | 849.6 ± 158.2 | 8.8 | 1736.2 | 1.84 ± 0.83 |
| kcen | input-lanjian | 888.5 ± 153.9 | 466.2 | 1559.9 | 1.92 ± 0.86 |
| kcen | input-mattcl | 893.7 ± 146.3 | 397.4 | 1408.2 | 1.94 ± 0.86 |
| lanjian | input-lanjian | 1086.4 ± 230.5 | 97.0 | 1802.9 | 2.35 ± 1.09 |
| lanjian | input-whyando | 1108.4 ± 194.1 | 486.4 | 1765.4 | 2.40 ± 1.07 |
| lanjian | input-mattcl | 1137.6 ± 209.0 | 389.1 | 1977.5 | 2.46 ± 1.11 |
| mattcl-py | input-lanjian | 18220.2 ± 543.1 | 17247.7 | 20733.1 | 39.45 ± 16.29 |
| mattcl-py | input-mattcl | 18294.8 ± 672.3 | 17397.1 | 21888.7 | 39.61 ± 16.38 |
| mattcl-py | input-whyando | 18338.5 ± 786.9 | 17031.7 | 21793.0 | 39.71 ± 16.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|