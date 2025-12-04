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
| whyando | input-lanjian | 498.8 ± 166.3 | 0.0 | 1073.7 | 1.00 |
| whyando | input-whyando | 527.9 ± 161.0 | 0.0 | 1068.8 | 1.06 ± 0.48 |
| whyando | input-mattcl | 541.9 ± 150.9 | 0.0 | 934.9 | 1.09 ± 0.47 |
| kcen | input-whyando | 763.7 ± 141.1 | 215.9 | 1225.4 | 1.53 ± 0.58 |
| kcen | input-mattcl | 769.8 ± 142.8 | 349.7 | 1215.2 | 1.54 ± 0.59 |
| kcen | input-lanjian | 776.7 ± 132.6 | 180.0 | 1233.4 | 1.56 ± 0.58 |
| mattcl | input-whyando | 928.9 ± 139.5 | 409.1 | 1527.3 | 1.86 ± 0.68 |
| mattcl | input-mattcl | 941.1 ± 166.5 | 241.8 | 1616.0 | 1.89 ± 0.71 |
| mattcl | input-lanjian | 955.2 ± 162.1 | 33.7 | 1549.6 | 1.92 ± 0.72 |
| lanjian | input-lanjian | 1027.8 ± 196.5 | 100.1 | 1765.3 | 2.06 ± 0.79 |
| lanjian | input-mattcl | 1063.3 ± 182.8 | 395.1 | 1781.4 | 2.13 ± 0.80 |
| lanjian | input-whyando | 1072.3 ± 192.3 | 467.1 | 1820.7 | 2.15 ± 0.81 |
| mattcl-py | input-whyando | 20193.3 ± 548.0 | 19051.3 | 22855.5 | 40.49 ± 13.54 |
| mattcl-py | input-lanjian | 20564.9 ± 649.6 | 19490.5 | 23561.3 | 41.23 ± 13.81 |
| mattcl-py | input-mattcl | 20650.9 ± 585.2 | 19751.2 | 23960.0 | 41.41 ± 13.85 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|