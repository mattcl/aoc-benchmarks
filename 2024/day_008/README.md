# Day 8 benchmarks

[link to problem](https://adventofcode.com/2024/day/8)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 8)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-lanjian | 1.0 ± 0.4 | 0.2 | 1.7 | 1.00 |
| mattcl | input-lanjian | 1.0 ± 0.4 | 0.1 | 2.0 | 1.03 ± 0.56 |
| kcen | input-lanjian | 1.1 ± 0.4 | 0.3 | 2.0 | 1.05 ± 0.62 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.4 | 1.9 | 1.26 ± 0.57 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.1 | 1.35 ± 0.62 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.9 | 2.6 | 1.41 ± 0.62 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.8 | 2.0 | 1.42 ± 0.63 |
| kcen | input-kcen | 1.4 ± 0.2 | 0.7 | 2.6 | 1.42 ± 0.64 |
| kcen | input-mattcl | 1.5 ± 0.3 | 1.0 | 2.5 | 1.52 ± 0.70 |
| mattcl-py | input-kcen | 16.6 ± 0.9 | 15.4 | 23.4 | 16.31 ± 7.01 |
| mattcl-py | input-lanjian | 16.7 ± 0.6 | 15.9 | 19.2 | 16.47 ± 7.05 |
| mattcl-py | input-mattcl | 16.9 ± 0.8 | 15.8 | 20.3 | 16.62 ± 7.13 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>261</pre>|<pre>898</pre>|
|input-lanjian|<pre>357</pre>|<pre>1266</pre>|
|input-mattcl|<pre>413</pre>|<pre>1417</pre>|