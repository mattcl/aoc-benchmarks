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
| mattcl | input-lanjian | 0.7 ± 0.1 | 0.3 | 1.1 | 1.00 |
| mattcl | input-whyando | 0.7 ± 0.2 | 0.0 | 1.2 | 1.00 ± 0.32 |
| mattcl | input-mattcl | 0.7 ± 0.1 | 0.3 | 1.2 | 1.01 ± 0.27 |
| whyando | input-lanjian | 1.0 ± 0.2 | 0.5 | 1.6 | 1.46 ± 0.36 |
| whyando | input-mattcl | 1.1 ± 0.1 | 0.5 | 1.6 | 1.48 ± 0.36 |
| whyando | input-whyando | 1.1 ± 0.2 | 0.6 | 2.0 | 1.61 ± 0.44 |
| kcen | input-lanjian | 1.4 ± 0.2 | 0.5 | 2.3 | 1.95 ± 0.51 |
| kcen | input-mattcl | 1.4 ± 0.2 | 0.6 | 2.2 | 1.97 ± 0.46 |
| kcen | input-whyando | 1.4 ± 0.2 | 0.8 | 2.6 | 2.01 ± 0.49 |
| lanjian | input-mattcl | 1.8 ± 0.3 | 1.0 | 2.6 | 2.52 ± 0.67 |
| lanjian | input-whyando | 1.9 ± 0.4 | 1.2 | 3.0 | 2.75 ± 0.74 |
| lanjian | input-lanjian | 2.0 ± 0.3 | 1.1 | 3.0 | 2.85 ± 0.73 |
| mattcl-py | input-mattcl | 18.1 ± 0.6 | 17.1 | 20.6 | 25.42 ± 5.09 |
| mattcl-py | input-whyando | 18.1 ± 0.7 | 17.3 | 21.1 | 25.54 ± 5.12 |
| mattcl-py | input-lanjian | 18.2 ± 0.7 | 16.8 | 21.4 | 25.62 ± 5.16 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>640</pre>|<pre>365804144481581</pre>|
|input-mattcl|<pre>607</pre>|<pre>342433357244012</pre>|
|input-whyando|<pre>643</pre>|<pre>342018167474526</pre>|