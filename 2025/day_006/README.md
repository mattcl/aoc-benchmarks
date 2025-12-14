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
| whyando | input-mattcl | 0.5 ± 0.2 | 0.0 | 0.9 | 1.00 |
| whyando | input-lanjian | 0.5 ± 0.1 | 0.0 | 1.0 | 1.03 ± 0.43 |
| whyando | input-whyando | 0.5 ± 0.1 | 0.0 | 0.9 | 1.06 ± 0.45 |
| mattcl | input-whyando | 0.7 ± 0.2 | 0.0 | 1.2 | 1.40 ± 0.58 |
| mattcl | input-lanjian | 0.7 ± 0.1 | 0.0 | 1.2 | 1.44 ± 0.55 |
| mattcl | input-mattcl | 0.7 ± 0.1 | 0.2 | 1.4 | 1.47 ± 0.57 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.1 | 1.9 | 1.96 ± 0.75 |
| lanjian | input-lanjian | 1.0 ± 0.1 | 0.4 | 1.5 | 1.97 ± 0.71 |
| lanjian | input-whyando | 1.0 ± 0.1 | 0.5 | 1.5 | 2.00 ± 0.72 |
| kcen | input-mattcl | 1.6 ± 0.3 | 1.2 | 2.5 | 3.20 ± 1.21 |
| kcen | input-whyando | 1.6 ± 0.3 | 0.9 | 2.7 | 3.25 ± 1.24 |
| kcen | input-lanjian | 1.7 ± 0.3 | 0.9 | 2.8 | 3.35 ± 1.31 |
| mattcl-py | input-lanjian | 20.8 ± 0.7 | 19.8 | 23.7 | 42.33 ± 13.99 |
| mattcl-py | input-mattcl | 20.8 ± 0.7 | 20.0 | 25.1 | 42.34 ± 13.99 |
| mattcl-py | input-whyando | 20.9 ± 0.7 | 19.9 | 23.6 | 42.40 ± 14.01 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|