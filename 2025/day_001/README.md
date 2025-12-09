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
| whyando | input-lanjian | 508.4 ± 160.1 | 0.0 | 1091.4 | 1.00 |
| whyando | input-mattcl | 520.6 ± 164.5 | 0.0 | 937.9 | 1.02 ± 0.46 |
| whyando | input-whyando | 521.2 ± 141.3 | 0.0 | 902.1 | 1.03 ± 0.43 |
| mattcl | input-lanjian | 528.8 ± 160.3 | 0.0 | 958.9 | 1.04 ± 0.45 |
| mattcl | input-mattcl | 542.9 ± 168.8 | 0.0 | 1146.3 | 1.07 ± 0.47 |
| mattcl | input-whyando | 565.6 ± 121.3 | 82.1 | 816.8 | 1.11 ± 0.42 |
| kcen | input-lanjian | 847.7 ± 152.8 | 277.9 | 1304.1 | 1.67 ± 0.60 |
| kcen | input-mattcl | 848.7 ± 134.0 | 274.2 | 1425.4 | 1.67 ± 0.59 |
| lanjian | input-whyando | 849.1 ± 159.9 | 43.2 | 1424.5 | 1.67 ± 0.61 |
| kcen | input-whyando | 857.0 ± 153.6 | 246.7 | 1316.0 | 1.69 ± 0.61 |
| lanjian | input-lanjian | 891.4 ± 157.4 | 272.1 | 1547.4 | 1.75 ± 0.63 |
| lanjian | input-mattcl | 895.7 ± 177.6 | 57.1 | 1452.7 | 1.76 ± 0.66 |
| mattcl-py | input-whyando | 18253.5 ± 568.6 | 17127.7 | 21328.9 | 35.90 ± 11.36 |
| mattcl-py | input-mattcl | 18388.2 ± 671.9 | 17276.9 | 21163.3 | 36.17 ± 11.46 |
| mattcl-py | input-lanjian | 18427.6 ± 765.0 | 17259.9 | 21979.9 | 36.24 ± 11.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|