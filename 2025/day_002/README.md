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
| whyando | input-lanjian | 351.7 ± 169.7 | 0.0 | 1013.5 | 1.00 |
| whyando | input-whyando | 368.1 ± 145.8 | 0.0 | 629.8 | 1.05 ± 0.65 |
| whyando | input-mattcl | 389.9 ± 173.7 | 0.0 | 954.4 | 1.11 ± 0.73 |
| mattcl | input-mattcl | 563.8 ± 190.4 | 0.0 | 1083.9 | 1.60 ± 0.94 |
| lanjian | input-mattcl | 601.1 ± 178.9 | 52.0 | 1058.7 | 1.71 ± 0.97 |
| lanjian | input-lanjian | 616.8 ± 144.5 | 95.9 | 818.9 | 1.75 ± 0.94 |
| mattcl | input-whyando | 617.5 ± 147.4 | 0.0 | 989.0 | 1.76 ± 0.95 |
| mattcl | input-lanjian | 618.7 ± 172.6 | 0.0 | 1193.4 | 1.76 ± 0.98 |
| lanjian | input-whyando | 670.4 ± 134.2 | 138.8 | 1105.3 | 1.91 ± 1.00 |
| kcen | input-mattcl | 749.4 ± 189.7 | 0.0 | 1335.3 | 2.13 ± 1.16 |
| kcen | input-whyando | 773.6 ± 161.5 | 53.1 | 1368.3 | 2.20 ± 1.16 |
| kcen | input-lanjian | 845.4 ± 184.4 | 107.2 | 1445.0 | 2.40 ± 1.27 |
| mattcl-py | input-whyando | 20401.9 ± 723.5 | 18980.5 | 23919.9 | 58.01 ± 28.07 |
| mattcl-py | input-mattcl | 20706.3 ± 703.9 | 19173.8 | 24112.3 | 58.87 ± 28.48 |
| mattcl-py | input-lanjian | 20807.5 ± 795.9 | 19794.3 | 24062.3 | 59.16 ± 28.64 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|