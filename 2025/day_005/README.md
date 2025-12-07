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
| mattcl | input-mattcl | 0.6 ± 0.2 | 0.0 | 1.1 | 1.00 |
| whyando | input-mattcl | 0.6 ± 0.1 | 0.0 | 0.9 | 1.00 ± 0.35 |
| mattcl | input-whyando | 0.6 ± 0.2 | 0.0 | 1.0 | 1.01 ± 0.38 |
| mattcl | input-lanjian | 0.6 ± 0.2 | 0.0 | 1.4 | 1.02 ± 0.39 |
| whyando | input-whyando | 0.6 ± 0.2 | 0.1 | 1.1 | 1.04 ± 0.40 |
| whyando | input-lanjian | 0.6 ± 0.1 | 0.0 | 1.1 | 1.04 ± 0.36 |
| kcen | input-lanjian | 1.3 ± 0.2 | 0.6 | 2.1 | 2.13 ± 0.65 |
| kcen | input-mattcl | 1.4 ± 0.2 | 0.5 | 2.0 | 2.19 ± 0.65 |
| kcen | input-whyando | 1.4 ± 0.2 | 0.7 | 2.1 | 2.23 ± 0.65 |
| lanjian | input-mattcl | 1.7 ± 0.4 | 0.9 | 2.7 | 2.78 ± 0.94 |
| lanjian | input-whyando | 1.9 ± 0.4 | 0.8 | 2.8 | 3.06 ± 1.01 |
| lanjian | input-lanjian | 1.9 ± 0.3 | 1.0 | 2.9 | 3.12 ± 1.01 |
| mattcl-py | input-mattcl | 18.0 ± 0.7 | 16.7 | 21.2 | 29.15 ± 7.91 |
| mattcl-py | input-lanjian | 18.1 ± 0.7 | 17.1 | 21.0 | 29.21 ± 7.93 |
| mattcl-py | input-whyando | 18.1 ± 0.7 | 16.8 | 21.0 | 29.30 ± 7.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>640</pre>|<pre>365804144481581</pre>|
|input-mattcl|<pre>607</pre>|<pre>342433357244012</pre>|
|input-whyando|<pre>643</pre>|<pre>342018167474526</pre>|