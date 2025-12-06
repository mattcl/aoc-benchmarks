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
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.2 | 1.00 |
| whyando | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.1 | 1.05 ± 0.37 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.3 | 1.3 | 1.06 ± 0.37 |
| mattcl | input-whyando | 0.7 ± 0.2 | 0.0 | 1.3 | 1.10 ± 0.39 |
| whyando | input-lanjian | 0.7 ± 0.1 | 0.2 | 1.2 | 1.10 ± 0.35 |
| whyando | input-whyando | 0.8 ± 0.2 | 0.0 | 1.4 | 1.12 ± 0.38 |
| kcen | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.6 | 2.04 ± 0.63 |
| kcen | input-lanjian | 1.4 ± 0.2 | 0.6 | 2.1 | 2.05 ± 0.60 |
| kcen | input-whyando | 1.4 ± 0.2 | 0.6 | 2.1 | 2.10 ± 0.61 |
| lanjian | input-mattcl | 1.8 ± 0.4 | 0.8 | 2.9 | 2.66 ± 0.89 |
| lanjian | input-whyando | 2.0 ± 0.4 | 1.2 | 2.9 | 2.93 ± 0.93 |
| lanjian | input-lanjian | 2.1 ± 0.3 | 1.2 | 3.2 | 3.05 ± 0.94 |
| mattcl-py | input-whyando | 18.2 ± 0.6 | 16.9 | 21.2 | 26.80 ± 7.12 |
| mattcl-py | input-mattcl | 18.3 ± 0.7 | 17.2 | 21.5 | 27.02 ± 7.21 |
| mattcl-py | input-lanjian | 18.4 ± 0.8 | 17.0 | 21.7 | 27.10 ± 7.24 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>640</pre>|<pre>365804144481581</pre>|
|input-mattcl|<pre>607</pre>|<pre>342433357244012</pre>|
|input-whyando|<pre>643</pre>|<pre>342018167474526</pre>|