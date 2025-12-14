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
| whyando | input-lanjian | 0.5 ± 0.1 | 0.0 | 1.0 | 1.00 |
| whyando | input-whyando | 0.5 ± 0.2 | 0.0 | 1.0 | 1.02 ± 0.43 |
| whyando | input-mattcl | 0.5 ± 0.2 | 0.0 | 1.0 | 1.05 ± 0.45 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.3 | 1.43 ± 0.54 |
| mattcl | input-whyando | 0.7 ± 0.2 | 0.0 | 1.2 | 1.45 ± 0.54 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.2 | 1.48 ± 0.56 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.5 | 1.88 ± 0.65 |
| lanjian | input-whyando | 1.0 ± 0.2 | 0.4 | 1.6 | 1.92 ± 0.65 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.5 | 1.6 | 1.97 ± 0.67 |
| kcen | input-lanjian | 1.5 ± 0.2 | 0.9 | 2.4 | 3.08 ± 1.03 |
| kcen | input-mattcl | 1.6 ± 0.3 | 1.0 | 2.4 | 3.17 ± 1.12 |
| kcen | input-whyando | 1.6 ± 0.3 | 0.7 | 2.8 | 3.21 ± 1.16 |
| mattcl-py | input-whyando | 20.8 ± 0.5 | 19.8 | 23.3 | 41.86 ± 12.51 |
| mattcl-py | input-lanjian | 20.9 ± 0.5 | 20.0 | 23.4 | 42.01 ± 12.56 |
| mattcl-py | input-mattcl | 20.9 ± 0.9 | 19.5 | 24.4 | 42.09 ± 12.65 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|