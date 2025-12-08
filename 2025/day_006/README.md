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
| whyando | input-mattcl | 0.5 ± 0.1 | 0.0 | 1.2 | 1.01 ± 0.52 |
| whyando | input-lanjian | 0.5 ± 0.2 | 0.0 | 1.0 | 1.05 ± 0.58 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.3 | 1.4 | 1.82 ± 0.81 |
| mattcl | input-mattcl | 0.8 ± 0.1 | 0.0 | 1.4 | 1.88 ± 0.82 |
| mattcl | input-whyando | 0.9 ± 0.2 | 0.0 | 1.5 | 1.92 ± 0.89 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.5 | 2.1 | 2.80 ± 1.23 |
| lanjian | input-whyando | 1.3 ± 0.2 | 0.6 | 2.1 | 2.85 ± 1.24 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.7 | 2.0 | 2.86 ± 1.25 |
| kcen | input-lanjian | 1.5 ± 0.2 | 0.7 | 2.7 | 3.32 ± 1.44 |
| kcen | input-mattcl | 1.5 ± 0.3 | 1.0 | 2.6 | 3.43 ± 1.50 |
| kcen | input-whyando | 1.6 ± 0.4 | 0.6 | 3.0 | 3.60 ± 1.64 |
| mattcl-py | input-mattcl | 20.7 ± 0.6 | 19.7 | 24.2 | 46.04 ± 18.55 |
| mattcl-py | input-lanjian | 20.7 ± 0.6 | 19.6 | 23.6 | 46.17 ± 18.60 |
| mattcl-py | input-whyando | 20.9 ± 0.7 | 19.9 | 23.8 | 46.58 ± 18.78 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|