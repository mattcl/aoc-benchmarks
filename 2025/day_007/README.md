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
| mattcl | input-whyando | 412.8 ± 197.0 | 0.0 | 913.9 | 1.00 |
| mattcl | input-lanjian | 429.0 ± 178.0 | 0.0 | 942.1 | 1.04 ± 0.66 |
| whyando | input-lanjian | 436.6 ± 176.5 | 0.0 | 1146.4 | 1.06 ± 0.66 |
| whyando | input-whyando | 440.8 ± 180.9 | 0.0 | 1127.3 | 1.07 ± 0.67 |
| whyando | input-mattcl | 452.5 ± 165.1 | 0.0 | 1021.5 | 1.10 ± 0.66 |
| mattcl | input-mattcl | 470.6 ± 163.8 | 0.0 | 976.9 | 1.14 ± 0.67 |
| lanjian | input-lanjian | 719.2 ± 189.0 | 0.6 | 1422.2 | 1.74 ± 0.95 |
| lanjian | input-whyando | 745.2 ± 179.7 | 0.0 | 1343.7 | 1.81 ± 0.97 |
| lanjian | input-mattcl | 766.2 ± 140.5 | 280.4 | 1261.1 | 1.86 ± 0.95 |
| kcen | input-lanjian | 896.6 ± 160.1 | 293.0 | 1451.7 | 2.17 ± 1.11 |
| kcen | input-whyando | 917.8 ± 133.0 | 362.4 | 1381.8 | 2.22 ± 1.11 |
| kcen | input-mattcl | 932.9 ± 129.1 | 452.2 | 1525.6 | 2.26 ± 1.12 |
| mattcl-py | input-lanjian | 17540.6 ± 577.7 | 16332.1 | 20597.3 | 42.49 ± 20.33 |
| mattcl-py | input-mattcl | 17607.7 ± 585.6 | 16471.2 | 20381.6 | 42.65 ± 20.41 |
| mattcl-py | input-whyando | 17612.7 ± 670.3 | 16183.8 | 21056.3 | 42.67 ± 20.43 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|