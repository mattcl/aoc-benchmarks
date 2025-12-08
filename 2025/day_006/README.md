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
| whyando | input-whyando | 0.5 ± 0.2 | 0.0 | 0.9 | 1.00 |
| whyando | input-lanjian | 0.5 ± 0.2 | 0.0 | 1.0 | 1.03 ± 0.53 |
| whyando | input-mattcl | 0.5 ± 0.2 | 0.0 | 1.1 | 1.03 ± 0.56 |
| mattcl | input-lanjian | 0.8 ± 0.1 | 0.3 | 1.3 | 1.78 ± 0.79 |
| mattcl | input-whyando | 0.8 ± 0.1 | 0.3 | 1.3 | 1.80 ± 0.78 |
| mattcl | input-mattcl | 0.8 ± 0.1 | 0.0 | 1.3 | 1.81 ± 0.80 |
| lanjian | input-whyando | 1.3 ± 0.2 | 0.5 | 2.1 | 2.79 ± 1.22 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.6 | 2.1 | 2.79 ± 1.23 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.5 | 2.0 | 2.83 ± 1.25 |
| kcen | input-lanjian | 1.6 ± 0.3 | 0.9 | 2.4 | 3.38 ± 1.50 |
| kcen | input-whyando | 1.6 ± 0.3 | 0.9 | 2.6 | 3.51 ± 1.57 |
| kcen | input-mattcl | 1.6 ± 0.3 | 0.9 | 2.7 | 3.53 ± 1.62 |
| mattcl-py | input-lanjian | 20.8 ± 0.7 | 19.9 | 23.8 | 45.10 ± 18.41 |
| mattcl-py | input-mattcl | 20.9 ± 0.8 | 19.6 | 24.5 | 45.22 ± 18.47 |
| mattcl-py | input-whyando | 20.9 ± 0.7 | 19.9 | 23.9 | 45.28 ± 18.47 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|