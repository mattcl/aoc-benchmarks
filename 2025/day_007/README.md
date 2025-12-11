# Day 7 benchmarks

[link to problem](https://adventofcode.com/2025/day/7)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 7)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-lanjian | 399.1 ± 176.3 | 0.0 | 1053.5 | 1.00 |
| mattcl | input-mattcl | 425.0 ± 193.1 | 0.0 | 1045.1 | 1.06 ± 0.67 |
| whyando | input-whyando | 435.1 ± 157.6 | 0.0 | 1015.1 | 1.09 ± 0.62 |
| whyando | input-mattcl | 438.4 ± 153.5 | 0.0 | 1107.8 | 1.10 ± 0.62 |
| mattcl | input-lanjian | 443.2 ± 170.3 | 0.0 | 1023.5 | 1.11 ± 0.65 |
| mattcl | input-whyando | 457.0 ± 146.0 | 0.0 | 928.6 | 1.14 ± 0.62 |
| lanjian | input-lanjian | 718.6 ± 200.4 | 0.0 | 1215.2 | 1.80 ± 0.94 |
| lanjian | input-mattcl | 739.9 ± 179.7 | 10.7 | 1340.3 | 1.85 ± 0.93 |
| lanjian | input-whyando | 789.4 ± 186.4 | 46.2 | 1493.5 | 1.98 ± 0.99 |
| kcen | input-whyando | 953.3 ± 156.2 | 316.2 | 1513.3 | 2.39 ± 1.13 |
| kcen | input-lanjian | 960.6 ± 153.6 | 484.5 | 1522.9 | 2.41 ± 1.13 |
| kcen | input-mattcl | 979.5 ± 196.8 | 281.4 | 1630.0 | 2.45 ± 1.19 |
| mattcl-py | input-lanjian | 17661.3 ± 675.2 | 16447.1 | 20764.7 | 44.25 ± 19.61 |
| mattcl-py | input-whyando | 17685.9 ± 649.9 | 16401.9 | 20675.8 | 44.31 ± 19.64 |
| mattcl-py | input-mattcl | 17796.3 ± 761.5 | 16735.7 | 21372.4 | 44.59 ± 19.78 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|