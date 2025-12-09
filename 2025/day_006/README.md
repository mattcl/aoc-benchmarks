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
| whyando | input-mattcl | 0.4 ± 0.2 | 0.0 | 1.0 | 1.00 |
| whyando | input-lanjian | 0.5 ± 0.2 | 0.0 | 1.0 | 1.09 ± 0.55 |
| whyando | input-whyando | 0.5 ± 0.2 | 0.0 | 1.2 | 1.11 ± 0.55 |
| mattcl | input-whyando | 0.7 ± 0.2 | 0.0 | 1.1 | 1.51 ± 0.69 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.1 | 1.53 ± 0.70 |
| mattcl | input-mattcl | 0.7 ± 0.1 | 0.3 | 1.1 | 1.63 ± 0.70 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.7 | 2.05 ± 0.92 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.4 | 1.4 | 2.10 ± 0.89 |
| lanjian | input-whyando | 1.0 ± 0.2 | 0.2 | 1.5 | 2.13 ± 0.92 |
| kcen | input-lanjian | 1.5 ± 0.3 | 0.6 | 2.3 | 3.41 ± 1.50 |
| kcen | input-mattcl | 1.6 ± 0.3 | 0.9 | 2.8 | 3.61 ± 1.60 |
| kcen | input-whyando | 1.6 ± 0.3 | 1.1 | 2.7 | 3.61 ± 1.60 |
| mattcl-py | input-mattcl | 20.7 ± 0.4 | 19.7 | 22.1 | 46.33 ± 18.34 |
| mattcl-py | input-lanjian | 20.9 ± 0.8 | 19.9 | 24.5 | 46.76 ± 18.57 |
| mattcl-py | input-whyando | 20.9 ± 0.8 | 20.0 | 24.5 | 46.90 ± 18.64 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|