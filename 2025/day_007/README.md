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
| whyando | input-whyando | 361.1 ± 154.5 | 0.0 | 979.0 | 1.00 |
| whyando | input-lanjian | 368.1 ± 153.8 | 0.0 | 937.0 | 1.02 ± 0.61 |
| whyando | input-mattcl | 396.2 ± 149.6 | 0.0 | 900.2 | 1.10 ± 0.63 |
| mattcl | input-lanjian | 410.3 ± 161.3 | 0.0 | 961.6 | 1.14 ± 0.66 |
| mattcl | input-mattcl | 424.5 ± 165.5 | 0.0 | 982.2 | 1.18 ± 0.68 |
| mattcl | input-whyando | 444.2 ± 174.6 | 0.0 | 1191.4 | 1.23 ± 0.71 |
| lanjian | input-lanjian | 672.4 ± 186.8 | 0.0 | 1111.3 | 1.86 ± 0.95 |
| lanjian | input-whyando | 708.1 ± 131.2 | 112.5 | 1085.0 | 1.96 ± 0.91 |
| lanjian | input-mattcl | 715.1 ± 161.2 | 0.0 | 1302.1 | 1.98 ± 0.96 |
| kcen | input-whyando | 861.9 ± 131.9 | 427.3 | 1397.9 | 2.39 ± 1.08 |
| kcen | input-mattcl | 903.0 ± 168.1 | 98.9 | 1397.0 | 2.50 ± 1.17 |
| kcen | input-lanjian | 905.9 ± 192.4 | 0.0 | 1615.6 | 2.51 ± 1.20 |
| mattcl-py | input-mattcl | 17434.6 ± 717.0 | 16013.8 | 20932.1 | 48.28 ± 20.75 |
| mattcl-py | input-lanjian | 17462.9 ± 778.2 | 16367.9 | 20651.4 | 48.36 ± 20.80 |
| mattcl-py | input-whyando | 17485.6 ± 666.9 | 16492.4 | 20720.7 | 48.42 ± 20.80 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1516</pre>|<pre>1393669447690</pre>|
|input-mattcl|<pre>1642</pre>|<pre>47274292756692</pre>|
|input-whyando|<pre>1672</pre>|<pre>231229866702355</pre>|