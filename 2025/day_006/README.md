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
| mattcl | input-lanjian | 0.4 ± 0.3 | 0.0 | 1.1 | 1.00 |
| whyando | input-mattcl | 0.5 ± 0.2 | 0.0 | 1.0 | 1.39 ± 1.20 |
| whyando | input-whyando | 0.5 ± 0.2 | 0.0 | 1.0 | 1.41 ± 1.22 |
| whyando | input-lanjian | 0.5 ± 0.2 | 0.0 | 1.0 | 1.41 ± 1.21 |
| mattcl | input-whyando | 0.7 ± 0.2 | 0.0 | 1.3 | 1.97 ± 1.65 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.2 | 2.01 ± 1.66 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.6 | 2.59 ± 2.13 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.6 | 2.66 ± 2.18 |
| lanjian | input-whyando | 1.0 ± 0.2 | 0.4 | 1.8 | 2.71 ± 2.22 |
| kcen | input-lanjian | 1.3 ± 0.4 | 0.5 | 2.4 | 3.57 ± 3.01 |
| kcen | input-whyando | 1.6 ± 0.3 | 1.0 | 2.8 | 4.37 ± 3.59 |
| kcen | input-mattcl | 1.7 ± 0.3 | 1.0 | 2.7 | 4.43 ± 3.64 |
| mattcl-py | input-whyando | 20.8 ± 0.5 | 19.7 | 23.4 | 55.66 ± 44.51 |
| mattcl-py | input-mattcl | 20.9 ± 0.6 | 19.8 | 23.7 | 55.74 ± 44.57 |
| mattcl-py | input-lanjian | 21.0 ± 0.6 | 20.0 | 23.6 | 55.97 ± 44.76 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|