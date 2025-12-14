# Day 7 benchmarks

[link to problem](https://adventofcode.com/2025/day/7)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 7)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-lanjian | 391.7 ± 170.3 | 0.0 | 1036.7 | 1.00 |
| whyando | input-mattcl | 413.9 ± 192.6 | 0.0 | 1039.0 | 1.06 ± 0.67 |
| whyando | input-whyando | 419.6 ± 160.9 | 0.0 | 1008.5 | 1.07 ± 0.62 |
| mattcl | input-whyando | 430.3 ± 165.3 | 0.0 | 1038.4 | 1.10 ± 0.64 |
| mattcl | input-lanjian | 434.9 ± 188.5 | 0.0 | 974.8 | 1.11 ± 0.68 |
| mattcl | input-mattcl | 451.1 ± 163.5 | 0.0 | 1017.9 | 1.15 ± 0.65 |
| lanjian | input-whyando | 731.5 ± 164.3 | 0.0 | 1264.3 | 1.87 ± 0.91 |
| lanjian | input-lanjian | 757.3 ± 127.1 | 239.6 | 1147.1 | 1.93 ± 0.90 |
| lanjian | input-mattcl | 777.0 ± 166.5 | 216.2 | 1232.3 | 1.98 ± 0.96 |
| kcen | input-mattcl | 900.8 ± 132.7 | 295.3 | 1477.2 | 2.30 ± 1.06 |
| kcen | input-lanjian | 934.2 ± 150.6 | 234.6 | 1523.5 | 2.38 ± 1.11 |
| kcen | input-whyando | 984.7 ± 171.8 | 363.0 | 1826.5 | 2.51 ± 1.18 |
| mattcl-py | input-mattcl | 17421.8 ± 612.9 | 16386.1 | 20485.6 | 44.48 ± 19.40 |
| mattcl-py | input-whyando | 17545.7 ± 726.0 | 16289.7 | 21135.2 | 44.79 ± 19.56 |
| mattcl-py | input-lanjian | 17551.3 ± 632.5 | 16643.7 | 20739.6 | 44.81 ± 19.55 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|