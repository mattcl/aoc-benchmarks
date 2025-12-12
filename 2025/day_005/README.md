# Day 5 benchmarks

[link to problem](https://adventofcode.com/2025/day/5)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 5)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-mattcl | 0.6 ± 0.2 | 0.0 | 1.4 | 1.00 |
| mattcl | input-whyando | 0.6 ± 0.2 | 0.0 | 1.1 | 1.05 ± 0.42 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.1 | 1.07 ± 0.44 |
| whyando | input-whyando | 0.7 ± 0.2 | 0.0 | 1.3 | 1.08 ± 0.44 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.2 | 1.1 | 1.08 ± 0.44 |
| whyando | input-lanjian | 0.7 ± 0.1 | 0.2 | 1.1 | 1.13 ± 0.42 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.4 | 1.5 | 1.49 ± 0.54 |
| lanjian | input-whyando | 0.9 ± 0.2 | 0.3 | 1.5 | 1.52 ± 0.56 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.6 | 1.56 ± 0.60 |
| kcen | input-mattcl | 1.3 ± 0.2 | 0.6 | 2.0 | 2.15 ± 0.75 |
| kcen | input-lanjian | 1.3 ± 0.2 | 0.5 | 2.1 | 2.17 ± 0.77 |
| kcen | input-whyando | 1.4 ± 0.2 | 0.6 | 2.7 | 2.22 ± 0.79 |
| mattcl-py | input-mattcl | 18.2 ± 0.7 | 17.3 | 21.5 | 29.59 ± 9.64 |
| mattcl-py | input-whyando | 18.3 ± 0.6 | 17.1 | 21.7 | 29.62 ± 9.64 |
| mattcl-py | input-lanjian | 18.3 ± 0.6 | 17.3 | 21.0 | 29.64 ± 9.64 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>640</pre>|<pre>365804144481581</pre>|
|input-mattcl|<pre>607</pre>|<pre>342433357244012</pre>|
|input-whyando|<pre>643</pre>|<pre>342018167474526</pre>|