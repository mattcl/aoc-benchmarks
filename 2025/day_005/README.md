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
| whyando | input-lanjian | 0.6 ± 0.2 | 0.0 | 1.2 | 1.00 |
| whyando | input-whyando | 0.6 ± 0.1 | 0.0 | 1.0 | 1.04 ± 0.40 |
| whyando | input-mattcl | 0.7 ± 0.1 | 0.2 | 1.2 | 1.11 ± 0.42 |
| mattcl | input-lanjian | 0.7 ± 0.1 | 0.0 | 1.0 | 1.14 ± 0.42 |
| mattcl | input-mattcl | 0.7 ± 0.1 | 0.0 | 0.9 | 1.14 ± 0.42 |
| mattcl | input-whyando | 0.8 ± 0.2 | 0.1 | 1.6 | 1.21 ± 0.47 |
| kcen | input-lanjian | 1.3 ± 0.2 | 0.2 | 2.4 | 2.16 ± 0.78 |
| kcen | input-mattcl | 1.3 ± 0.2 | 0.6 | 1.8 | 2.17 ± 0.74 |
| kcen | input-whyando | 1.4 ± 0.2 | 0.5 | 2.5 | 2.19 ± 0.78 |
| lanjian | input-mattcl | 1.8 ± 0.4 | 0.9 | 2.8 | 2.90 ± 1.08 |
| lanjian | input-whyando | 1.8 ± 0.3 | 1.0 | 2.6 | 2.95 ± 1.08 |
| lanjian | input-lanjian | 2.0 ± 0.4 | 1.2 | 3.0 | 3.19 ± 1.17 |
| mattcl-py | input-lanjian | 18.2 ± 0.6 | 17.3 | 21.3 | 29.25 ± 9.27 |
| mattcl-py | input-mattcl | 18.2 ± 0.6 | 17.3 | 20.9 | 29.29 ± 9.28 |
| mattcl-py | input-whyando | 18.2 ± 0.7 | 17.0 | 21.3 | 29.36 ± 9.32 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>640</pre>|<pre>365804144481581</pre>|
|input-mattcl|<pre>607</pre>|<pre>342433357244012</pre>|
|input-whyando|<pre>643</pre>|<pre>342018167474526</pre>|