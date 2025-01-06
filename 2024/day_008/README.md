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
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.5 | 2.0 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.0 | 1.05 ± 0.23 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.6 | 1.9 | 1.05 ± 0.23 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.7 | 2.6 | 1.10 ± 0.24 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.4 | 1.10 ± 0.22 |
| lanjian | input-mattcl | 1.4 ± 0.1 | 0.8 | 1.7 | 1.10 ± 0.19 |
| kcen | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.3 | 1.11 ± 0.21 |
| kcen | input-kcen | 1.4 ± 0.2 | 0.8 | 2.3 | 1.11 ± 0.24 |
| kcen | input-mattcl | 1.5 ± 0.2 | 0.9 | 2.3 | 1.12 ± 0.22 |
| mattcl-py | input-kcen | 16.4 ± 0.7 | 15.1 | 20.0 | 12.62 ± 2.07 |
| mattcl-py | input-lanjian | 16.6 ± 0.8 | 15.6 | 19.7 | 12.77 ± 2.11 |
| mattcl-py | input-mattcl | 16.6 ± 0.7 | 15.3 | 20.0 | 12.80 ± 2.10 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>261</pre>|<pre>898</pre>|
|input-lanjian|<pre>357</pre>|<pre>1266</pre>|
|input-mattcl|<pre>413</pre>|<pre>1417</pre>|