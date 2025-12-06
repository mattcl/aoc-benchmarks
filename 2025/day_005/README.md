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
| whyando | input-mattcl | 0.6 ± 0.1 | 0.2 | 1.2 | 1.00 |
| whyando | input-lanjian | 0.6 ± 0.1 | 0.0 | 1.5 | 1.00 ± 0.30 |
| whyando | input-whyando | 0.7 ± 0.1 | 0.2 | 1.2 | 1.04 ± 0.31 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.1 | 1.7 | 1.59 ± 0.43 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.4 | 1.7 | 1.60 ± 0.44 |
| mattcl | input-whyando | 1.0 ± 0.2 | 0.4 | 2.6 | 1.62 ± 0.47 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.1 | 2.0 | 1.83 ± 0.60 |
| lanjian | input-whyando | 1.3 ± 0.2 | 0.6 | 2.1 | 2.10 ± 0.55 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.7 | 2.1 | 2.10 ± 0.52 |
| kcen | input-mattcl | 1.3 ± 0.2 | 0.5 | 2.6 | 2.11 ± 0.53 |
| kcen | input-lanjian | 1.3 ± 0.2 | 0.7 | 2.0 | 2.12 ± 0.52 |
| kcen | input-whyando | 1.4 ± 0.2 | 0.7 | 1.9 | 2.13 ± 0.50 |
| mattcl-py | input-lanjian | 18.2 ± 0.6 | 17.2 | 21.2 | 28.60 ± 5.73 |
| mattcl-py | input-mattcl | 18.2 ± 0.6 | 17.1 | 21.0 | 28.61 ± 5.75 |
| mattcl-py | input-whyando | 18.3 ± 0.7 | 16.8 | 21.9 | 28.77 ± 5.80 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>640</pre>|<pre>365804144481581</pre>|
|input-mattcl|<pre>607</pre>|<pre>342433357244012</pre>|
|input-whyando|<pre>643</pre>|<pre>342018167474526</pre>|