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
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.0 | 0.9 | 1.00 |
| mattcl | input-whyando | 0.7 ± 0.2 | 0.0 | 1.0 | 1.03 ± 0.45 |
| whyando | input-whyando | 0.7 ± 0.2 | 0.0 | 0.9 | 1.03 ± 0.45 |
| mattcl | input-lanjian | 0.7 ± 0.1 | 0.1 | 0.9 | 1.06 ± 0.42 |
| whyando | input-lanjian | 0.7 ± 0.1 | 0.1 | 0.9 | 1.09 ± 0.43 |
| whyando | input-mattcl | 0.7 ± 0.1 | 0.1 | 1.0 | 1.10 ± 0.42 |
| lanjian | input-whyando | 1.0 ± 0.2 | 0.3 | 1.2 | 1.46 ± 0.54 |
| lanjian | input-lanjian | 1.0 ± 0.1 | 0.5 | 1.2 | 1.47 ± 0.54 |
| lanjian | input-mattcl | 1.0 ± 0.1 | 0.6 | 1.2 | 1.49 ± 0.53 |
| kcen | input-lanjian | 1.3 ± 0.3 | 0.2 | 1.7 | 1.94 ± 0.76 |
| kcen | input-mattcl | 1.3 ± 0.2 | 0.3 | 1.6 | 2.00 ± 0.76 |
| kcen | input-whyando | 1.4 ± 0.2 | 0.8 | 1.7 | 2.06 ± 0.74 |
| mattcl-py | input-mattcl | 18.7 ± 0.4 | 17.6 | 20.9 | 28.09 ± 9.44 |
| mattcl-py | input-whyando | 19.8 ± 2.9 | 17.7 | 28.4 | 29.84 ± 10.89 |
| mattcl-py | input-lanjian | 20.0 ± 3.0 | 17.9 | 31.5 | 30.05 ± 11.03 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>640</pre>|<pre>365804144481581</pre>|
|input-mattcl|<pre>607</pre>|<pre>342433357244012</pre>|
|input-whyando|<pre>643</pre>|<pre>342018167474526</pre>|