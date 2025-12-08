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
| whyando | input-whyando | 372.0 ± 161.0 | 0.0 | 842.1 | 1.00 |
| whyando | input-lanjian | 398.0 ± 166.1 | 0.0 | 946.6 | 1.07 ± 0.64 |
| whyando | input-mattcl | 404.1 ± 161.7 | 0.0 | 1004.0 | 1.09 ± 0.64 |
| mattcl | input-lanjian | 614.4 ± 180.2 | 0.0 | 1083.6 | 1.65 ± 0.86 |
| mattcl | input-whyando | 631.4 ± 150.5 | 100.0 | 1052.8 | 1.70 ± 0.84 |
| mattcl | input-mattcl | 636.5 ± 126.6 | 134.1 | 863.5 | 1.71 ± 0.81 |
| kcen | input-lanjian | 894.1 ± 139.2 | 419.3 | 1677.7 | 2.40 ± 1.11 |
| kcen | input-mattcl | 903.1 ± 124.3 | 437.2 | 1491.3 | 2.43 ± 1.10 |
| kcen | input-whyando | 906.9 ± 141.5 | 166.0 | 1492.5 | 2.44 ± 1.12 |
| mattcl-py | input-whyando | 17279.9 ± 538.4 | 16383.0 | 20153.7 | 46.45 ± 20.15 |
| mattcl-py | input-lanjian | 17293.7 ± 603.8 | 16556.5 | 20274.3 | 46.49 ± 20.18 |
| mattcl-py | input-mattcl | 17396.0 ± 695.9 | 16331.7 | 20597.5 | 46.76 ± 20.32 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|