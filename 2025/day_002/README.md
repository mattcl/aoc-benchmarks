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
| whyando | input-whyando | 362.8 ± 173.9 | 0.0 | 911.8 | 1.00 |
| whyando | input-mattcl | 376.0 ± 187.7 | 0.0 | 1032.1 | 1.04 ± 0.72 |
| whyando | input-lanjian | 414.2 ± 185.9 | 0.0 | 1091.2 | 1.14 ± 0.75 |
| mattcl | input-lanjian | 473.2 ± 293.5 | 0.0 | 2995.7 | 1.30 ± 1.02 |
| mattcl | input-whyando | 607.5 ± 182.9 | 0.0 | 1016.6 | 1.67 ± 0.95 |
| mattcl | input-mattcl | 646.0 ± 156.5 | 0.0 | 1010.7 | 1.78 ± 0.96 |
| kcen | input-whyando | 710.7 ± 242.6 | 0.0 | 1399.4 | 1.96 ± 1.15 |
| kcen | input-lanjian | 794.9 ± 178.8 | 0.0 | 1402.9 | 2.19 ± 1.16 |
| lanjian | input-whyando | 832.7 ± 181.1 | 0.0 | 1308.1 | 2.30 ± 1.21 |
| lanjian | input-lanjian | 854.7 ± 181.2 | 310.5 | 1480.1 | 2.36 ± 1.23 |
| kcen | input-mattcl | 872.2 ± 212.0 | 0.0 | 1487.0 | 2.40 ± 1.29 |
| lanjian | input-mattcl | 889.4 ± 171.2 | 259.1 | 1476.7 | 2.45 ± 1.27 |
| mattcl-py | input-whyando | 20727.2 ± 638.9 | 19697.9 | 23051.0 | 57.12 ± 27.44 |
| mattcl-py | input-mattcl | 20784.4 ± 744.4 | 19710.3 | 24082.2 | 57.28 ± 27.53 |
| mattcl-py | input-lanjian | 20784.7 ± 603.3 | 19572.6 | 23778.2 | 57.28 ± 27.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|