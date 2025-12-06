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
| mattcl | input-mattcl | 474.3 ± 237.9 | 0.0 | 1195.1 | 1.00 |
| mattcl | input-lanjian | 537.8 ± 190.2 | 0.0 | 1141.8 | 1.13 ± 0.70 |
| whyando | input-whyando | 538.3 ± 168.7 | 0.0 | 923.7 | 1.13 ± 0.67 |
| mattcl | input-whyando | 538.9 ± 194.1 | 0.0 | 1035.0 | 1.14 ± 0.70 |
| whyando | input-mattcl | 551.1 ± 128.2 | 0.0 | 741.1 | 1.16 ± 0.64 |
| whyando | input-lanjian | 556.1 ± 154.6 | 0.0 | 1180.3 | 1.17 ± 0.67 |
| kcen | input-lanjian | 876.9 ± 180.4 | 0.0 | 1355.0 | 1.85 ± 1.00 |
| kcen | input-whyando | 900.0 ± 148.4 | 249.1 | 1478.3 | 1.90 ± 1.00 |
| kcen | input-mattcl | 926.1 ± 176.2 | 125.5 | 1870.2 | 1.95 ± 1.05 |
| lanjian | input-lanjian | 1136.6 ± 218.1 | 548.8 | 2606.6 | 2.40 ± 1.29 |
| lanjian | input-mattcl | 1144.6 ± 211.5 | 188.3 | 1956.6 | 2.41 ± 1.29 |
| lanjian | input-whyando | 1234.0 ± 207.3 | 668.3 | 2428.2 | 2.60 ± 1.38 |
| mattcl-py | input-mattcl | 18341.1 ± 679.7 | 17163.6 | 21354.1 | 38.67 ± 19.45 |
| mattcl-py | input-whyando | 18357.5 ± 776.3 | 17270.2 | 21797.3 | 38.71 ± 19.48 |
| mattcl-py | input-lanjian | 18387.8 ± 729.2 | 17245.3 | 21774.0 | 38.77 ± 19.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|