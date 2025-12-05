# Day 2 benchmarks

[link to problem](https://adventofcode.com/2025/day/2)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 2)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-whyando | 441.7 ± 244.3 | 0.0 | 1007.4 | 1.00 |
| whyando | input-lanjian | 510.7 ± 200.6 | 0.0 | 1103.7 | 1.16 ± 0.78 |
| whyando | input-mattcl | 558.1 ± 186.2 | 0.0 | 1745.1 | 1.26 ± 0.82 |
| kcen | input-whyando | 688.2 ± 262.5 | 0.0 | 1319.2 | 1.56 ± 1.05 |
| kcen | input-mattcl | 788.2 ± 140.3 | 0.0 | 977.0 | 1.78 ± 1.04 |
| kcen | input-lanjian | 892.4 ± 178.0 | 287.8 | 1457.3 | 2.02 ± 1.19 |
| mattcl | input-mattcl | 991.0 ± 186.5 | 373.5 | 1963.7 | 2.24 ± 1.31 |
| mattcl | input-lanjian | 1035.7 ± 171.9 | 143.9 | 1648.9 | 2.35 ± 1.35 |
| mattcl | input-whyando | 1035.8 ± 184.9 | 129.4 | 1759.9 | 2.35 ± 1.36 |
| lanjian | input-whyando | 1155.0 ± 245.1 | 532.6 | 1903.1 | 2.62 ± 1.55 |
| lanjian | input-mattcl | 1188.8 ± 227.7 | 548.6 | 1917.6 | 2.69 ± 1.58 |
| lanjian | input-lanjian | 1224.5 ± 234.3 | 534.4 | 2603.9 | 2.77 ± 1.62 |
| mattcl-py | input-whyando | 20493.1 ± 605.0 | 19570.2 | 23609.4 | 46.40 ± 25.70 |
| mattcl-py | input-mattcl | 20691.3 ± 711.8 | 19330.3 | 24005.3 | 46.85 ± 25.96 |
| mattcl-py | input-lanjian | 20746.6 ± 646.6 | 19615.9 | 23430.1 | 46.97 ± 26.02 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|