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
| mattcl | input-mattcl | 451.9 ± 229.1 | 0.0 | 803.4 | 1.00 |
| lanjian | input-mattcl | 482.6 ± 266.8 | 0.0 | 1251.1 | 1.07 ± 0.80 |
| whyando | input-lanjian | 483.0 ± 919.6 | 0.0 | 9987.4 | 1.07 ± 2.11 |
| whyando | input-whyando | 500.9 ± 189.4 | 0.0 | 796.9 | 1.11 ± 0.70 |
| mattcl | input-whyando | 516.5 ± 186.4 | 0.0 | 825.4 | 1.14 ± 0.71 |
| whyando | input-mattcl | 527.0 ± 160.2 | 0.0 | 750.4 | 1.17 ± 0.69 |
| mattcl | input-lanjian | 534.4 ± 194.2 | 0.0 | 779.9 | 1.18 ± 0.74 |
| lanjian | input-whyando | 840.0 ± 222.5 | 0.0 | 1798.4 | 1.86 ± 1.06 |
| kcen | input-whyando | 842.0 ± 154.9 | 0.0 | 1033.6 | 1.86 ± 1.00 |
| kcen | input-lanjian | 863.5 ± 168.7 | 93.8 | 1031.6 | 1.91 ± 1.04 |
| lanjian | input-lanjian | 919.3 ± 131.7 | 419.9 | 1131.4 | 2.03 ± 1.07 |
| kcen | input-mattcl | 1780.3 ± 3470.0 | 0.0 | 18385.3 | 3.94 ± 7.93 |
| mattcl-py | input-lanjian | 18839.9 ± 482.5 | 17702.4 | 21229.2 | 41.69 ± 21.16 |
| mattcl-py | input-whyando | 19119.0 ± 779.9 | 17450.9 | 24336.5 | 42.30 ± 21.51 |
| mattcl-py | input-mattcl | 19409.1 ± 407.2 | 18494.7 | 21793.4 | 42.95 ± 21.79 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|