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
| whyando | input-mattcl | 0.5 ± 0.2 | 0.0 | 1.0 | 1.07 ± 0.55 |
| whyando | input-whyando | 0.5 ± 0.2 | 0.0 | 0.9 | 1.08 ± 0.53 |
| mattcl | input-whyando | 0.8 ± 0.2 | 0.3 | 1.4 | 1.92 ± 0.77 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.3 | 1.5 | 1.97 ± 0.81 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.3 | 1.6 | 1.99 ± 0.78 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.5 | 2.1 | 2.97 ± 1.19 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.6 | 2.1 | 2.97 ± 1.18 |
| lanjian | input-whyando | 1.3 ± 0.2 | 0.5 | 2.1 | 3.02 ± 1.18 |
| kcen | input-mattcl | 1.5 ± 0.3 | 0.6 | 2.4 | 3.42 ± 1.37 |
| kcen | input-lanjian | 1.6 ± 0.3 | 1.0 | 2.9 | 3.57 ± 1.46 |
| kcen | input-whyando | 1.6 ± 0.3 | 1.0 | 2.8 | 3.66 ± 1.52 |
| mattcl-py | input-mattcl | 20.7 ± 0.7 | 19.7 | 23.8 | 46.93 ± 16.84 |
| mattcl-py | input-lanjian | 20.7 ± 0.7 | 19.5 | 24.0 | 46.98 ± 16.86 |
| mattcl-py | input-whyando | 20.8 ± 0.7 | 19.7 | 23.6 | 47.13 ± 16.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|