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
| whyando | input-lanjian | 0.4 ± 0.2 | 0.0 | 0.7 | 1.00 |
| whyando | input-whyando | 0.4 ± 0.2 | 0.0 | 0.8 | 1.02 ± 0.70 |
| whyando | input-mattcl | 0.5 ± 0.2 | 0.0 | 0.7 | 1.15 ± 0.69 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.0 | 1.69 ± 0.90 |
| mattcl | input-whyando | 0.7 ± 0.2 | 0.0 | 0.9 | 1.71 ± 0.92 |
| mattcl | input-mattcl | 1.1 ± 2.8 | 0.0 | 14.9 | 2.56 ± 6.87 |
| lanjian | input-mattcl | 1.4 ± 0.1 | 0.7 | 1.6 | 3.32 ± 1.63 |
| lanjian | input-whyando | 1.4 ± 0.2 | 0.7 | 1.7 | 3.32 ± 1.64 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.8 | 1.7 | 3.32 ± 1.64 |
| kcen | input-mattcl | 1.6 ± 0.3 | 0.8 | 2.4 | 3.91 ± 2.01 |
| kcen | input-lanjian | 1.6 ± 0.3 | 0.7 | 2.4 | 3.94 ± 2.04 |
| kcen | input-whyando | 1.6 ± 0.3 | 0.9 | 2.5 | 4.01 ± 2.08 |
| mattcl-py | input-lanjian | 21.2 ± 0.4 | 20.3 | 23.5 | 51.65 ± 24.83 |
| mattcl-py | input-whyando | 21.3 ± 0.5 | 20.2 | 23.7 | 51.71 ± 24.86 |
| mattcl-py | input-mattcl | 21.7 ± 2.2 | 20.3 | 32.6 | 52.81 ± 25.93 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|