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
| whyando | input-whyando | 0.4 ± 0.2 | 0.0 | 1.2 | 1.00 |
| whyando | input-mattcl | 0.5 ± 0.2 | 0.0 | 1.1 | 1.27 ± 0.91 |
| whyando | input-lanjian | 0.5 ± 0.2 | 0.0 | 1.0 | 1.31 ± 0.91 |
| mattcl | input-whyando | 0.5 ± 0.4 | 0.0 | 4.3 | 1.38 ± 1.30 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.2 | 1.83 ± 1.18 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.4 | 2.01 ± 1.28 |
| lanjian | input-whyando | 0.9 ± 0.2 | 0.0 | 1.4 | 2.47 ± 1.55 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.5 | 2.51 ± 1.56 |
| lanjian | input-lanjian | 0.9 ± 0.1 | 0.4 | 1.4 | 2.55 ± 1.55 |
| kcen | input-lanjian | 1.6 ± 0.3 | 0.6 | 2.5 | 4.43 ± 2.75 |
| kcen | input-whyando | 1.6 ± 0.3 | 0.6 | 2.4 | 4.47 ± 2.78 |
| kcen | input-mattcl | 1.6 ± 0.3 | 0.9 | 3.0 | 4.51 ± 2.84 |
| mattcl-py | input-lanjian | 20.8 ± 0.6 | 19.8 | 23.8 | 57.69 ± 34.21 |
| mattcl-py | input-mattcl | 20.8 ± 0.7 | 19.3 | 24.2 | 57.74 ± 34.26 |
| mattcl-py | input-whyando | 20.9 ± 0.6 | 19.7 | 23.2 | 58.18 ± 34.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|