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
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.1 | 2.1 | 1.00 |
| mattcl | input-kcen | 1.3 ± 0.3 | 0.2 | 2.1 | 1.03 ± 0.36 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.1 | 1.12 ± 0.36 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.3 | 1.8 | 1.14 ± 0.35 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.2 | 1.15 ± 0.37 |
| kcen | input-kcen | 1.4 ± 0.2 | 0.8 | 2.2 | 1.15 ± 0.36 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.0 | 1.15 ± 0.36 |
| kcen | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.3 | 1.18 ± 0.38 |
| kcen | input-mattcl | 1.5 ± 0.2 | 1.0 | 2.5 | 1.23 ± 0.40 |
| mattcl-py | input-kcen | 16.7 ± 0.6 | 15.4 | 19.3 | 13.74 ± 3.95 |
| mattcl-py | input-lanjian | 16.8 ± 0.6 | 16.0 | 19.5 | 13.81 ± 3.96 |
| mattcl-py | input-mattcl | 16.9 ± 0.7 | 15.4 | 20.5 | 13.88 ± 3.99 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>261</pre>|<pre>898</pre>|
|input-lanjian|<pre>357</pre>|<pre>1266</pre>|
|input-mattcl|<pre>413</pre>|<pre>1417</pre>|