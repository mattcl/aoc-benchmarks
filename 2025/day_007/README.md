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
| whyando | input-lanjian | 359.7 ± 152.8 | 0.0 | 977.7 | 1.00 |
| whyando | input-mattcl | 364.9 ± 152.7 | 0.0 | 973.3 | 1.01 ± 0.60 |
| whyando | input-whyando | 401.2 ± 143.5 | 0.0 | 958.3 | 1.12 ± 0.62 |
| mattcl | input-mattcl | 407.9 ± 178.9 | 0.0 | 1026.1 | 1.13 ± 0.69 |
| mattcl | input-lanjian | 426.9 ± 144.6 | 0.0 | 997.2 | 1.19 ± 0.64 |
| mattcl | input-whyando | 443.5 ± 136.1 | 0.0 | 972.4 | 1.23 ± 0.65 |
| lanjian | input-mattcl | 685.4 ± 145.8 | 0.0 | 926.1 | 1.91 ± 0.91 |
| lanjian | input-whyando | 699.3 ± 149.4 | 0.0 | 1215.0 | 1.94 ± 0.92 |
| lanjian | input-lanjian | 710.4 ± 140.8 | 18.2 | 1120.0 | 1.98 ± 0.93 |
| kcen | input-whyando | 870.5 ± 152.9 | 183.6 | 1360.2 | 2.42 ± 1.11 |
| kcen | input-mattcl | 878.4 ± 141.3 | 276.8 | 1437.5 | 2.44 ± 1.11 |
| kcen | input-lanjian | 892.0 ± 163.6 | 271.5 | 1409.3 | 2.48 ± 1.15 |
| mattcl-py | input-lanjian | 17507.4 ± 729.3 | 16323.9 | 21056.5 | 48.68 ± 20.78 |
| mattcl-py | input-mattcl | 17511.2 ± 635.9 | 16527.3 | 20482.5 | 48.69 ± 20.76 |
| mattcl-py | input-whyando | 17550.0 ± 711.3 | 16682.1 | 21097.1 | 48.80 ± 20.82 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|