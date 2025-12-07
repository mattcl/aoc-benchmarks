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
| whyando | input-lanjian | 364.9 ± 189.2 | 0.0 | 896.3 | 1.00 |
| whyando | input-whyando | 383.2 ± 159.6 | 0.0 | 1045.9 | 1.05 ± 0.70 |
| whyando | input-mattcl | 383.2 ± 163.4 | 0.0 | 975.7 | 1.05 ± 0.71 |
| mattcl | input-mattcl | 410.8 ± 143.3 | 0.0 | 664.7 | 1.13 ± 0.70 |
| mattcl | input-whyando | 433.3 ± 156.5 | 0.0 | 1030.6 | 1.19 ± 0.75 |
| mattcl | input-lanjian | 455.0 ± 131.5 | 0.0 | 945.2 | 1.25 ± 0.74 |
| kcen | input-mattcl | 874.4 ± 154.3 | 336.7 | 1359.9 | 2.40 ± 1.31 |
| kcen | input-whyando | 887.7 ± 146.8 | 60.5 | 1427.3 | 2.43 ± 1.32 |
| kcen | input-lanjian | 892.7 ± 169.7 | 0.0 | 1579.5 | 2.45 ± 1.35 |
| lanjian | input-mattcl | 1390.8 ± 176.9 | 461.7 | 1796.9 | 3.81 ± 2.04 |
| lanjian | input-lanjian | 1402.9 ± 207.0 | 354.1 | 2145.8 | 3.85 ± 2.07 |
| lanjian | input-whyando | 1426.8 ± 105.0 | 796.7 | 1700.1 | 3.91 ± 2.05 |
| mattcl-py | input-mattcl | 17438.2 ± 631.9 | 16153.3 | 21043.4 | 47.79 ± 24.85 |
| mattcl-py | input-whyando | 17473.6 ± 645.4 | 16459.8 | 20930.1 | 47.89 ± 24.90 |
| mattcl-py | input-lanjian | 17532.7 ± 671.2 | 16344.3 | 20276.8 | 48.05 ± 24.99 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|