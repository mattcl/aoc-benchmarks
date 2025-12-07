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
| mattcl | input-lanjian | 0.6 ± 0.2 | 0.0 | 1.2 | 1.00 |
| mattcl | input-mattcl | 0.6 ± 0.2 | 0.0 | 1.3 | 1.02 ± 0.45 |
| whyando | input-mattcl | 0.6 ± 0.1 | 0.1 | 1.3 | 1.07 ± 0.40 |
| whyando | input-whyando | 0.7 ± 0.1 | 0.1 | 0.8 | 1.09 ± 0.41 |
| mattcl | input-whyando | 0.7 ± 0.2 | 0.1 | 1.7 | 1.13 ± 0.46 |
| whyando | input-lanjian | 0.8 ± 0.3 | 0.0 | 1.9 | 1.26 ± 0.58 |
| kcen | input-lanjian | 1.3 ± 0.2 | 0.5 | 1.8 | 2.22 ± 0.78 |
| kcen | input-mattcl | 1.4 ± 0.2 | 0.3 | 2.4 | 2.26 ± 0.81 |
| kcen | input-whyando | 1.4 ± 0.2 | 0.7 | 1.7 | 2.27 ± 0.76 |
| lanjian | input-mattcl | 1.6 ± 0.5 | 0.5 | 2.9 | 2.67 ± 1.15 |
| lanjian | input-whyando | 1.9 ± 0.3 | 1.1 | 2.7 | 3.12 ± 1.13 |
| lanjian | input-lanjian | 2.0 ± 0.3 | 1.2 | 2.9 | 3.35 ± 1.18 |
| mattcl-py | input-mattcl | 18.2 ± 0.6 | 17.2 | 21.1 | 30.13 ± 9.48 |
| mattcl-py | input-whyando | 18.3 ± 0.6 | 17.4 | 21.0 | 30.29 ± 9.52 |
| mattcl-py | input-lanjian | 18.3 ± 0.9 | 17.0 | 21.6 | 30.31 ± 9.58 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>640</pre>|<pre>365804144481581</pre>|
|input-mattcl|<pre>607</pre>|<pre>342433357244012</pre>|
|input-whyando|<pre>643</pre>|<pre>342018167474526</pre>|