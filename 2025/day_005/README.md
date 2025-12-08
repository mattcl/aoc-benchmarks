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
| mattcl | input-whyando | 0.6 ± 0.2 | 0.0 | 1.0 | 1.00 |
| mattcl | input-mattcl | 0.6 ± 0.2 | 0.0 | 1.0 | 1.04 ± 0.44 |
| whyando | input-mattcl | 0.6 ± 0.1 | 0.0 | 1.1 | 1.05 ± 0.42 |
| mattcl | input-lanjian | 0.7 ± 0.1 | 0.1 | 1.1 | 1.07 ± 0.42 |
| whyando | input-lanjian | 0.7 ± 0.1 | 0.0 | 1.1 | 1.10 ± 0.41 |
| whyando | input-whyando | 0.7 ± 0.1 | 0.2 | 1.0 | 1.11 ± 0.41 |
| lanjian | input-whyando | 0.9 ± 0.2 | 0.3 | 1.5 | 1.53 ± 0.55 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.3 | 1.5 | 1.53 ± 0.55 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.4 | 1.6 | 1.60 ± 0.59 |
| kcen | input-lanjian | 1.2 ± 0.4 | 0.1 | 3.7 | 2.03 ± 0.92 |
| kcen | input-mattcl | 1.4 ± 0.1 | 0.7 | 1.6 | 2.28 ± 0.76 |
| kcen | input-whyando | 1.4 ± 0.2 | 0.7 | 2.2 | 2.31 ± 0.78 |
| mattcl-py | input-whyando | 18.1 ± 0.6 | 17.1 | 21.3 | 29.75 ± 9.61 |
| mattcl-py | input-lanjian | 18.2 ± 0.6 | 17.1 | 20.9 | 29.84 ± 9.65 |
| mattcl-py | input-mattcl | 18.2 ± 0.7 | 17.1 | 21.4 | 29.97 ± 9.70 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>640</pre>|<pre>365804144481581</pre>|
|input-mattcl|<pre>607</pre>|<pre>342433357244012</pre>|
|input-whyando|<pre>643</pre>|<pre>342018167474526</pre>|