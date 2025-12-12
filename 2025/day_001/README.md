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
| mattcl | input-mattcl | 529.6 ± 155.7 | 0.0 | 940.0 | 1.00 |
| whyando | input-lanjian | 530.1 ± 155.6 | 0.0 | 1015.0 | 1.00 ± 0.42 |
| mattcl | input-lanjian | 537.8 ± 154.4 | 0.0 | 961.0 | 1.02 ± 0.42 |
| whyando | input-mattcl | 545.0 ± 147.8 | 39.6 | 1071.7 | 1.03 ± 0.41 |
| mattcl | input-whyando | 552.5 ± 179.5 | 0.0 | 1210.8 | 1.04 ± 0.46 |
| whyando | input-whyando | 566.2 ± 129.4 | 34.5 | 948.4 | 1.07 ± 0.40 |
| lanjian | input-mattcl | 844.5 ± 143.2 | 0.0 | 1037.1 | 1.59 ± 0.54 |
| kcen | input-whyando | 854.7 ± 173.2 | 0.0 | 1447.1 | 1.61 ± 0.58 |
| lanjian | input-whyando | 875.5 ± 130.3 | 384.8 | 1329.7 | 1.65 ± 0.54 |
| lanjian | input-lanjian | 882.3 ± 138.0 | 344.4 | 1388.3 | 1.67 ± 0.55 |
| kcen | input-mattcl | 896.1 ± 138.9 | 326.8 | 1453.1 | 1.69 ± 0.56 |
| kcen | input-lanjian | 977.7 ± 187.1 | 280.9 | 1564.1 | 1.85 ± 0.65 |
| mattcl-py | input-whyando | 18286.7 ± 662.9 | 17269.7 | 21845.1 | 34.53 ± 10.23 |
| mattcl-py | input-mattcl | 18318.4 ± 690.4 | 17299.3 | 21632.3 | 34.59 ± 10.26 |
| mattcl-py | input-lanjian | 18340.7 ± 831.1 | 16754.9 | 21854.3 | 34.63 ± 10.30 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|