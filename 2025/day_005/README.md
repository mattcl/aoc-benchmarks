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
| whyando | input-lanjian | 0.5 ± 0.3 | 0.0 | 1.3 | 1.00 |
| mattcl | input-lanjian | 0.6 ± 0.2 | 0.0 | 1.2 | 1.19 ± 0.74 |
| mattcl | input-mattcl | 0.6 ± 0.2 | 0.0 | 1.0 | 1.25 ± 0.74 |
| mattcl | input-whyando | 0.7 ± 0.1 | 0.0 | 1.0 | 1.29 ± 0.73 |
| whyando | input-mattcl | 0.7 ± 0.1 | 0.2 | 1.1 | 1.34 ± 0.76 |
| whyando | input-whyando | 0.7 ± 0.1 | 0.3 | 1.3 | 1.39 ± 0.78 |
| kcen | input-mattcl | 1.1 ± 0.4 | 0.1 | 2.5 | 2.13 ± 1.40 |
| kcen | input-whyando | 1.3 ± 0.2 | 0.6 | 1.8 | 2.57 ± 1.42 |
| kcen | input-lanjian | 1.4 ± 0.2 | 0.2 | 2.1 | 2.62 ± 1.45 |
| lanjian | input-mattcl | 1.7 ± 0.4 | 0.6 | 2.7 | 3.23 ± 1.85 |
| lanjian | input-lanjian | 2.0 ± 0.3 | 0.8 | 2.9 | 3.77 ± 2.12 |
| lanjian | input-whyando | 2.0 ± 0.4 | 1.0 | 3.2 | 3.82 ± 2.17 |
| mattcl-py | input-mattcl | 18.0 ± 0.5 | 16.6 | 21.1 | 34.85 ± 18.59 |
| mattcl-py | input-whyando | 18.2 ± 0.7 | 17.2 | 21.4 | 35.21 ± 18.79 |
| mattcl-py | input-lanjian | 18.2 ± 0.9 | 16.5 | 21.8 | 35.24 ± 18.84 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>640</pre>|<pre>365804144481581</pre>|
|input-mattcl|<pre>607</pre>|<pre>342433357244012</pre>|
|input-whyando|<pre>643</pre>|<pre>342018167474526</pre>|