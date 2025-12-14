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
| mattcl | input-whyando | 394.7 ± 187.8 | 0.0 | 975.5 | 1.00 |
| whyando | input-mattcl | 399.2 ± 160.7 | 0.0 | 932.5 | 1.01 ± 0.63 |
| mattcl | input-lanjian | 409.1 ± 181.1 | 0.0 | 970.3 | 1.04 ± 0.67 |
| mattcl | input-mattcl | 410.3 ± 190.2 | 0.0 | 920.0 | 1.04 ± 0.69 |
| whyando | input-whyando | 421.5 ± 165.4 | 0.0 | 1109.2 | 1.07 ± 0.66 |
| whyando | input-lanjian | 430.3 ± 162.1 | 0.0 | 833.9 | 1.09 ± 0.66 |
| lanjian | input-whyando | 728.2 ± 146.2 | 161.7 | 923.5 | 1.84 ± 0.95 |
| lanjian | input-lanjian | 728.6 ± 166.7 | 0.0 | 1186.1 | 1.85 ± 0.97 |
| lanjian | input-mattcl | 750.2 ± 156.3 | 0.0 | 1378.7 | 1.90 ± 0.99 |
| kcen | input-whyando | 912.3 ± 173.8 | 400.1 | 1469.0 | 2.31 ± 1.18 |
| kcen | input-lanjian | 937.1 ± 136.4 | 408.5 | 1445.6 | 2.37 ± 1.18 |
| kcen | input-mattcl | 947.9 ± 175.7 | 238.9 | 1555.0 | 2.40 ± 1.23 |
| mattcl-py | input-lanjian | 17505.0 ± 708.1 | 16326.9 | 20342.4 | 44.35 ± 21.18 |
| mattcl-py | input-mattcl | 17541.1 ± 554.7 | 16507.9 | 20575.3 | 44.44 ± 21.19 |
| mattcl-py | input-whyando | 17588.7 ± 602.4 | 16521.8 | 20731.5 | 44.56 ± 21.26 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|