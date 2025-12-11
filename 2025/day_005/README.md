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
| mattcl | input-lanjian | 0.5 ± 0.2 | 0.0 | 1.1 | 1.00 |
| mattcl | input-whyando | 0.6 ± 0.1 | 0.2 | 1.0 | 1.20 ± 0.61 |
| whyando | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.1 | 1.23 ± 0.63 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.1 | 1.24 ± 0.66 |
| whyando | input-whyando | 0.7 ± 0.2 | 0.0 | 1.1 | 1.25 ± 0.66 |
| whyando | input-lanjian | 0.7 ± 0.2 | 0.2 | 1.5 | 1.28 ± 0.67 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.0 | 1.5 | 1.55 ± 0.82 |
| lanjian | input-whyando | 0.9 ± 0.1 | 0.0 | 1.5 | 1.72 ± 0.84 |
| lanjian | input-lanjian | 0.9 ± 0.1 | 0.5 | 1.6 | 1.75 ± 0.86 |
| kcen | input-lanjian | 1.3 ± 0.2 | 0.3 | 1.8 | 2.47 ± 1.21 |
| kcen | input-whyando | 1.4 ± 0.1 | 0.7 | 1.8 | 2.52 ± 1.20 |
| kcen | input-mattcl | 1.4 ± 0.2 | 0.5 | 2.1 | 2.53 ± 1.22 |
| mattcl-py | input-mattcl | 18.1 ± 0.6 | 17.3 | 21.5 | 33.65 ± 15.63 |
| mattcl-py | input-whyando | 18.2 ± 0.6 | 17.3 | 21.3 | 33.76 ± 15.68 |
| mattcl-py | input-lanjian | 18.4 ± 0.8 | 16.8 | 21.8 | 34.18 ± 15.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>640</pre>|<pre>365804144481581</pre>|
|input-mattcl|<pre>607</pre>|<pre>342433357244012</pre>|
|input-whyando|<pre>643</pre>|<pre>342018167474526</pre>|