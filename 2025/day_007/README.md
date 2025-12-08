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
| whyando | input-lanjian | 340.4 ± 174.3 | 0.0 | 739.8 | 1.00 |
| whyando | input-mattcl | 369.5 ± 170.5 | 0.0 | 637.2 | 1.09 ± 0.75 |
| whyando | input-whyando | 375.7 ± 164.0 | 0.0 | 626.3 | 1.10 ± 0.74 |
| mattcl | input-whyando | 672.7 ± 157.0 | 0.0 | 930.6 | 1.98 ± 1.11 |
| mattcl | input-lanjian | 700.0 ± 157.7 | 31.9 | 924.6 | 2.06 ± 1.15 |
| kcen | input-whyando | 895.0 ± 211.7 | 11.0 | 1160.4 | 2.63 ± 1.48 |
| kcen | input-lanjian | 928.1 ± 157.8 | 0.0 | 1140.9 | 2.73 ± 1.47 |
| mattcl | input-mattcl | 1145.8 ± 3276.1 | 0.0 | 19449.0 | 3.37 ± 9.78 |
| kcen | input-mattcl | 1217.5 ± 1880.2 | 0.0 | 14988.4 | 3.58 ± 5.82 |
| mattcl-py | input-lanjian | 17787.3 ± 571.0 | 16684.4 | 20718.2 | 52.26 ± 26.81 |
| mattcl-py | input-mattcl | 18057.4 ± 659.1 | 16854.5 | 20776.8 | 53.05 ± 27.23 |
| mattcl-py | input-whyando | 18071.4 ± 572.9 | 16945.5 | 20891.1 | 53.09 ± 27.24 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|