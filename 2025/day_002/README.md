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
| whyando | input-whyando | 366.6 ± 160.2 | 0.0 | 988.9 | 1.00 |
| whyando | input-mattcl | 413.6 ± 152.8 | 0.0 | 1010.6 | 1.13 ± 0.65 |
| whyando | input-lanjian | 427.7 ± 124.5 | 0.0 | 937.9 | 1.17 ± 0.61 |
| mattcl | input-whyando | 619.8 ± 154.8 | 0.0 | 1054.7 | 1.69 ± 0.85 |
| mattcl | input-lanjian | 620.5 ± 175.1 | 0.0 | 1199.7 | 1.69 ± 0.88 |
| mattcl | input-mattcl | 642.0 ± 167.7 | 0.0 | 1397.0 | 1.75 ± 0.89 |
| kcen | input-lanjian | 775.1 ± 210.1 | 0.0 | 1541.6 | 2.11 ± 1.09 |
| kcen | input-mattcl | 787.8 ± 128.4 | 252.4 | 1242.9 | 2.15 ± 1.00 |
| kcen | input-whyando | 806.1 ± 119.0 | 466.1 | 1234.2 | 2.20 ± 1.01 |
| lanjian | input-mattcl | 839.2 ± 137.1 | 406.9 | 1368.0 | 2.29 ± 1.07 |
| lanjian | input-whyando | 843.5 ± 160.7 | 36.9 | 1295.8 | 2.30 ± 1.10 |
| lanjian | input-lanjian | 868.1 ± 142.6 | 400.8 | 1449.1 | 2.37 ± 1.11 |
| mattcl-py | input-whyando | 20512.8 ± 609.8 | 18966.1 | 23607.2 | 55.95 ± 24.51 |
| mattcl-py | input-mattcl | 20636.3 ± 486.1 | 19834.6 | 22913.3 | 56.29 ± 24.64 |
| mattcl-py | input-lanjian | 20915.2 ± 786.7 | 19770.6 | 24169.5 | 57.05 ± 25.03 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|