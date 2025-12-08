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
| whyando | input-mattcl | 0.4 ± 0.2 | 0.0 | 0.7 | 1.00 |
| whyando | input-whyando | 0.4 ± 0.2 | 0.0 | 0.7 | 1.21 ± 0.79 |
| whyando | input-lanjian | 0.5 ± 0.2 | 0.0 | 1.1 | 1.28 ± 0.83 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.0 | 0.9 | 1.77 ± 1.10 |
| mattcl | input-whyando | 0.7 ± 0.2 | 0.0 | 0.9 | 1.86 ± 1.10 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.1 | 0.9 | 1.87 ± 1.10 |
| lanjian | input-whyando | 1.3 ± 0.2 | 0.6 | 1.6 | 3.46 ± 1.93 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.3 | 1.6 | 3.59 ± 2.01 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.2 | 1.6 | 3.61 ± 2.01 |
| kcen | input-mattcl | 1.6 ± 0.4 | 0.7 | 2.6 | 4.42 ± 2.58 |
| kcen | input-whyando | 1.6 ± 0.3 | 0.7 | 2.5 | 4.42 ± 2.56 |
| kcen | input-lanjian | 1.7 ± 0.3 | 0.9 | 2.5 | 4.55 ± 2.63 |
| mattcl-py | input-whyando | 21.2 ± 0.6 | 20.2 | 23.7 | 57.33 ± 31.15 |
| mattcl-py | input-lanjian | 21.3 ± 0.5 | 20.6 | 24.4 | 57.56 ± 31.28 |
| mattcl-py | input-mattcl | 22.7 ± 3.7 | 20.0 | 34.2 | 61.41 ± 34.80 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|