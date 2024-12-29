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
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.9 | 2.7 | 1.00 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.9 | 2.6 | 1.00 ± 0.22 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.8 | 2.4 | 1.01 ± 0.20 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.9 | 2.6 | 1.01 ± 0.23 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.6 | 2.2 | 1.02 ± 0.21 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.3 | 2.3 | 1.02 ± 0.20 |
| kcen | input-kcen | 1.4 ± 0.2 | 0.7 | 2.3 | 1.02 ± 0.20 |
| kcen | input-mattcl | 1.4 ± 0.2 | 0.8 | 2.3 | 1.03 ± 0.20 |
| kcen | input-lanjian | 1.5 ± 0.2 | 0.6 | 2.4 | 1.05 ± 0.24 |
| mattcl-py | input-kcen | 18.4 ± 0.6 | 17.3 | 21.1 | 13.08 ± 2.08 |
| mattcl-py | input-lanjian | 18.6 ± 0.5 | 17.4 | 21.4 | 13.26 ± 2.10 |
| mattcl-py | input-mattcl | 18.9 ± 0.6 | 17.7 | 21.5 | 13.41 ± 2.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>611</pre>|<pre>1380</pre>|
|input-lanjian|<pre>776</pre>|<pre>1657</pre>|
|input-mattcl|<pre>624</pre>|<pre>1483</pre>|