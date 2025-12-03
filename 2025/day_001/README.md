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
| whyando | input-mattcl | 634.7 ± 231.1 | 0.0 | 973.9 | 1.00 |
| whyando | input-whyando | 702.8 ± 150.9 | 177.0 | 982.2 | 1.11 ± 0.47 |
| whyando | input-lanjian | 717.8 ± 147.7 | 0.0 | 927.2 | 1.13 ± 0.47 |
| kcen | input-lanjian | 825.6 ± 177.2 | 170.2 | 1063.7 | 1.30 ± 0.55 |
| kcen | input-whyando | 858.9 ± 148.6 | 212.4 | 1104.7 | 1.35 ± 0.55 |
| kcen | input-mattcl | 900.7 ± 133.7 | 156.5 | 1073.5 | 1.42 ± 0.56 |
| mattcl | input-lanjian | 1004.3 ± 185.2 | 313.8 | 1232.5 | 1.58 ± 0.65 |
| mattcl | input-whyando | 1025.1 ± 184.6 | 52.5 | 1276.0 | 1.62 ± 0.66 |
| mattcl | input-mattcl | 1035.6 ± 180.3 | 297.3 | 1327.2 | 1.63 ± 0.66 |
| lanjian | input-whyando | 1301.4 ± 169.8 | 524.7 | 1584.8 | 2.05 ± 0.79 |
| lanjian | input-lanjian | 1317.7 ± 150.6 | 523.7 | 1534.0 | 2.08 ± 0.79 |
| lanjian | input-mattcl | 1336.3 ± 160.5 | 708.6 | 1602.0 | 2.11 ± 0.81 |
| mattcl-py | input-whyando | 18385.6 ± 544.0 | 17317.6 | 20783.4 | 28.97 ± 10.58 |
| mattcl-py | input-lanjian | 19278.7 ± 387.8 | 18401.6 | 20733.7 | 30.38 ± 11.08 |
| mattcl-py | input-mattcl | 19395.9 ± 444.8 | 18436.9 | 21616.0 | 30.56 ± 11.15 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|