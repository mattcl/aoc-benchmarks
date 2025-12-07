# Day 4 benchmarks

[link to problem](https://adventofcode.com/2025/day/4)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 4)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-lanjian | 0.9 ± 0.3 | 0.0 | 1.6 | 1.00 |
| whyando | input-whyando | 1.0 ± 0.1 | 0.4 | 1.6 | 1.12 ± 0.39 |
| whyando | input-mattcl | 1.0 ± 0.1 | 0.5 | 1.5 | 1.13 ± 0.40 |
| mattcl | input-whyando | 1.0 ± 0.4 | 0.1 | 1.8 | 1.19 ± 0.64 |
| mattcl | input-mattcl | 1.2 ± 0.4 | 0.1 | 2.1 | 1.39 ± 0.62 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.5 | 2.1 | 1.53 ± 0.56 |
| lanjian | input-mattcl | 2.5 ± 0.3 | 1.1 | 3.4 | 2.88 ± 1.00 |
| kcen | input-mattcl | 2.5 ± 0.3 | 1.4 | 3.2 | 2.90 ± 1.00 |
| kcen | input-whyando | 2.5 ± 0.2 | 1.4 | 3.2 | 2.91 ± 0.98 |
| kcen | input-lanjian | 2.6 ± 0.3 | 1.7 | 4.3 | 2.98 ± 1.02 |
| lanjian | input-lanjian | 2.7 ± 0.4 | 1.8 | 4.0 | 3.11 ± 1.09 |
| lanjian | input-whyando | 2.8 ± 0.4 | 2.1 | 5.3 | 3.26 ± 1.15 |
| mattcl-py | input-mattcl | 37.9 ± 1.1 | 36.6 | 41.7 | 43.87 ± 14.28 |
| mattcl-py | input-whyando | 38.0 ± 0.7 | 36.9 | 39.9 | 44.05 ± 14.30 |
| mattcl-py | input-lanjian | 38.2 ± 0.9 | 36.4 | 41.1 | 44.25 ± 14.39 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1491</pre>|<pre>8722</pre>|
|input-mattcl|<pre>1441</pre>|<pre>9050</pre>|
|input-whyando|<pre>1419</pre>|<pre>8739</pre>|