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
| mattcl | input-lanjian | 0.6 ± 0.2 | 0.0 | 1.3 | 1.00 |
| mattcl | input-whyando | 0.6 ± 0.2 | 0.0 | 1.2 | 1.00 ± 0.36 |
| mattcl | input-mattcl | 0.7 ± 0.1 | 0.0 | 1.1 | 1.03 ± 0.36 |
| whyando | input-whyando | 0.7 ± 0.1 | 0.1 | 0.9 | 1.04 ± 0.36 |
| whyando | input-mattcl | 0.7 ± 0.1 | 0.0 | 1.1 | 1.06 ± 0.36 |
| whyando | input-lanjian | 0.7 ± 0.1 | 0.2 | 1.3 | 1.10 ± 0.36 |
| lanjian | input-whyando | 0.9 ± 0.2 | 0.0 | 1.5 | 1.44 ± 0.46 |
| lanjian | input-mattcl | 1.0 ± 0.1 | 0.5 | 1.5 | 1.48 ± 0.43 |
| lanjian | input-lanjian | 1.0 ± 0.1 | 0.3 | 1.4 | 1.50 ± 0.46 |
| kcen | input-mattcl | 1.3 ± 0.2 | 0.3 | 2.0 | 2.08 ± 0.65 |
| kcen | input-lanjian | 1.4 ± 0.2 | 0.5 | 2.2 | 2.10 ± 0.66 |
| kcen | input-whyando | 1.4 ± 0.1 | 0.7 | 1.7 | 2.15 ± 0.60 |
| mattcl-py | input-mattcl | 18.2 ± 0.7 | 17.2 | 21.5 | 28.40 ± 7.57 |
| mattcl-py | input-whyando | 18.3 ± 0.6 | 17.4 | 21.3 | 28.45 ± 7.56 |
| mattcl-py | input-lanjian | 18.3 ± 0.8 | 17.0 | 22.1 | 28.56 ± 7.64 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>640</pre>|<pre>365804144481581</pre>|
|input-mattcl|<pre>607</pre>|<pre>342433357244012</pre>|
|input-whyando|<pre>643</pre>|<pre>342018167474526</pre>|