# Day 1 benchmarks

[link to problem](https://adventofcode.com/2025/day/1)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 1)

- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-mattcl | 0.6 ± 0.2 | 0.0 | 1.1 | 1.00 |
| whyando | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.0 | 1.06 ± 0.39 |
| whyando | input-whyando | 0.7 ± 0.1 | 0.0 | 1.2 | 1.07 ± 0.38 |
| mattcl | input-whyando | 1.1 ± 0.2 | 0.2 | 1.9 | 1.77 ± 0.61 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 2.0 | 1.81 ± 0.62 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.6 | 2.4 | 1.93 ± 0.66 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.6 | 2.2 | 1.93 ± 0.66 |
| lanjian | input-whyando | 1.3 ± 0.3 | 0.5 | 2.5 | 2.05 ± 0.72 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.4 | 2.1 | 2.06 ± 0.70 |
| mattcl-py | input-whyando | 18.0 ± 0.5 | 16.7 | 20.7 | 27.86 ± 8.11 |
| mattcl-py | input-mattcl | 18.1 ± 0.5 | 17.3 | 21.3 | 27.90 ± 8.12 |
| mattcl-py | input-lanjian | 18.1 ± 0.7 | 17.1 | 21.3 | 28.05 ± 8.21 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1158</pre>|<pre>6860</pre>|
|input-mattcl|<pre>1084</pre>|<pre>6475</pre>|
|input-whyando|<pre>1120</pre>|<pre>6554</pre>|