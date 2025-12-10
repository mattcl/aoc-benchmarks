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
| whyando | input-whyando | 380.2 ± 166.7 | 0.0 | 943.8 | 1.00 |
| whyando | input-mattcl | 407.4 ± 162.3 | 0.0 | 982.1 | 1.07 ± 0.63 |
| whyando | input-lanjian | 413.3 ± 143.2 | 0.0 | 915.1 | 1.09 ± 0.61 |
| mattcl | input-whyando | 602.5 ± 150.2 | 0.0 | 1088.9 | 1.58 ± 0.80 |
| lanjian | input-whyando | 622.2 ± 161.0 | 0.0 | 1070.1 | 1.64 ± 0.83 |
| mattcl | input-mattcl | 625.8 ± 168.0 | 0.0 | 1246.3 | 1.65 ± 0.85 |
| mattcl | input-lanjian | 630.3 ± 227.9 | 0.0 | 2810.2 | 1.66 ± 0.94 |
| lanjian | input-lanjian | 656.7 ± 137.6 | 0.0 | 1149.8 | 1.73 ± 0.84 |
| lanjian | input-mattcl | 663.7 ± 143.6 | 0.0 | 1213.1 | 1.75 ± 0.85 |
| kcen | input-lanjian | 751.5 ± 173.6 | 0.0 | 1381.0 | 1.98 ± 0.98 |
| kcen | input-mattcl | 758.2 ± 137.6 | 0.0 | 1300.5 | 1.99 ± 0.95 |
| kcen | input-whyando | 784.9 ± 146.9 | 0.0 | 1297.0 | 2.06 ± 0.98 |
| mattcl-py | input-whyando | 20464.3 ± 628.0 | 19464.5 | 23925.3 | 53.83 ± 23.66 |
| mattcl-py | input-mattcl | 20672.6 ± 722.8 | 19506.3 | 23532.9 | 54.37 ± 23.92 |
| mattcl-py | input-lanjian | 20728.5 ± 765.2 | 19708.0 | 23667.6 | 54.52 ± 23.99 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|