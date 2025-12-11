# Day 6 benchmarks

[link to problem](https://adventofcode.com/2025/day/6)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 6)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-lanjian | 0.5 ± 0.2 | 0.0 | 0.7 | 1.00 |
| whyando | input-whyando | 0.5 ± 0.2 | 0.0 | 0.8 | 1.13 ± 0.65 |
| whyando | input-mattcl | 0.5 ± 0.2 | 0.0 | 0.8 | 1.15 ± 0.63 |
| mattcl | input-mattcl | 0.6 ± 0.3 | 0.0 | 1.0 | 1.23 ± 0.79 |
| lanjian | input-mattcl | 0.6 ± 0.4 | 0.0 | 3.5 | 1.39 ± 1.14 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.0 | 0.9 | 1.57 ± 0.77 |
| mattcl | input-whyando | 0.7 ± 0.2 | 0.2 | 1.0 | 1.62 ± 0.78 |
| lanjian | input-whyando | 1.0 ± 0.2 | 0.1 | 1.2 | 2.14 ± 1.00 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.4 | 1.2 | 2.17 ± 1.01 |
| kcen | input-mattcl | 1.5 ± 0.3 | 0.5 | 2.2 | 3.17 ± 1.51 |
| kcen | input-lanjian | 1.6 ± 0.3 | 0.9 | 2.5 | 3.53 ± 1.69 |
| kcen | input-whyando | 1.7 ± 0.3 | 1.0 | 2.6 | 3.70 ± 1.79 |
| mattcl-py | input-lanjian | 21.2 ± 0.7 | 20.2 | 24.1 | 46.13 ± 20.26 |
| mattcl-py | input-whyando | 21.5 ± 0.5 | 20.5 | 24.5 | 46.72 ± 20.50 |
| mattcl-py | input-mattcl | 22.9 ± 3.6 | 20.5 | 34.8 | 49.68 ± 23.15 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|