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
| mattcl | input-lanjian | 390.9 ± 151.5 | 0.0 | 689.2 | 1.00 |
| whyando | input-lanjian | 392.8 ± 139.7 | 0.0 | 758.5 | 1.00 ± 0.53 |
| whyando | input-mattcl | 401.1 ± 144.8 | 0.0 | 1069.5 | 1.03 ± 0.54 |
| mattcl | input-whyando | 405.4 ± 155.8 | 0.0 | 714.7 | 1.04 ± 0.57 |
| whyando | input-whyando | 410.6 ± 159.0 | 0.0 | 1002.4 | 1.05 ± 0.58 |
| mattcl | input-mattcl | 426.7 ± 163.0 | 0.0 | 978.7 | 1.09 ± 0.59 |
| kcen | input-whyando | 891.8 ± 160.9 | 16.9 | 1430.0 | 2.28 ± 0.98 |
| kcen | input-mattcl | 903.6 ± 142.1 | 119.9 | 1382.5 | 2.31 ± 0.97 |
| kcen | input-lanjian | 909.6 ± 165.1 | 4.7 | 1384.2 | 2.33 ± 1.00 |
| mattcl-py | input-lanjian | 17220.9 ± 431.2 | 16439.2 | 19506.4 | 44.05 ± 17.11 |
| mattcl-py | input-mattcl | 17267.6 ± 598.0 | 16503.4 | 20651.4 | 44.17 ± 17.19 |
| mattcl-py | input-whyando | 17383.1 ± 697.2 | 16121.0 | 20617.9 | 44.47 ± 17.33 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|