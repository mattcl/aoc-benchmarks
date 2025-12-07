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
| whyando | input-lanjian | 0.5 ± 0.2 | 0.0 | 1.1 | 1.00 |
| whyando | input-whyando | 0.5 ± 0.2 | 0.0 | 1.1 | 1.03 ± 0.54 |
| whyando | input-mattcl | 0.5 ± 0.1 | 0.0 | 1.0 | 1.03 ± 0.50 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.3 | 1.42 ± 0.63 |
| mattcl | input-whyando | 0.7 ± 0.2 | 0.0 | 1.1 | 1.43 ± 0.66 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.3 | 1.54 ± 0.71 |
| lanjian | input-lanjian | 1.2 ± 0.3 | 0.1 | 2.1 | 2.62 ± 1.24 |
| lanjian | input-whyando | 1.4 ± 0.1 | 0.8 | 1.7 | 3.00 ± 1.17 |
| lanjian | input-mattcl | 1.4 ± 0.1 | 0.8 | 2.0 | 3.02 ± 1.17 |
| kcen | input-mattcl | 1.5 ± 0.3 | 0.9 | 2.6 | 3.36 ± 1.38 |
| kcen | input-lanjian | 1.6 ± 0.3 | 1.0 | 2.7 | 3.44 ± 1.48 |
| kcen | input-whyando | 1.6 ± 0.3 | 0.9 | 2.6 | 3.51 ± 1.50 |
| mattcl-py | input-mattcl | 20.7 ± 0.6 | 19.6 | 23.5 | 44.96 ± 16.98 |
| mattcl-py | input-lanjian | 20.8 ± 0.6 | 19.7 | 23.4 | 45.18 ± 17.06 |
| mattcl-py | input-whyando | 20.8 ± 0.7 | 19.5 | 24.1 | 45.19 ± 17.09 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|