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
| whyando | input-whyando | 0.6 ± 0.2 | 0.0 | 1.1 | 1.00 |
| whyando | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.1 | 1.03 ± 0.35 |
| whyando | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.3 | 1.10 ± 0.37 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.8 | 1.63 ± 0.48 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.6 | 1.8 | 1.67 ± 0.50 |
| mattcl | input-whyando | 1.1 ± 0.2 | 0.6 | 2.3 | 1.72 ± 0.56 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.6 | 2.5 | 2.04 ± 0.63 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.6 | 2.6 | 2.10 ± 0.63 |
| lanjian | input-whyando | 1.4 ± 0.2 | 0.6 | 2.6 | 2.11 ± 0.65 |
| kcen | input-whyando | 1.4 ± 0.2 | 0.7 | 2.1 | 2.13 ± 0.65 |
| kcen | input-lanjian | 1.4 ± 0.2 | 0.6 | 2.1 | 2.14 ± 0.62 |
| kcen | input-mattcl | 1.4 ± 0.2 | 0.6 | 1.9 | 2.18 ± 0.62 |
| mattcl-py | input-lanjian | 18.1 ± 0.7 | 16.8 | 21.2 | 28.11 ± 7.27 |
| mattcl-py | input-mattcl | 18.1 ± 0.7 | 17.0 | 21.7 | 28.12 ± 7.26 |
| mattcl-py | input-whyando | 18.2 ± 0.7 | 17.2 | 21.1 | 28.33 ± 7.32 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>640</pre>|<pre>365804144481581</pre>|
|input-mattcl|<pre>607</pre>|<pre>342433357244012</pre>|
|input-whyando|<pre>643</pre>|<pre>342018167474526</pre>|