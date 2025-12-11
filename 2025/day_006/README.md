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
| whyando | input-whyando | 0.5 ± 0.2 | 0.0 | 0.9 | 1.00 |
| whyando | input-lanjian | 0.5 ± 0.1 | 0.0 | 1.0 | 1.09 ± 0.50 |
| whyando | input-mattcl | 0.5 ± 0.2 | 0.0 | 1.3 | 1.15 ± 0.58 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.1 | 1.43 ± 0.62 |
| mattcl | input-whyando | 0.7 ± 0.2 | 0.0 | 1.3 | 1.45 ± 0.64 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.5 | 1.50 ± 0.67 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.0 | 1.6 | 2.00 ± 0.84 |
| lanjian | input-whyando | 0.9 ± 0.2 | 0.4 | 1.7 | 2.02 ± 0.81 |
| lanjian | input-lanjian | 1.0 ± 0.1 | 0.4 | 1.4 | 2.05 ± 0.80 |
| kcen | input-mattcl | 1.5 ± 0.3 | 0.5 | 2.7 | 3.26 ± 1.33 |
| kcen | input-lanjian | 1.6 ± 0.3 | 1.0 | 2.5 | 3.47 ± 1.40 |
| kcen | input-whyando | 1.6 ± 0.3 | 0.7 | 2.4 | 3.50 ± 1.43 |
| mattcl-py | input-mattcl | 20.8 ± 0.5 | 19.9 | 22.8 | 44.99 ± 16.27 |
| mattcl-py | input-whyando | 20.9 ± 0.7 | 19.7 | 24.2 | 45.19 ± 16.38 |
| mattcl-py | input-lanjian | 21.0 ± 1.0 | 19.7 | 29.7 | 45.41 ± 16.53 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|