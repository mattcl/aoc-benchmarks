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
| mattcl | input-kcen | 1.2 ± 0.3 | 0.1 | 2.0 | 1.00 |
| lanjian | input-kcen | 1.2 ± 0.3 | 0.2 | 1.7 | 1.06 ± 0.40 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.4 | 2.1 | 1.08 ± 0.36 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 2.5 | 1.10 ± 0.36 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.6 | 1.9 | 1.16 ± 0.36 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.7 | 1.7 | 1.17 ± 0.36 |
| kcen | input-kcen | 1.4 ± 0.1 | 0.8 | 2.1 | 1.19 ± 0.36 |
| kcen | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.3 | 1.20 ± 0.39 |
| kcen | input-mattcl | 1.5 ± 0.3 | 0.8 | 2.5 | 1.28 ± 0.44 |
| mattcl-py | input-kcen | 16.5 ± 0.6 | 15.2 | 19.6 | 13.97 ± 3.99 |
| mattcl-py | input-lanjian | 16.6 ± 0.6 | 15.6 | 19.8 | 14.10 ± 4.02 |
| mattcl-py | input-mattcl | 16.8 ± 0.7 | 15.5 | 20.2 | 14.22 ± 4.06 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>261</pre>|<pre>898</pre>|
|input-lanjian|<pre>357</pre>|<pre>1266</pre>|
|input-mattcl|<pre>413</pre>|<pre>1417</pre>|