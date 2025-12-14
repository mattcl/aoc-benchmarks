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
| mattcl | input-lanjian | 0.7 ± 0.1 | 0.0 | 0.9 | 1.00 |
| mattcl | input-whyando | 0.7 ± 0.2 | 0.1 | 1.3 | 1.01 ± 0.33 |
| whyando | input-mattcl | 0.7 ± 0.1 | 0.2 | 0.9 | 1.02 ± 0.31 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.2 | 1.05 ± 0.33 |
| whyando | input-whyando | 0.7 ± 0.2 | 0.0 | 1.3 | 1.09 ± 0.34 |
| whyando | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.3 | 1.10 ± 0.38 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.5 | 1.6 | 1.41 ± 0.38 |
| lanjian | input-whyando | 1.0 ± 0.2 | 0.0 | 1.5 | 1.42 ± 0.39 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.4 | 1.7 | 1.42 ± 0.42 |
| kcen | input-mattcl | 1.4 ± 0.2 | 0.6 | 2.1 | 2.01 ± 0.53 |
| kcen | input-whyando | 1.4 ± 0.2 | 0.8 | 3.0 | 2.07 ± 0.53 |
| kcen | input-lanjian | 1.4 ± 0.2 | 0.6 | 2.2 | 2.08 ± 0.56 |
| mattcl-py | input-whyando | 18.2 ± 0.5 | 17.2 | 20.5 | 27.00 ± 6.03 |
| mattcl-py | input-mattcl | 18.2 ± 0.8 | 17.2 | 21.3 | 27.09 ± 6.11 |
| mattcl-py | input-lanjian | 18.4 ± 0.7 | 17.2 | 21.0 | 27.29 ± 6.13 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>640</pre>|<pre>365804144481581</pre>|
|input-mattcl|<pre>607</pre>|<pre>342433357244012</pre>|
|input-whyando|<pre>643</pre>|<pre>342018167474526</pre>|