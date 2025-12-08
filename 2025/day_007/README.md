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
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-mattcl | 366.4 ± 160.3 | 0.0 | 980.1 | 1.00 |
| whyando | input-lanjian | 379.7 ± 151.5 | 0.0 | 581.5 | 1.04 ± 0.61 |
| mattcl | input-lanjian | 397.8 ± 172.2 | 0.0 | 843.4 | 1.09 ± 0.67 |
| whyando | input-whyando | 402.4 ± 166.0 | 0.0 | 1026.0 | 1.10 ± 0.66 |
| mattcl | input-whyando | 430.0 ± 171.8 | 0.0 | 1029.2 | 1.17 ± 0.70 |
| mattcl | input-mattcl | 432.4 ± 181.2 | 0.0 | 1048.6 | 1.18 ± 0.71 |
| kcen | input-lanjian | 893.6 ± 130.0 | 379.9 | 1459.7 | 2.44 ± 1.12 |
| kcen | input-whyando | 905.9 ± 139.0 | 476.7 | 1425.2 | 2.47 ± 1.15 |
| kcen | input-mattcl | 924.8 ± 174.8 | 308.9 | 1453.9 | 2.52 ± 1.20 |
| mattcl-py | input-lanjian | 17361.2 ± 671.1 | 16212.5 | 20195.0 | 47.39 ± 20.81 |
| mattcl-py | input-mattcl | 17389.3 ± 578.6 | 16361.3 | 21064.5 | 47.46 ± 20.83 |
| mattcl-py | input-whyando | 17413.8 ± 730.8 | 16472.2 | 20612.6 | 47.53 ± 20.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|