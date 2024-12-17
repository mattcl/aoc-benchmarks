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
| lanjian | input-lanjian | 1.1 ± 0.4 | 0.2 | 2.0 | 1.00 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.2 | 1.8 | 1.04 ± 0.44 |
| mattcl | input-lanjian | 1.3 ± 0.3 | 0.4 | 2.5 | 1.16 ± 0.48 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.4 | 2.2 | 1.19 ± 0.47 |
| kcen | input-lanjian | 1.3 ± 0.3 | 0.3 | 1.9 | 1.19 ± 0.49 |
| lanjian | input-mattcl | 1.4 ± 0.1 | 0.6 | 1.8 | 1.25 ± 0.47 |
| lanjian | input-kcen | 1.4 ± 0.1 | 0.9 | 1.6 | 1.27 ± 0.47 |
| kcen | input-kcen | 1.4 ± 0.2 | 0.6 | 2.1 | 1.27 ± 0.48 |
| kcen | input-mattcl | 1.5 ± 0.3 | 0.9 | 2.6 | 1.36 ± 0.55 |
| mattcl-py | input-kcen | 16.5 ± 0.7 | 15.7 | 19.7 | 15.13 ± 5.52 |
| mattcl-py | input-mattcl | 16.6 ± 0.5 | 15.3 | 19.3 | 15.24 ± 5.54 |
| mattcl-py | input-lanjian | 16.8 ± 0.8 | 15.6 | 21.0 | 15.36 ± 5.61 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>261</pre>|<pre>898</pre>|
|input-lanjian|<pre>357</pre>|<pre>1266</pre>|
|input-mattcl|<pre>413</pre>|<pre>1417</pre>|