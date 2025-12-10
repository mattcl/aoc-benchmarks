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
| whyando | input-lanjian | 0.3 ± 0.2 | 0.0 | 1.0 | 1.00 |
| mattcl | input-mattcl | 0.4 ± 0.3 | 0.0 | 0.9 | 1.26 ± 1.33 |
| lanjian | input-mattcl | 0.5 ± 0.3 | 0.0 | 1.1 | 1.52 ± 1.58 |
| whyando | input-whyando | 0.5 ± 0.2 | 0.0 | 1.2 | 1.61 ± 1.38 |
| whyando | input-mattcl | 0.5 ± 0.2 | 0.0 | 1.3 | 1.64 ± 1.38 |
| mattcl | input-whyando | 0.7 ± 0.2 | 0.2 | 1.1 | 2.28 ± 1.87 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.7 | 2.33 ± 1.96 |
| lanjian | input-whyando | 0.9 ± 0.1 | 0.3 | 1.5 | 2.96 ± 2.39 |
| lanjian | input-lanjian | 1.0 ± 0.1 | 0.4 | 1.5 | 3.06 ± 2.46 |
| kcen | input-mattcl | 1.1 ± 0.4 | 0.5 | 1.9 | 3.59 ± 3.09 |
| kcen | input-whyando | 1.6 ± 0.3 | 1.0 | 2.6 | 5.02 ± 4.07 |
| kcen | input-lanjian | 1.6 ± 0.4 | 0.9 | 2.7 | 5.22 ± 4.27 |
| mattcl-py | input-mattcl | 20.8 ± 0.6 | 19.9 | 24.3 | 66.43 ± 52.47 |
| mattcl-py | input-whyando | 20.8 ± 0.5 | 19.5 | 23.5 | 66.44 ± 52.47 |
| mattcl-py | input-lanjian | 20.8 ± 1.0 | 19.7 | 30.0 | 66.70 ± 52.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|