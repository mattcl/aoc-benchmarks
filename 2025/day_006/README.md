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
| whyando | input-mattcl | 0.4 ± 0.2 | 0.0 | 1.1 | 1.00 |
| whyando | input-lanjian | 0.4 ± 0.2 | 0.0 | 1.1 | 1.00 ± 0.58 |
| whyando | input-whyando | 0.5 ± 0.1 | 0.0 | 0.9 | 1.09 ± 0.56 |
| mattcl | input-mattcl | 0.6 ± 0.2 | 0.0 | 1.0 | 1.42 ± 0.72 |
| mattcl | input-lanjian | 0.7 ± 0.1 | 0.2 | 1.1 | 1.57 ± 0.72 |
| mattcl | input-whyando | 0.7 ± 0.1 | 0.1 | 1.3 | 1.61 ± 0.74 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.6 | 2.6 | 2.93 ± 1.28 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.5 | 2.5 | 3.00 ± 1.32 |
| lanjian | input-whyando | 1.3 ± 0.2 | 0.6 | 2.0 | 3.01 ± 1.31 |
| kcen | input-mattcl | 1.5 ± 0.2 | 0.7 | 2.4 | 3.38 ± 1.44 |
| kcen | input-lanjian | 1.5 ± 0.3 | 0.5 | 2.7 | 3.54 ± 1.57 |
| kcen | input-whyando | 1.5 ± 0.3 | 0.7 | 2.9 | 3.59 ± 1.59 |
| mattcl-py | input-lanjian | 20.6 ± 0.6 | 19.5 | 23.6 | 47.86 ± 19.40 |
| mattcl-py | input-whyando | 20.6 ± 0.5 | 19.5 | 23.5 | 47.87 ± 19.40 |
| mattcl-py | input-mattcl | 20.6 ± 0.7 | 19.7 | 23.4 | 47.92 ± 19.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|