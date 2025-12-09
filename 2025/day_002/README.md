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
| whyando | input-lanjian | 346.1 ± 159.2 | 0.0 | 583.8 | 1.00 |
| whyando | input-mattcl | 390.7 ± 141.2 | 0.0 | 627.6 | 1.13 ± 0.66 |
| whyando | input-whyando | 395.4 ± 170.2 | 0.0 | 1029.3 | 1.14 ± 0.72 |
| mattcl | input-whyando | 602.6 ± 141.2 | 0.0 | 952.8 | 1.74 ± 0.90 |
| lanjian | input-mattcl | 619.4 ± 168.5 | 0.0 | 1066.2 | 1.79 ± 0.96 |
| lanjian | input-whyando | 646.6 ± 141.6 | 0.0 | 1152.2 | 1.87 ± 0.95 |
| lanjian | input-lanjian | 651.6 ± 191.2 | 0.0 | 1316.4 | 1.88 ± 1.03 |
| mattcl | input-mattcl | 673.1 ± 158.3 | 0.0 | 1525.6 | 1.94 ± 1.00 |
| mattcl | input-lanjian | 680.3 ± 201.0 | 0.0 | 1321.8 | 1.97 ± 1.07 |
| kcen | input-mattcl | 772.0 ± 150.3 | 0.0 | 1373.0 | 2.23 ± 1.11 |
| kcen | input-lanjian | 781.9 ± 170.4 | 28.8 | 1337.4 | 2.26 ± 1.15 |
| kcen | input-whyando | 866.0 ± 182.8 | 342.7 | 1398.7 | 2.50 ± 1.27 |
| mattcl-py | input-whyando | 20381.1 ± 481.5 | 18919.7 | 22687.1 | 58.88 ± 27.12 |
| mattcl-py | input-mattcl | 20681.3 ± 552.8 | 19765.1 | 23030.8 | 59.75 ± 27.53 |
| mattcl-py | input-lanjian | 20695.3 ± 769.8 | 19775.3 | 27117.5 | 59.79 ± 27.59 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|