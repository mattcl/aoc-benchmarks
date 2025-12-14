# Day 5 benchmarks

[link to problem](https://adventofcode.com/2025/day/5)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 5)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-mattcl | 0.2 ± 0.3 | 0.0 | 1.0 | 1.00 |
| mattcl | input-whyando | 0.6 ± 0.2 | 0.0 | 1.2 | 2.69 ± 3.14 |
| mattcl | input-lanjian | 0.6 ± 0.2 | 0.0 | 1.2 | 2.75 ± 3.24 |
| whyando | input-lanjian | 0.6 ± 0.2 | 0.0 | 1.4 | 2.76 ± 3.23 |
| mattcl | input-mattcl | 0.7 ± 0.1 | 0.2 | 1.2 | 2.80 ± 3.23 |
| whyando | input-whyando | 0.7 ± 0.2 | 0.1 | 1.3 | 2.89 ± 3.36 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.0 | 1.4 | 3.84 ± 4.42 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.4 | 2.9 | 4.20 ± 4.89 |
| lanjian | input-whyando | 1.0 ± 0.2 | 0.6 | 1.6 | 4.41 ± 5.08 |
| kcen | input-whyando | 1.1 ± 0.3 | 0.1 | 1.7 | 4.86 ± 5.71 |
| kcen | input-lanjian | 1.3 ± 0.2 | 0.5 | 2.0 | 5.57 ± 6.42 |
| kcen | input-mattcl | 1.3 ± 0.2 | 0.7 | 2.0 | 5.67 ± 6.50 |
| mattcl-py | input-whyando | 18.1 ± 0.6 | 17.0 | 21.3 | 77.35 ± 88.13 |
| mattcl-py | input-lanjian | 18.3 ± 0.6 | 17.1 | 21.1 | 77.85 ± 88.70 |
| mattcl-py | input-mattcl | 18.4 ± 0.8 | 17.2 | 24.0 | 78.63 ± 89.62 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>640</pre>|<pre>365804144481581</pre>|
|input-mattcl|<pre>607</pre>|<pre>342433357244012</pre>|
|input-whyando|<pre>643</pre>|<pre>342018167474526</pre>|