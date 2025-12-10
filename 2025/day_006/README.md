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
| whyando | input-mattcl | 0.5 ± 0.2 | 0.0 | 1.1 | 1.00 |
| whyando | input-lanjian | 0.5 ± 0.2 | 0.0 | 1.1 | 1.05 ± 0.52 |
| whyando | input-whyando | 0.5 ± 0.1 | 0.0 | 1.0 | 1.07 ± 0.52 |
| mattcl | input-lanjian | 0.7 ± 0.1 | 0.0 | 1.1 | 1.47 ± 0.64 |
| mattcl | input-whyando | 0.7 ± 0.2 | 0.2 | 1.2 | 1.51 ± 0.69 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.4 | 1.57 ± 0.71 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.0 | 1.6 | 2.04 ± 0.84 |
| lanjian | input-whyando | 0.9 ± 0.2 | 0.0 | 1.5 | 2.06 ± 0.87 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.5 | 2.5 | 2.07 ± 0.87 |
| kcen | input-whyando | 1.6 ± 0.3 | 1.0 | 2.9 | 3.49 ± 1.50 |
| kcen | input-mattcl | 1.6 ± 0.3 | 1.0 | 2.7 | 3.57 ± 1.54 |
| kcen | input-lanjian | 1.6 ± 0.4 | 0.8 | 2.8 | 3.60 ± 1.59 |
| mattcl-py | input-lanjian | 20.9 ± 0.7 | 19.8 | 24.2 | 45.57 ± 17.45 |
| mattcl-py | input-whyando | 21.0 ± 0.7 | 19.9 | 24.6 | 45.74 ± 17.51 |
| mattcl-py | input-mattcl | 21.0 ± 0.8 | 19.7 | 24.2 | 45.86 ± 17.57 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|