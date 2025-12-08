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
| whyando | input-mattcl | 0.4 ± 0.2 | 0.0 | 0.7 | 1.00 |
| whyando | input-lanjian | 0.5 ± 0.2 | 0.0 | 0.7 | 1.04 ± 0.58 |
| whyando | input-whyando | 0.5 ± 0.1 | 0.0 | 0.7 | 1.10 ± 0.56 |
| mattcl | input-whyando | 0.8 ± 0.2 | 0.3 | 1.7 | 1.94 ± 0.88 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.3 | 1.1 | 1.97 ± 0.86 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.0 | 1.2 | 2.03 ± 0.93 |
| lanjian | input-whyando | 1.3 ± 0.2 | 0.3 | 1.5 | 2.90 ± 1.30 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.5 | 1.5 | 2.97 ± 1.29 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.6 | 1.5 | 2.99 ± 1.29 |
| kcen | input-whyando | 1.6 ± 0.3 | 0.8 | 2.5 | 3.69 ± 1.68 |
| kcen | input-mattcl | 1.7 ± 0.3 | 0.8 | 2.6 | 3.88 ± 1.77 |
| kcen | input-lanjian | 1.7 ± 0.4 | 1.0 | 2.6 | 4.03 ± 1.84 |
| mattcl-py | input-mattcl | 21.2 ± 0.6 | 20.2 | 23.8 | 48.91 ± 19.97 |
| mattcl-py | input-whyando | 22.6 ± 3.7 | 20.4 | 38.2 | 52.12 ± 22.87 |
| mattcl-py | input-lanjian | 22.8 ± 3.6 | 20.1 | 34.0 | 52.40 ± 22.93 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>4405895212738</pre>|<pre>7450962489289</pre>|
|input-mattcl|<pre>6299564383938</pre>|<pre>11950004808442</pre>|
|input-whyando|<pre>3785892992137</pre>|<pre>7669802156452</pre>|