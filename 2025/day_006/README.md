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
| whyando | input-mattcl | 0.4 ± 0.2 | 0.0 | 1.0 | 1.00 |
| whyando | input-lanjian | 0.5 ± 0.2 | 0.0 | 0.8 | 1.19 ± 0.80 |
| whyando | input-whyando | 0.5 ± 0.1 | 0.0 | 1.1 | 1.33 ± 0.87 |
| mattcl | input-whyando | 0.6 ± 0.2 | 0.0 | 1.1 | 1.62 ± 1.12 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.3 | 1.75 ± 1.15 |
| mattcl | input-mattcl | 0.7 ± 0.1 | 0.0 | 1.1 | 1.83 ± 1.14 |
| lanjian | input-whyando | 1.3 ± 0.3 | 0.2 | 1.8 | 3.38 ± 2.11 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.6 | 1.8 | 3.55 ± 2.12 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.8 | 1.9 | 3.56 ± 2.13 |
| kcen | input-whyando | 1.4 ± 0.4 | 0.5 | 2.5 | 3.59 ± 2.31 |
| kcen | input-mattcl | 1.5 ± 0.2 | 0.6 | 2.4 | 3.70 ± 2.23 |
| kcen | input-lanjian | 1.6 ± 0.3 | 0.7 | 2.7 | 4.08 ± 2.52 |
| mattcl-py | input-mattcl | 20.5 ± 0.7 | 19.1 | 23.7 | 52.07 ± 30.65 |
| mattcl-py | input-whyando | 20.7 ± 0.6 | 19.6 | 23.6 | 52.47 ± 30.87 |
| mattcl-py | input-lanjian | 20.7 ± 0.7 | 19.7 | 24.2 | 52.65 ± 30.99 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|