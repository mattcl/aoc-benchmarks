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
| whyando | input-lanjian | 0.5 ± 0.2 | 0.0 | 0.7 | 1.00 |
| whyando | input-mattcl | 0.5 ± 0.2 | 0.0 | 0.8 | 1.03 ± 0.53 |
| whyando | input-whyando | 0.5 ± 0.2 | 0.0 | 0.8 | 1.04 ± 0.56 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.0 | 1.49 ± 0.65 |
| mattcl | input-whyando | 0.7 ± 0.2 | 0.0 | 1.0 | 1.50 ± 0.69 |
| mattcl | input-mattcl | 0.7 ± 0.1 | 0.2 | 0.9 | 1.51 ± 0.64 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.2 | 1.6 | 2.72 ± 1.14 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.6 | 1.6 | 2.74 ± 1.12 |
| kcen | input-lanjian | 1.6 ± 0.3 | 0.9 | 2.5 | 3.21 ± 1.34 |
| kcen | input-mattcl | 1.6 ± 0.3 | 0.9 | 2.5 | 3.34 ± 1.41 |
| lanjian | input-whyando | 1.7 ± 1.8 | 0.4 | 19.0 | 3.45 ± 3.88 |
| kcen | input-whyando | 1.8 ± 1.8 | 0.6 | 15.1 | 3.75 ± 3.84 |
| mattcl-py | input-mattcl | 21.0 ± 0.5 | 20.0 | 23.7 | 42.71 ± 16.30 |
| mattcl-py | input-lanjian | 21.1 ± 0.6 | 20.0 | 23.3 | 42.80 ± 16.35 |
| mattcl-py | input-whyando | 21.3 ± 0.5 | 20.5 | 24.0 | 43.23 ± 16.50 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|