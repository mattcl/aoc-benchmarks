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
| whyando | input-mattcl | 0.5 ± 0.2 | 0.0 | 1.0 | 1.00 |
| whyando | input-whyando | 0.5 ± 0.2 | 0.0 | 0.9 | 1.01 ± 0.52 |
| whyando | input-lanjian | 0.5 ± 0.2 | 0.0 | 1.0 | 1.02 ± 0.54 |
| mattcl | input-mattcl | 0.7 ± 0.1 | 0.0 | 1.2 | 1.44 ± 0.64 |
| mattcl | input-whyando | 0.7 ± 0.2 | 0.0 | 1.1 | 1.47 ± 0.66 |
| mattcl | input-lanjian | 0.7 ± 0.1 | 0.0 | 1.1 | 1.50 ± 0.64 |
| lanjian | input-whyando | 1.3 ± 0.2 | 0.1 | 2.1 | 2.79 ± 1.19 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.5 | 2.1 | 2.84 ± 1.20 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.5 | 2.1 | 2.84 ± 1.17 |
| kcen | input-lanjian | 1.5 ± 0.2 | 0.9 | 2.5 | 3.23 ± 1.34 |
| kcen | input-mattcl | 1.5 ± 0.2 | 1.0 | 2.4 | 3.28 ± 1.34 |
| kcen | input-whyando | 1.6 ± 0.3 | 1.0 | 2.9 | 3.41 ± 1.46 |
| mattcl-py | input-lanjian | 20.6 ± 0.5 | 19.4 | 23.1 | 44.43 ± 17.05 |
| mattcl-py | input-mattcl | 20.6 ± 0.5 | 19.6 | 23.8 | 44.46 ± 17.07 |
| mattcl-py | input-whyando | 20.8 ± 0.6 | 19.4 | 24.0 | 44.89 ± 17.25 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|