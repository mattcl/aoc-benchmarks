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
| whyando | input-whyando | 483.6 ± 146.2 | 0.0 | 769.2 | 1.00 |
| whyando | input-mattcl | 496.7 ± 142.6 | 0.0 | 788.2 | 1.03 ± 0.43 |
| whyando | input-lanjian | 503.0 ± 172.3 | 0.0 | 1370.1 | 1.04 ± 0.48 |
| mattcl | input-mattcl | 748.1 ± 174.9 | 0.0 | 1378.9 | 1.55 ± 0.59 |
| mattcl | input-lanjian | 752.0 ± 147.0 | 127.8 | 1131.1 | 1.56 ± 0.56 |
| mattcl | input-whyando | 826.5 ± 157.3 | 312.5 | 1423.2 | 1.71 ± 0.61 |
| kcen | input-whyando | 834.0 ± 155.0 | 245.2 | 1336.1 | 1.72 ± 0.61 |
| kcen | input-mattcl | 855.3 ± 147.0 | 377.3 | 1321.0 | 1.77 ± 0.62 |
| kcen | input-lanjian | 905.6 ± 158.1 | 324.2 | 1640.0 | 1.87 ± 0.65 |
| lanjian | input-mattcl | 1063.2 ± 221.1 | 98.2 | 1848.8 | 2.20 ± 0.81 |
| lanjian | input-lanjian | 1105.8 ± 204.2 | 248.0 | 1796.8 | 2.29 ± 0.81 |
| lanjian | input-whyando | 1153.5 ± 204.5 | 323.6 | 1838.5 | 2.39 ± 0.84 |
| mattcl-py | input-mattcl | 18254.4 ± 536.7 | 17264.5 | 20415.4 | 37.75 ± 11.47 |
| mattcl-py | input-lanjian | 18290.7 ± 565.2 | 17269.2 | 21441.5 | 37.82 ± 11.50 |
| mattcl-py | input-whyando | 18353.0 ± 627.4 | 17393.4 | 21516.1 | 37.95 ± 11.55 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|