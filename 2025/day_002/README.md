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
| whyando | input-whyando | 228.9 ± 235.5 | 0.0 | 782.8 | 1.00 |
| whyando | input-lanjian | 552.5 ± 146.2 | 0.0 | 994.8 | 2.41 ± 2.56 |
| whyando | input-mattcl | 565.4 ± 145.3 | 0.0 | 1037.2 | 2.47 ± 2.62 |
| kcen | input-whyando | 801.4 ± 136.4 | 330.9 | 1256.7 | 3.50 ± 3.65 |
| mattcl | input-whyando | 815.8 ± 308.2 | 0.0 | 1617.9 | 3.56 ± 3.91 |
| kcen | input-lanjian | 828.5 ± 120.5 | 410.4 | 1403.8 | 3.62 ± 3.76 |
| kcen | input-mattcl | 838.2 ± 170.1 | 288.5 | 1515.9 | 3.66 ± 3.84 |
| mattcl | input-mattcl | 962.1 ± 154.0 | 232.3 | 1501.8 | 4.20 ± 4.38 |
| mattcl | input-lanjian | 962.9 ± 148.2 | 10.5 | 1461.7 | 4.21 ± 4.38 |
| lanjian | input-whyando | 1057.1 ± 194.4 | 462.4 | 1780.6 | 4.62 ± 4.83 |
| lanjian | input-lanjian | 1062.3 ± 159.0 | 543.0 | 1750.2 | 4.64 ± 4.82 |
| lanjian | input-mattcl | 1129.3 ± 205.7 | 574.2 | 2452.6 | 4.93 ± 5.15 |
| mattcl-py | input-lanjian | 20512.5 ± 474.0 | 19519.8 | 22533.3 | 89.61 ± 92.20 |
| mattcl-py | input-whyando | 20551.4 ± 777.2 | 19475.8 | 26043.5 | 89.78 ± 92.42 |
| mattcl-py | input-mattcl | 20581.3 ± 610.2 | 19352.7 | 23725.4 | 89.91 ± 92.53 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|