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
| whyando | input-lanjian | 0.5 ± 0.2 | 0.0 | 1.0 | 1.00 |
| whyando | input-whyando | 0.5 ± 0.2 | 0.0 | 1.0 | 1.01 ± 0.50 |
| whyando | input-mattcl | 0.5 ± 0.2 | 0.0 | 1.1 | 1.02 ± 0.52 |
| mattcl | input-lanjian | 0.7 ± 0.1 | 0.1 | 1.1 | 1.45 ± 0.59 |
| mattcl | input-mattcl | 0.7 ± 0.1 | 0.0 | 1.0 | 1.46 ± 0.57 |
| mattcl | input-whyando | 0.7 ± 0.2 | 0.0 | 1.3 | 1.47 ± 0.60 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.5 | 2.5 | 2.83 ± 1.05 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.6 | 2.0 | 2.86 ± 1.06 |
| lanjian | input-whyando | 1.3 ± 0.2 | 0.5 | 2.0 | 2.93 ± 1.06 |
| kcen | input-whyando | 1.4 ± 0.0 | 1.3 | 1.5 | 3.08 ± 1.03 |
| kcen | input-lanjian | 1.5 ± 0.3 | 0.6 | 2.7 | 3.37 ± 1.28 |
| kcen | input-mattcl | 1.6 ± 0.3 | 0.6 | 2.7 | 3.51 ± 1.38 |
| mattcl-py | input-mattcl | 20.7 ± 0.5 | 19.7 | 22.6 | 45.58 ± 15.28 |
| mattcl-py | input-lanjian | 20.7 ± 0.7 | 19.8 | 24.3 | 45.66 ± 15.33 |
| mattcl-py | input-whyando | 20.7 ± 0.7 | 19.4 | 23.9 | 45.69 ± 15.35 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|