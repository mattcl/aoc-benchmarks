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
| mattcl | input-mattcl | 0.6 ± 0.2 | 0.1 | 1.0 | 1.00 |
| mattcl | input-lanjian | 0.6 ± 0.2 | 0.0 | 1.1 | 1.02 ± 0.37 |
| mattcl | input-whyando | 0.6 ± 0.1 | 0.0 | 1.0 | 1.04 ± 0.34 |
| whyando | input-mattcl | 0.6 ± 0.1 | 0.0 | 1.0 | 1.05 ± 0.35 |
| whyando | input-whyando | 0.7 ± 0.2 | 0.0 | 1.1 | 1.07 ± 0.39 |
| whyando | input-lanjian | 0.7 ± 0.1 | 0.2 | 1.1 | 1.14 ± 0.37 |
| lanjian | input-whyando | 1.3 ± 0.2 | 0.5 | 2.1 | 2.11 ± 0.63 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.5 | 2.0 | 2.13 ± 0.62 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.6 | 2.1 | 2.16 ± 0.64 |
| kcen | input-mattcl | 1.4 ± 0.2 | 0.6 | 1.8 | 2.21 ± 0.62 |
| kcen | input-lanjian | 1.4 ± 0.2 | 0.6 | 1.8 | 2.23 ± 0.62 |
| kcen | input-whyando | 1.4 ± 0.2 | 0.5 | 2.1 | 2.23 ± 0.64 |
| mattcl-py | input-mattcl | 18.1 ± 0.7 | 16.7 | 21.2 | 29.45 ± 7.44 |
| mattcl-py | input-lanjian | 18.2 ± 0.6 | 16.8 | 20.8 | 29.62 ± 7.46 |
| mattcl-py | input-whyando | 18.2 ± 0.6 | 16.9 | 21.0 | 29.69 ± 7.49 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>640</pre>|<pre>365804144481581</pre>|
|input-mattcl|<pre>607</pre>|<pre>342433357244012</pre>|
|input-whyando|<pre>643</pre>|<pre>342018167474526</pre>|