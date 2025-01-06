# Day 10 benchmarks

[link to problem](https://adventofcode.com/2024/day/10)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 10)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-kcen | 1.4 ± 0.2 | 1.0 | 2.4 | 1.00 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.9 | 2.4 | 1.00 ± 0.20 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.4 | 1.01 ± 0.20 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.7 | 2.2 | 1.01 ± 0.17 |
| kcen | input-mattcl | 1.4 ± 0.2 | 0.8 | 2.7 | 1.02 ± 0.20 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.6 | 1.02 ± 0.19 |
| kcen | input-kcen | 1.5 ± 0.2 | 0.8 | 2.7 | 1.03 ± 0.21 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 0.6 | 2.5 | 1.04 ± 0.21 |
| kcen | input-lanjian | 1.5 ± 0.3 | 0.8 | 2.4 | 1.07 ± 0.24 |
| mattcl-py | input-kcen | 18.4 ± 0.6 | 17.1 | 21.5 | 12.93 ± 1.78 |
| mattcl-py | input-lanjian | 18.7 ± 0.7 | 17.4 | 22.2 | 13.16 ± 1.82 |
| mattcl-py | input-mattcl | 18.8 ± 0.6 | 17.6 | 21.9 | 13.21 ± 1.81 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>611</pre>|<pre>1380</pre>|
|input-lanjian|<pre>776</pre>|<pre>1657</pre>|
|input-mattcl|<pre>624</pre>|<pre>1483</pre>|