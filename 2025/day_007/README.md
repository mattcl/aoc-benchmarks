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
| whyando | input-whyando | 11.4 ± 29.0 | 0.0 | 157.6 | 1.00 |
| whyando | input-mattcl | 28.6 ± 43.9 | 0.0 | 185.9 | 2.51 ± 7.46 |
| whyando | input-lanjian | 35.0 ± 48.0 | 0.0 | 167.7 | 3.07 ± 8.88 |
| mattcl | input-lanjian | 46.7 ± 54.8 | 0.0 | 263.2 | 4.10 ± 11.49 |
| mattcl | input-mattcl | 52.4 ± 58.8 | 0.0 | 228.2 | 4.60 ± 12.79 |
| mattcl | input-whyando | 58.6 ± 62.8 | 0.0 | 255.6 | 5.15 ± 14.20 |
| lanjian | input-mattcl | 293.1 ± 122.8 | 0.0 | 484.9 | 25.72 ± 66.32 |
| lanjian | input-whyando | 293.2 ± 144.0 | 0.0 | 556.8 | 25.74 ± 66.68 |
| lanjian | input-lanjian | 296.2 ± 139.4 | 0.0 | 547.9 | 25.99 ± 67.24 |
| kcen | input-lanjian | 353.0 ± 418.5 | 0.0 | 4971.5 | 30.98 ± 86.95 |
| kcen | input-mattcl | 453.7 ± 143.4 | 0.0 | 660.2 | 39.82 ± 102.06 |
| kcen | input-whyando | 464.0 ± 169.2 | 0.0 | 659.0 | 40.73 ± 104.65 |
| mattcl-py | input-lanjian | 17608.0 ± 447.3 | 16617.6 | 19796.7 | 1545.44 ± 3931.27 |
| mattcl-py | input-mattcl | 17662.1 ± 471.9 | 16791.4 | 19754.4 | 1550.18 ± 3943.36 |
| mattcl-py | input-whyando | 18671.3 ± 2900.0 | 16349.3 | 29865.2 | 1638.76 ± 4176.22 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|