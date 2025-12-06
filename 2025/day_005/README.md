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
| whyando | input-whyando | 0.6 ± 0.2 | 0.0 | 1.1 | 1.00 |
| mattcl | input-mattcl | 0.6 ± 0.2 | 0.0 | 1.1 | 1.07 ± 0.53 |
| mattcl | input-lanjian | 0.7 ± 0.1 | 0.0 | 1.1 | 1.13 ± 0.54 |
| whyando | input-mattcl | 0.7 ± 0.1 | 0.2 | 1.1 | 1.17 ± 0.55 |
| mattcl | input-whyando | 0.7 ± 0.2 | 0.1 | 1.4 | 1.17 ± 0.57 |
| whyando | input-lanjian | 0.7 ± 0.1 | 0.2 | 0.9 | 1.22 ± 0.55 |
| kcen | input-lanjian | 1.3 ± 0.2 | 0.6 | 2.6 | 2.26 ± 1.02 |
| kcen | input-mattcl | 1.4 ± 0.2 | 0.5 | 2.1 | 2.34 ± 1.04 |
| kcen | input-whyando | 1.4 ± 0.2 | 0.8 | 2.2 | 2.34 ± 1.04 |
| lanjian | input-mattcl | 1.7 ± 0.3 | 1.0 | 2.7 | 2.92 ± 1.35 |
| lanjian | input-whyando | 1.8 ± 0.4 | 1.1 | 2.6 | 3.11 ± 1.44 |
| lanjian | input-lanjian | 2.0 ± 0.4 | 1.3 | 3.3 | 3.43 ± 1.57 |
| mattcl-py | input-whyando | 18.1 ± 0.5 | 17.0 | 20.8 | 30.75 ± 13.01 |
| mattcl-py | input-mattcl | 18.2 ± 0.7 | 17.0 | 21.7 | 30.86 ± 13.09 |
| mattcl-py | input-lanjian | 18.3 ± 0.8 | 17.0 | 21.5 | 31.02 ± 13.15 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>640</pre>|<pre>365804144481581</pre>|
|input-mattcl|<pre>607</pre>|<pre>342433357244012</pre>|
|input-whyando|<pre>643</pre>|<pre>342018167474526</pre>|