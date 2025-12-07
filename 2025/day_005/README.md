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
| mattcl | input-lanjian | 0.4 ± 0.3 | 0.0 | 1.0 | 1.00 |
| mattcl | input-mattcl | 0.6 ± 0.2 | 0.0 | 1.0 | 1.66 ± 1.45 |
| mattcl | input-whyando | 0.6 ± 0.2 | 0.0 | 1.2 | 1.71 ± 1.48 |
| whyando | input-mattcl | 0.6 ± 0.2 | 0.0 | 1.1 | 1.72 ± 1.49 |
| whyando | input-lanjian | 0.6 ± 0.1 | 0.0 | 1.0 | 1.79 ± 1.52 |
| whyando | input-whyando | 0.7 ± 0.1 | 0.1 | 1.2 | 1.87 ± 1.59 |
| kcen | input-mattcl | 1.3 ± 0.2 | 0.6 | 2.0 | 3.72 ± 3.12 |
| kcen | input-whyando | 1.3 ± 0.2 | 0.5 | 1.7 | 3.75 ± 3.13 |
| kcen | input-lanjian | 1.3 ± 0.2 | 0.4 | 1.8 | 3.77 ± 3.16 |
| lanjian | input-mattcl | 1.7 ± 0.3 | 1.0 | 2.8 | 4.94 ± 4.18 |
| lanjian | input-whyando | 1.9 ± 0.3 | 1.2 | 3.3 | 5.29 ± 4.46 |
| lanjian | input-lanjian | 1.9 ± 0.4 | 0.7 | 3.0 | 5.37 ± 4.56 |
| mattcl-py | input-mattcl | 18.1 ± 0.6 | 16.9 | 20.9 | 51.30 ± 42.21 |
| mattcl-py | input-whyando | 18.1 ± 0.6 | 17.1 | 21.0 | 51.43 ± 42.32 |
| mattcl-py | input-lanjian | 18.2 ± 0.6 | 17.1 | 21.0 | 51.54 ± 42.41 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>640</pre>|<pre>365804144481581</pre>|
|input-mattcl|<pre>607</pre>|<pre>342433357244012</pre>|
|input-whyando|<pre>643</pre>|<pre>342018167474526</pre>|