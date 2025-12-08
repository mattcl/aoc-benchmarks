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
| whyando | input-whyando | 341.5 ± 166.6 | 0.0 | 1020.6 | 1.00 |
| whyando | input-lanjian | 351.0 ± 139.6 | 0.0 | 893.0 | 1.03 ± 0.65 |
| whyando | input-mattcl | 373.3 ± 119.1 | 0.0 | 556.7 | 1.09 ± 0.64 |
| mattcl | input-whyando | 380.8 ± 179.7 | 0.0 | 870.6 | 1.12 ± 0.76 |
| mattcl | input-mattcl | 407.5 ± 142.6 | 0.0 | 903.4 | 1.19 ± 0.72 |
| mattcl | input-lanjian | 408.1 ± 147.7 | 0.0 | 1009.9 | 1.19 ± 0.73 |
| kcen | input-whyando | 853.9 ± 143.2 | 48.0 | 1373.9 | 2.50 ± 1.29 |
| kcen | input-mattcl | 854.2 ± 134.9 | 323.6 | 1353.8 | 2.50 ± 1.28 |
| kcen | input-lanjian | 859.4 ± 122.8 | 274.5 | 1301.4 | 2.52 ± 1.28 |
| mattcl-py | input-lanjian | 17342.3 ± 644.0 | 16113.2 | 20668.0 | 50.78 ± 24.85 |
| mattcl-py | input-mattcl | 17410.8 ± 681.6 | 16103.3 | 20481.2 | 50.98 ± 24.95 |
| mattcl-py | input-whyando | 17413.9 ± 508.7 | 16532.5 | 20115.8 | 50.99 ± 24.92 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|