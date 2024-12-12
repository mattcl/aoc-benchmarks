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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.9 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 2.0 | 1.05 ± 0.26 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.2 | 2.1 | 1.05 ± 0.28 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.6 | 2.1 | 1.18 ± 0.26 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.2 | 1.9 | 1.18 ± 0.26 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.0 | 1.19 ± 0.26 |
| kcen | input-kcen | 1.4 ± 0.2 | 0.5 | 2.4 | 1.22 ± 0.27 |
| kcen | input-lanjian | 1.4 ± 0.1 | 0.8 | 2.1 | 1.23 ± 0.24 |
| kcen | input-mattcl | 1.5 ± 0.2 | 0.7 | 2.5 | 1.27 ± 0.30 |
| mattcl-py | input-kcen | 16.3 ± 0.7 | 15.3 | 19.0 | 14.14 ± 2.43 |
| mattcl-py | input-lanjian | 16.4 ± 0.6 | 15.4 | 20.0 | 14.25 ± 2.44 |
| mattcl-py | input-mattcl | 16.5 ± 0.6 | 15.3 | 19.9 | 14.31 ± 2.46 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>261</pre>|<pre>898</pre>|
|input-lanjian|<pre>357</pre>|<pre>1266</pre>|
|input-mattcl|<pre>413</pre>|<pre>1417</pre>|