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
| whyando | input-mattcl | 0.3 ± 0.2 | 0.0 | 0.9 | 1.00 |
| whyando | input-lanjian | 0.4 ± 0.1 | 0.0 | 0.8 | 1.38 ± 1.08 |
| whyando | input-whyando | 0.5 ± 0.2 | 0.0 | 1.0 | 1.71 ± 1.31 |
| mattcl | input-mattcl | 0.6 ± 0.2 | 0.1 | 1.1 | 2.17 ± 1.64 |
| mattcl | input-whyando | 0.7 ± 0.2 | 0.1 | 1.2 | 2.23 ± 1.65 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.2 | 2.25 ± 1.68 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.5 | 2.0 | 4.03 ± 2.94 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 2.0 | 4.18 ± 3.03 |
| lanjian | input-whyando | 1.3 ± 0.3 | 0.5 | 2.5 | 4.47 ± 3.26 |
| kcen | input-mattcl | 1.5 ± 0.3 | 0.5 | 2.8 | 4.88 ± 3.54 |
| kcen | input-lanjian | 1.5 ± 0.3 | 1.0 | 2.7 | 5.13 ± 3.72 |
| kcen | input-whyando | 1.6 ± 0.3 | 0.8 | 2.6 | 5.29 ± 3.86 |
| mattcl-py | input-whyando | 20.8 ± 0.7 | 19.5 | 23.3 | 69.62 ± 48.94 |
| mattcl-py | input-mattcl | 20.8 ± 0.7 | 19.4 | 24.1 | 69.63 ± 48.94 |
| mattcl-py | input-lanjian | 20.8 ± 0.5 | 19.9 | 24.0 | 69.68 ± 48.95 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|