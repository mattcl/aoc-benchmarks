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
| whyando | input-mattcl | 0.3 ± 0.4 | 0.0 | 5.0 | 1.00 |
| whyando | input-whyando | 0.5 ± 0.2 | 0.0 | 1.1 | 1.64 ± 2.30 |
| whyando | input-lanjian | 0.5 ± 0.2 | 0.0 | 1.1 | 1.64 ± 2.33 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.2 | 1.2 | 2.24 ± 3.09 |
| mattcl | input-whyando | 0.7 ± 0.2 | 0.0 | 1.3 | 2.33 ± 3.22 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.0 | 1.3 | 2.39 ± 3.29 |
| lanjian | input-mattcl | 1.0 ± 0.1 | 0.4 | 1.3 | 3.03 ± 4.15 |
| lanjian | input-whyando | 1.0 ± 0.1 | 0.3 | 1.6 | 3.06 ± 4.19 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.4 | 1.7 | 3.13 ± 4.30 |
| kcen | input-whyando | 1.6 ± 0.3 | 0.5 | 2.7 | 4.97 ± 6.84 |
| kcen | input-lanjian | 1.6 ± 0.3 | 0.7 | 2.7 | 4.99 ± 6.86 |
| kcen | input-mattcl | 1.6 ± 0.3 | 1.0 | 2.8 | 5.13 ± 7.07 |
| mattcl-py | input-lanjian | 20.8 ± 0.7 | 19.4 | 23.9 | 65.61 ± 89.47 |
| mattcl-py | input-whyando | 20.8 ± 0.5 | 19.6 | 23.4 | 65.63 ± 89.49 |
| mattcl-py | input-mattcl | 20.8 ± 0.6 | 19.7 | 23.5 | 65.64 ± 89.50 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|