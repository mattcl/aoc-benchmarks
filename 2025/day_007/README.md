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
| whyando | input-mattcl | 399.4 ± 160.1 | 0.0 | 967.2 | 1.00 |
| whyando | input-lanjian | 413.7 ± 158.3 | 0.0 | 968.6 | 1.04 ± 0.57 |
| mattcl | input-lanjian | 429.3 ± 183.5 | 0.0 | 1009.0 | 1.07 ± 0.63 |
| whyando | input-whyando | 438.0 ± 130.6 | 0.0 | 636.3 | 1.10 ± 0.55 |
| mattcl | input-whyando | 442.8 ± 168.5 | 0.0 | 874.0 | 1.11 ± 0.61 |
| mattcl | input-mattcl | 449.5 ± 168.6 | 0.0 | 986.1 | 1.13 ± 0.62 |
| lanjian | input-lanjian | 685.6 ± 173.4 | 0.0 | 1318.4 | 1.72 ± 0.81 |
| lanjian | input-mattcl | 729.9 ± 155.0 | 0.0 | 1325.7 | 1.83 ± 0.83 |
| lanjian | input-whyando | 748.6 ± 140.9 | 0.4 | 1151.5 | 1.87 ± 0.83 |
| kcen | input-mattcl | 936.4 ± 177.5 | 359.5 | 1639.9 | 2.34 ± 1.04 |
| kcen | input-lanjian | 937.3 ± 133.8 | 531.2 | 1863.5 | 2.35 ± 1.00 |
| kcen | input-whyando | 981.3 ± 161.6 | 323.7 | 1625.7 | 2.46 ± 1.06 |
| mattcl-py | input-whyando | 17410.1 ± 579.1 | 16457.9 | 20300.9 | 43.59 ± 17.54 |
| mattcl-py | input-mattcl | 17420.2 ± 663.0 | 16383.9 | 20648.9 | 43.62 ± 17.57 |
| mattcl-py | input-lanjian | 17467.4 ± 628.8 | 16475.6 | 19907.0 | 43.74 ± 17.60 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|