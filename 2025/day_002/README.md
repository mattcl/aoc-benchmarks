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
| whyando | input-lanjian | 353.3 ± 173.3 | 0.0 | 934.9 | 1.00 |
| whyando | input-mattcl | 353.7 ± 145.0 | 0.0 | 574.8 | 1.00 ± 0.64 |
| whyando | input-whyando | 366.3 ± 166.5 | 0.0 | 1017.3 | 1.04 ± 0.69 |
| mattcl | input-lanjian | 596.9 ± 151.6 | 0.0 | 1018.1 | 1.69 ± 0.93 |
| mattcl | input-whyando | 622.4 ± 167.0 | 0.0 | 1122.0 | 1.76 ± 0.99 |
| mattcl | input-mattcl | 634.5 ± 152.9 | 0.0 | 1234.9 | 1.80 ± 0.98 |
| kcen | input-mattcl | 750.8 ± 152.3 | 67.2 | 1159.9 | 2.13 ± 1.13 |
| kcen | input-lanjian | 768.5 ± 173.3 | 217.8 | 1321.5 | 2.18 ± 1.17 |
| kcen | input-whyando | 785.8 ± 138.4 | 327.8 | 1200.8 | 2.22 ± 1.16 |
| lanjian | input-lanjian | 1087.7 ± 184.5 | 192.9 | 1772.7 | 3.08 ± 1.60 |
| lanjian | input-whyando | 1095.3 ± 194.5 | 523.8 | 1883.1 | 3.10 ± 1.62 |
| lanjian | input-mattcl | 1183.1 ± 194.9 | 581.4 | 1842.2 | 3.35 ± 1.73 |
| mattcl-py | input-whyando | 20337.1 ± 564.2 | 19068.6 | 23026.5 | 57.56 ± 28.29 |
| mattcl-py | input-mattcl | 20597.5 ± 587.9 | 19510.3 | 23411.6 | 58.30 ± 28.65 |
| mattcl-py | input-lanjian | 20631.2 ± 712.0 | 19634.6 | 23784.0 | 58.40 ± 28.72 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|