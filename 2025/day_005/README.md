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
| mattcl | input-whyando | 0.5 ± 0.4 | 0.0 | 4.5 | 1.00 |
| mattcl | input-mattcl | 0.6 ± 0.2 | 0.0 | 0.8 | 1.26 ± 1.18 |
| whyando | input-mattcl | 0.6 ± 0.2 | 0.0 | 0.9 | 1.30 ± 1.20 |
| mattcl | input-lanjian | 0.6 ± 0.2 | 0.0 | 0.9 | 1.31 ± 1.21 |
| whyando | input-lanjian | 0.7 ± 0.2 | 0.0 | 0.9 | 1.43 ± 1.29 |
| lanjian | input-whyando | 0.8 ± 0.4 | 0.0 | 1.2 | 1.58 ± 1.57 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.1 | 1.89 ± 1.68 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.0 | 1.2 | 1.95 ± 1.74 |
| kcen | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.5 | 2.63 ± 2.33 |
| kcen | input-whyando | 1.3 ± 0.2 | 0.3 | 1.6 | 2.64 ± 2.36 |
| kcen | input-lanjian | 1.3 ± 0.1 | 0.3 | 1.6 | 2.74 ± 2.41 |
| whyando | input-whyando | 1.4 ± 3.8 | 0.0 | 22.9 | 2.87 ± 8.04 |
| mattcl-py | input-mattcl | 18.7 ± 0.6 | 17.5 | 21.7 | 37.97 ± 33.18 |
| mattcl-py | input-whyando | 19.0 ± 1.7 | 17.5 | 27.7 | 38.69 ± 33.97 |
| mattcl-py | input-lanjian | 20.0 ± 3.0 | 17.7 | 30.5 | 40.68 ± 36.06 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>640</pre>|<pre>365804144481581</pre>|
|input-mattcl|<pre>607</pre>|<pre>342433357244012</pre>|
|input-whyando|<pre>643</pre>|<pre>342018167474526</pre>|