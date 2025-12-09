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
| mattcl | input-lanjian | 0.7 ± 0.1 | 0.1 | 1.2 | 1.00 |
| mattcl | input-mattcl | 0.7 ± 0.1 | 0.0 | 1.0 | 1.00 ± 0.30 |
| mattcl | input-whyando | 0.7 ± 0.2 | 0.0 | 1.1 | 1.02 ± 0.32 |
| whyando | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.1 | 1.02 ± 0.32 |
| whyando | input-whyando | 0.7 ± 0.2 | 0.1 | 1.2 | 1.04 ± 0.33 |
| whyando | input-mattcl | 0.7 ± 0.2 | 0.2 | 1.2 | 1.04 ± 0.33 |
| lanjian | input-whyando | 0.9 ± 0.1 | 0.0 | 1.4 | 1.41 ± 0.37 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.4 | 1.1 | 1.41 ± 0.36 |
| lanjian | input-lanjian | 0.9 ± 0.1 | 0.4 | 1.5 | 1.44 ± 0.38 |
| kcen | input-mattcl | 1.4 ± 0.2 | 0.7 | 1.8 | 2.10 ± 0.51 |
| kcen | input-whyando | 1.4 ± 0.2 | 0.6 | 2.0 | 2.10 ± 0.52 |
| kcen | input-lanjian | 1.4 ± 0.2 | 0.7 | 1.9 | 2.13 ± 0.52 |
| mattcl-py | input-whyando | 18.2 ± 0.6 | 17.1 | 20.9 | 27.88 ± 6.04 |
| mattcl-py | input-mattcl | 18.3 ± 0.7 | 17.2 | 21.0 | 27.99 ± 6.08 |
| mattcl-py | input-lanjian | 18.4 ± 0.7 | 17.1 | 21.8 | 28.15 ± 6.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>640</pre>|<pre>365804144481581</pre>|
|input-mattcl|<pre>607</pre>|<pre>342433357244012</pre>|
|input-whyando|<pre>643</pre>|<pre>342018167474526</pre>|