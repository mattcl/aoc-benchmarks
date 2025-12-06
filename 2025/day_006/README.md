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
| whyando | input-lanjian | 0.5 ± 0.2 | 0.0 | 1.1 | 1.00 |
| whyando | input-mattcl | 0.5 ± 0.2 | 0.0 | 1.0 | 1.02 ± 0.44 |
| whyando | input-whyando | 0.5 ± 0.2 | 0.0 | 1.1 | 1.04 ± 0.45 |
| mattcl | input-lanjian | 0.5 ± 0.3 | 0.0 | 1.1 | 1.07 ± 0.65 |
| mattcl | input-whyando | 0.7 ± 0.1 | 0.1 | 1.1 | 1.41 ± 0.53 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.3 | 1.3 | 1.47 ± 0.56 |
| lanjian | input-lanjian | 1.1 ± 0.3 | 0.1 | 2.1 | 2.25 ± 0.95 |
| kcen | input-lanjian | 1.3 ± 0.3 | 0.4 | 2.1 | 2.59 ± 1.01 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.6 | 2.5 | 2.65 ± 0.98 |
| lanjian | input-whyando | 1.4 ± 0.2 | 0.5 | 2.0 | 2.71 ± 0.94 |
| kcen | input-mattcl | 1.4 ± 0.4 | 0.5 | 3.0 | 2.85 ± 1.16 |
| kcen | input-whyando | 1.6 ± 0.3 | 1.0 | 2.7 | 3.20 ± 1.16 |
| mattcl-py | input-mattcl | 20.7 ± 0.6 | 19.6 | 23.8 | 40.88 ± 13.05 |
| mattcl-py | input-whyando | 20.8 ± 0.7 | 19.3 | 23.4 | 40.95 ± 13.09 |
| mattcl-py | input-lanjian | 20.9 ± 0.6 | 19.9 | 23.7 | 41.21 ± 13.16 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|