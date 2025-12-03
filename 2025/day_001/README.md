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
| whyando | input-whyando | 731.0 ± 163.9 | 0.0 | 1272.8 | 1.00 |
| whyando | input-mattcl | 741.6 ± 153.1 | 0.0 | 1188.7 | 1.01 ± 0.31 |
| whyando | input-lanjian | 753.0 ± 158.3 | 189.7 | 1532.0 | 1.03 ± 0.32 |
| kcen | input-whyando | 875.6 ± 165.5 | 61.5 | 1614.8 | 1.20 ± 0.35 |
| kcen | input-mattcl | 883.5 ± 204.8 | 0.0 | 1483.8 | 1.21 ± 0.39 |
| kcen | input-lanjian | 884.5 ± 176.7 | 23.4 | 1750.3 | 1.21 ± 0.36 |
| mattcl | input-mattcl | 1043.7 ± 201.4 | 0.0 | 1811.7 | 1.43 ± 0.42 |
| mattcl | input-whyando | 1057.9 ± 209.1 | 412.6 | 1703.4 | 1.45 ± 0.43 |
| mattcl | input-lanjian | 1063.6 ± 194.6 | 0.0 | 1805.8 | 1.45 ± 0.42 |
| lanjian | input-whyando | 1333.6 ± 197.9 | 691.3 | 2123.4 | 1.82 ± 0.49 |
| lanjian | input-mattcl | 1379.0 ± 211.7 | 637.0 | 2390.0 | 1.89 ± 0.51 |
| lanjian | input-lanjian | 1380.1 ± 231.9 | 425.9 | 2643.8 | 1.89 ± 0.53 |
| mattcl-py | input-whyando | 18258.3 ± 731.0 | 16815.3 | 22091.2 | 24.98 ± 5.69 |
| mattcl-py | input-lanjian | 18268.9 ± 821.3 | 17140.6 | 21995.3 | 24.99 ± 5.72 |
| mattcl-py | input-mattcl | 18281.7 ± 620.9 | 17157.8 | 21577.2 | 25.01 ± 5.67 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|