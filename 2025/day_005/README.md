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
| whyando | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.0 | 1.00 |
| whyando | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.4 | 1.04 ± 0.38 |
| whyando | input-whyando | 0.7 ± 0.2 | 0.0 | 1.2 | 1.06 ± 0.38 |
| mattcl | input-whyando | 1.1 ± 0.1 | 0.5 | 1.7 | 1.63 ± 0.49 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.8 | 1.64 ± 0.51 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.1 | 1.8 | 1.65 ± 0.54 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.6 | 2.5 | 1.99 ± 0.61 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.2 | 2.05 ± 0.64 |
| kcen | input-mattcl | 1.4 ± 0.2 | 0.3 | 1.7 | 2.06 ± 0.63 |
| lanjian | input-whyando | 1.4 ± 0.2 | 0.6 | 2.6 | 2.06 ± 0.65 |
| kcen | input-whyando | 1.5 ± 0.2 | 0.6 | 1.8 | 2.17 ± 0.63 |
| kcen | input-lanjian | 1.5 ± 0.2 | 0.8 | 2.1 | 2.19 ± 0.64 |
| mattcl-py | input-mattcl | 18.1 ± 0.6 | 16.9 | 21.3 | 26.86 ± 7.27 |
| mattcl-py | input-whyando | 18.1 ± 0.5 | 17.1 | 20.7 | 26.92 ± 7.28 |
| mattcl-py | input-lanjian | 18.2 ± 0.7 | 17.0 | 21.5 | 27.10 ± 7.35 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>640</pre>|<pre>365804144481581</pre>|
|input-mattcl|<pre>607</pre>|<pre>342433357244012</pre>|
|input-whyando|<pre>643</pre>|<pre>342018167474526</pre>|