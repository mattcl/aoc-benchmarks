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
| whyando | input-lanjian | 0.8 ± 0.1 | 0.0 | 1.3 | 1.00 |
| whyando | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.3 | 1.01 ± 0.25 |
| whyando | input-whyando | 0.9 ± 0.1 | 0.3 | 1.3 | 1.05 ± 0.24 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.8 | 1.29 ± 0.29 |
| mattcl | input-whyando | 1.0 ± 0.1 | 0.6 | 1.7 | 1.29 ± 0.27 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.4 | 1.7 | 1.33 ± 0.32 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.4 | 1.7 | 1.71 ± 0.36 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.3 | 2.2 | 1.71 ± 0.37 |
| lanjian | input-whyando | 1.4 ± 0.2 | 0.7 | 2.1 | 1.72 ± 0.34 |
| kcen | input-lanjian | 1.5 ± 0.3 | 0.5 | 2.5 | 1.84 ± 0.49 |
| kcen | input-whyando | 1.5 ± 0.2 | 0.9 | 2.4 | 1.90 ± 0.42 |
| kcen | input-mattcl | 1.6 ± 0.3 | 1.0 | 2.7 | 1.96 ± 0.51 |
| mattcl-py | input-lanjian | 20.6 ± 0.5 | 19.7 | 24.1 | 25.39 ± 4.22 |
| mattcl-py | input-mattcl | 20.7 ± 0.6 | 19.7 | 23.7 | 25.43 ± 4.24 |
| mattcl-py | input-whyando | 20.7 ± 0.5 | 20.0 | 23.4 | 25.52 ± 4.23 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|