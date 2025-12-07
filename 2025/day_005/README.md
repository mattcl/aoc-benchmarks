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
| mattcl | input-mattcl | 0.6 ± 0.2 | 0.0 | 0.9 | 1.00 |
| mattcl | input-lanjian | 0.6 ± 0.2 | 0.0 | 1.0 | 1.04 ± 0.45 |
| mattcl | input-whyando | 0.6 ± 0.2 | 0.0 | 0.9 | 1.08 ± 0.47 |
| whyando | input-mattcl | 0.7 ± 0.2 | 0.0 | 0.9 | 1.10 ± 0.46 |
| whyando | input-whyando | 0.7 ± 0.2 | 0.0 | 0.9 | 1.11 ± 0.49 |
| whyando | input-lanjian | 0.8 ± 1.9 | 0.0 | 15.2 | 1.28 ± 3.23 |
| kcen | input-mattcl | 1.3 ± 0.2 | 0.3 | 1.6 | 2.16 ± 0.82 |
| kcen | input-lanjian | 1.3 ± 0.2 | 0.1 | 1.6 | 2.18 ± 0.82 |
| kcen | input-whyando | 1.3 ± 0.2 | 0.5 | 1.6 | 2.22 ± 0.80 |
| lanjian | input-mattcl | 1.9 ± 0.4 | 1.0 | 2.6 | 3.16 ± 1.23 |
| lanjian | input-whyando | 1.9 ± 0.3 | 1.0 | 2.4 | 3.24 ± 1.23 |
| lanjian | input-lanjian | 2.1 ± 0.4 | 1.1 | 3.0 | 3.45 ± 1.32 |
| mattcl-py | input-whyando | 18.7 ± 0.5 | 17.5 | 21.2 | 31.29 ± 10.68 |
| mattcl-py | input-mattcl | 18.7 ± 0.6 | 17.6 | 21.5 | 31.39 ± 10.73 |
| mattcl-py | input-lanjian | 19.6 ± 2.7 | 17.5 | 28.8 | 32.88 ± 12.08 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>640</pre>|<pre>365804144481581</pre>|
|input-mattcl|<pre>607</pre>|<pre>342433357244012</pre>|
|input-whyando|<pre>643</pre>|<pre>342018167474526</pre>|