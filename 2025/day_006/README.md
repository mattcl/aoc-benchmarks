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
| whyando | input-whyando | 0.4 ± 0.2 | 0.0 | 1.0 | 1.00 |
| whyando | input-mattcl | 0.4 ± 0.2 | 0.0 | 1.0 | 1.01 ± 0.57 |
| whyando | input-lanjian | 0.5 ± 0.1 | 0.0 | 0.9 | 1.08 ± 0.55 |
| mattcl | input-whyando | 0.7 ± 0.1 | 0.0 | 1.1 | 1.54 ± 0.71 |
| mattcl | input-lanjian | 0.7 ± 0.1 | 0.0 | 1.0 | 1.54 ± 0.69 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.3 | 1.56 ± 0.74 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.9 | 2.87 ± 1.25 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.6 | 2.0 | 2.92 ± 1.26 |
| lanjian | input-whyando | 1.3 ± 0.2 | 0.6 | 2.5 | 2.96 ± 1.33 |
| kcen | input-whyando | 1.5 ± 0.2 | 1.1 | 2.3 | 3.39 ± 1.45 |
| kcen | input-mattcl | 1.5 ± 0.2 | 0.9 | 2.5 | 3.41 ± 1.47 |
| kcen | input-lanjian | 1.5 ± 0.2 | 0.9 | 2.7 | 3.45 ± 1.50 |
| mattcl-py | input-mattcl | 20.6 ± 0.6 | 19.8 | 23.4 | 47.25 ± 19.28 |
| mattcl-py | input-lanjian | 20.6 ± 0.6 | 19.5 | 24.0 | 47.28 ± 19.29 |
| mattcl-py | input-whyando | 20.7 ± 0.7 | 19.5 | 24.4 | 47.51 ± 19.41 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|