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
| mattcl | input-lanjian | 0.6 ± 0.2 | 0.0 | 1.1 | 1.00 |
| mattcl | input-whyando | 0.7 ± 0.1 | 0.0 | 1.1 | 1.04 ± 0.34 |
| mattcl | input-mattcl | 0.7 ± 0.1 | 0.1 | 1.1 | 1.04 ± 0.35 |
| whyando | input-lanjian | 0.9 ± 0.1 | 0.5 | 1.4 | 1.37 ± 0.42 |
| whyando | input-whyando | 0.9 ± 0.2 | 0.0 | 1.4 | 1.40 ± 0.45 |
| whyando | input-mattcl | 1.0 ± 0.2 | 0.0 | 1.5 | 1.46 ± 0.48 |
| lanjian | input-whyando | 1.2 ± 0.3 | 0.2 | 1.6 | 1.90 ± 0.66 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.3 | 2.1 | 2.10 ± 0.66 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.6 | 1.8 | 2.11 ± 0.62 |
| kcen | input-whyando | 1.5 ± 0.2 | 1.0 | 2.6 | 2.34 ± 0.72 |
| kcen | input-lanjian | 1.5 ± 0.3 | 1.0 | 2.7 | 2.37 ± 0.74 |
| kcen | input-mattcl | 1.5 ± 0.3 | 1.0 | 2.4 | 2.38 ± 0.76 |
| mattcl-py | input-whyando | 20.5 ± 0.4 | 19.2 | 22.2 | 31.59 ± 8.40 |
| mattcl-py | input-lanjian | 20.6 ± 0.7 | 19.2 | 23.6 | 31.77 ± 8.48 |
| mattcl-py | input-mattcl | 20.6 ± 0.5 | 19.8 | 23.2 | 31.80 ± 8.46 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|