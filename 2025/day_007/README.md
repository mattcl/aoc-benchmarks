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
| whyando | input-mattcl | 298.3 ± 173.5 | 0.0 | 914.1 | 1.00 |
| whyando | input-lanjian | 309.8 ± 151.2 | 0.0 | 760.1 | 1.04 ± 0.79 |
| whyando | input-whyando | 359.0 ± 143.2 | 0.0 | 805.7 | 1.20 ± 0.85 |
| mattcl | input-mattcl | 576.6 ± 184.0 | 0.0 | 1065.6 | 1.93 ± 1.28 |
| mattcl | input-whyando | 591.1 ± 175.2 | 0.0 | 1341.5 | 1.98 ± 1.29 |
| mattcl | input-lanjian | 663.4 ± 154.2 | 28.7 | 1002.8 | 2.22 ± 1.39 |
| kcen | input-whyando | 851.3 ± 152.1 | 360.7 | 1404.5 | 2.85 ± 1.74 |
| kcen | input-lanjian | 857.5 ± 159.4 | 195.0 | 1439.4 | 2.87 ± 1.76 |
| kcen | input-mattcl | 901.9 ± 188.7 | 214.3 | 1488.4 | 3.02 ± 1.87 |
| mattcl-py | input-lanjian | 17291.6 ± 522.9 | 16372.7 | 20412.5 | 57.97 ± 33.76 |
| mattcl-py | input-whyando | 17406.1 ± 568.6 | 16452.3 | 20343.6 | 58.35 ± 33.99 |
| mattcl-py | input-mattcl | 17485.9 ± 814.5 | 16569.0 | 20993.4 | 58.62 ± 34.20 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|