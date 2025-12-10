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
| whyando | input-lanjian | 438.2 ± 166.4 | 0.0 | 1030.6 | 1.00 |
| whyando | input-whyando | 438.6 ± 154.7 | 0.0 | 958.0 | 1.00 ± 0.52 |
| whyando | input-mattcl | 440.5 ± 162.9 | 0.0 | 983.4 | 1.01 ± 0.53 |
| mattcl | input-whyando | 649.3 ± 156.1 | 0.0 | 1017.4 | 1.48 ± 0.67 |
| mattcl | input-mattcl | 655.4 ± 154.2 | 129.3 | 1053.3 | 1.50 ± 0.67 |
| lanjian | input-mattcl | 666.5 ± 153.8 | 137.7 | 1102.5 | 1.52 ± 0.68 |
| lanjian | input-lanjian | 667.6 ± 146.4 | 0.0 | 1296.9 | 1.52 ± 0.67 |
| lanjian | input-whyando | 684.6 ± 167.4 | 0.0 | 1331.2 | 1.56 ± 0.71 |
| mattcl | input-lanjian | 695.2 ± 175.9 | 62.6 | 1353.3 | 1.59 ± 0.72 |
| kcen | input-lanjian | 780.9 ± 165.1 | 195.6 | 1442.9 | 1.78 ± 0.77 |
| kcen | input-whyando | 805.0 ± 192.5 | 0.0 | 1409.1 | 1.84 ± 0.82 |
| kcen | input-mattcl | 874.0 ± 164.8 | 362.9 | 1729.9 | 1.99 ± 0.85 |
| mattcl-py | input-whyando | 20577.7 ± 750.8 | 19234.3 | 23201.7 | 46.96 ± 17.92 |
| mattcl-py | input-lanjian | 20721.7 ± 706.0 | 19413.8 | 24139.8 | 47.29 ± 18.03 |
| mattcl-py | input-mattcl | 20726.5 ± 731.0 | 19731.9 | 24228.7 | 47.30 ± 18.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|