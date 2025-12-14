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
| whyando | input-whyando | 418.3 ± 180.0 | 0.0 | 1054.3 | 1.00 |
| whyando | input-lanjian | 433.4 ± 145.1 | 0.0 | 982.3 | 1.04 ± 0.56 |
| whyando | input-mattcl | 438.8 ± 158.2 | 0.0 | 954.8 | 1.05 ± 0.59 |
| mattcl | input-whyando | 618.7 ± 164.0 | 0.0 | 1217.6 | 1.48 ± 0.75 |
| mattcl | input-lanjian | 632.2 ± 144.0 | 0.0 | 878.8 | 1.51 ± 0.74 |
| lanjian | input-lanjian | 658.7 ± 147.4 | 96.7 | 1062.8 | 1.57 ± 0.76 |
| mattcl | input-mattcl | 671.4 ± 187.9 | 0.0 | 1401.2 | 1.60 ± 0.82 |
| lanjian | input-whyando | 704.3 ± 165.5 | 193.9 | 1172.9 | 1.68 ± 0.83 |
| lanjian | input-mattcl | 707.2 ± 162.5 | 179.8 | 1162.2 | 1.69 ± 0.82 |
| kcen | input-whyando | 778.8 ± 170.5 | 0.0 | 1227.1 | 1.86 ± 0.90 |
| kcen | input-mattcl | 792.4 ± 148.9 | 166.7 | 1347.2 | 1.89 ± 0.89 |
| kcen | input-lanjian | 860.6 ± 195.4 | 199.1 | 1531.7 | 2.06 ± 1.00 |
| mattcl-py | input-whyando | 20355.8 ± 678.0 | 19543.9 | 23671.1 | 48.66 ± 21.00 |
| mattcl-py | input-lanjian | 20656.7 ± 447.9 | 19530.2 | 22461.2 | 49.38 ± 21.28 |
| mattcl-py | input-mattcl | 20914.0 ± 771.1 | 19543.7 | 24573.1 | 49.99 ± 21.59 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|