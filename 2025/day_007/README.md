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
| whyando | input-mattcl | 306.4 ± 214.9 | 0.0 | 627.1 | 1.00 |
| whyando | input-lanjian | 383.6 ± 193.6 | 0.0 | 819.7 | 1.25 ± 1.08 |
| whyando | input-whyando | 405.3 ± 176.1 | 0.0 | 865.1 | 1.32 ± 1.09 |
| mattcl | input-mattcl | 657.2 ± 178.1 | 0.0 | 1056.6 | 2.15 ± 1.61 |
| mattcl | input-whyando | 666.2 ± 162.5 | 0.0 | 1361.7 | 2.17 ± 1.61 |
| mattcl | input-lanjian | 666.6 ± 164.0 | 0.0 | 1267.0 | 2.18 ± 1.62 |
| kcen | input-whyando | 943.9 ± 160.5 | 42.1 | 1498.5 | 3.08 ± 2.22 |
| kcen | input-mattcl | 952.7 ± 127.3 | 429.8 | 1480.8 | 3.11 ± 2.22 |
| kcen | input-lanjian | 953.3 ± 134.6 | 486.5 | 1332.1 | 3.11 ± 2.23 |
| mattcl-py | input-mattcl | 17478.2 ± 455.8 | 16627.3 | 20165.7 | 57.04 ± 40.04 |
| mattcl-py | input-lanjian | 17521.3 ± 670.4 | 16521.3 | 20729.7 | 57.18 ± 40.17 |
| mattcl-py | input-whyando | 17578.1 ± 600.6 | 16567.9 | 20431.9 | 57.37 ± 40.28 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|