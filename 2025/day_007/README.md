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
| whyando | input-whyando | 407.1 ± 171.9 | 0.0 | 922.1 | 1.00 |
| whyando | input-mattcl | 418.0 ± 149.7 | 0.0 | 638.5 | 1.03 ± 0.57 |
| whyando | input-lanjian | 446.2 ± 180.2 | 0.0 | 1279.3 | 1.10 ± 0.64 |
| mattcl | input-mattcl | 467.9 ± 191.6 | 0.0 | 1212.1 | 1.15 ± 0.68 |
| mattcl | input-whyando | 472.1 ± 163.5 | 0.0 | 1034.4 | 1.16 ± 0.63 |
| mattcl | input-lanjian | 479.3 ± 166.3 | 0.0 | 1050.2 | 1.18 ± 0.64 |
| lanjian | input-lanjian | 739.6 ± 163.3 | 0.0 | 1225.8 | 1.82 ± 0.87 |
| lanjian | input-mattcl | 747.3 ± 151.0 | 0.0 | 1259.3 | 1.84 ± 0.86 |
| lanjian | input-whyando | 786.3 ± 147.0 | 168.7 | 1335.7 | 1.93 ± 0.89 |
| kcen | input-mattcl | 950.2 ± 143.0 | 426.8 | 1630.9 | 2.33 ± 1.05 |
| kcen | input-whyando | 951.7 ± 181.0 | 306.8 | 1630.3 | 2.34 ± 1.08 |
| kcen | input-lanjian | 987.5 ± 188.3 | 363.9 | 1804.3 | 2.43 ± 1.12 |
| mattcl-py | input-lanjian | 17595.3 ± 669.9 | 16412.6 | 21076.2 | 43.22 ± 18.32 |
| mattcl-py | input-mattcl | 17604.0 ± 678.0 | 16384.7 | 20778.0 | 43.24 ± 18.33 |
| mattcl-py | input-whyando | 17796.2 ± 804.5 | 16595.4 | 21286.5 | 43.71 ± 18.56 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|