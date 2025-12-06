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
| whyando | input-mattcl | 0.6 ± 0.2 | 0.0 | 1.2 | 1.03 ± 0.46 |
| whyando | input-lanjian | 0.7 ± 0.1 | 0.1 | 1.1 | 1.10 ± 0.44 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.1 | 1.7 | 1.72 ± 0.66 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.8 | 1.74 ± 0.66 |
| mattcl | input-whyando | 1.0 ± 0.2 | 0.3 | 1.8 | 1.76 ± 0.67 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.4 | 2.1 | 2.19 ± 0.85 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.6 | 2.4 | 2.19 ± 0.82 |
| lanjian | input-whyando | 1.3 ± 0.2 | 0.3 | 2.2 | 2.20 ± 0.84 |
| kcen | input-lanjian | 1.3 ± 0.2 | 0.5 | 2.5 | 2.22 ± 0.85 |
| kcen | input-mattcl | 1.4 ± 0.2 | 0.5 | 2.9 | 2.27 ± 0.87 |
| kcen | input-whyando | 1.4 ± 0.2 | 0.5 | 2.1 | 2.27 ± 0.85 |
| mattcl-py | input-mattcl | 18.0 ± 0.7 | 17.1 | 20.9 | 30.14 ± 10.29 |
| mattcl-py | input-lanjian | 18.1 ± 0.7 | 16.5 | 20.8 | 30.34 ± 10.36 |
| mattcl-py | input-whyando | 18.3 ± 0.7 | 16.8 | 21.1 | 30.57 ± 10.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>640</pre>|<pre>365804144481581</pre>|
|input-mattcl|<pre>607</pre>|<pre>342433357244012</pre>|
|input-whyando|<pre>643</pre>|<pre>342018167474526</pre>|