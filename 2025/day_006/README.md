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
| whyando | input-lanjian | 0.4 ± 0.2 | 0.0 | 1.0 | 1.00 |
| whyando | input-whyando | 0.5 ± 0.2 | 0.0 | 1.0 | 1.06 ± 0.57 |
| whyando | input-mattcl | 0.5 ± 0.2 | 0.0 | 1.0 | 1.11 ± 0.55 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.3 | 1.48 ± 0.69 |
| mattcl | input-whyando | 0.7 ± 0.1 | 0.1 | 0.9 | 1.52 ± 0.68 |
| mattcl | input-mattcl | 0.7 ± 0.1 | 0.0 | 0.9 | 1.54 ± 0.68 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.5 | 1.7 | 3.04 ± 1.27 |
| lanjian | input-whyando | 1.4 ± 0.2 | 0.7 | 1.8 | 3.08 ± 1.26 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.0 | 3.09 ± 1.27 |
| kcen | input-whyando | 1.6 ± 0.3 | 0.7 | 2.8 | 3.47 ± 1.50 |
| kcen | input-mattcl | 1.6 ± 0.2 | 1.0 | 2.3 | 3.47 ± 1.46 |
| kcen | input-lanjian | 1.6 ± 0.3 | 1.0 | 2.8 | 3.57 ± 1.58 |
| mattcl-py | input-mattcl | 20.6 ± 0.5 | 19.5 | 23.4 | 45.81 ± 18.01 |
| mattcl-py | input-lanjian | 20.6 ± 0.7 | 19.8 | 23.7 | 45.87 ± 18.07 |
| mattcl-py | input-whyando | 20.7 ± 0.6 | 19.4 | 23.6 | 46.00 ± 18.11 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|