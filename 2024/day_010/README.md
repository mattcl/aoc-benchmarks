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
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.2 | 1.00 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.9 | 2.5 | 1.00 ± 0.22 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.8 | 2.2 | 1.00 ± 0.17 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.9 | 2.5 | 1.00 ± 0.19 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.9 | 2.5 | 1.01 ± 0.21 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.4 | 2.3 | 1.02 ± 0.17 |
| kcen | input-kcen | 1.5 ± 0.2 | 0.7 | 2.4 | 1.04 ± 0.17 |
| kcen | input-mattcl | 1.5 ± 0.2 | 0.8 | 2.3 | 1.05 ± 0.19 |
| kcen | input-lanjian | 1.5 ± 0.2 | 1.0 | 2.4 | 1.05 ± 0.19 |
| mattcl-py | input-kcen | 18.5 ± 0.8 | 17.3 | 21.4 | 13.24 ± 1.56 |
| mattcl-py | input-lanjian | 18.7 ± 0.7 | 17.5 | 21.5 | 13.36 ± 1.55 |
| mattcl-py | input-mattcl | 18.8 ± 0.6 | 17.8 | 21.2 | 13.42 ± 1.54 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>611</pre>|<pre>1380</pre>|
|input-lanjian|<pre>776</pre>|<pre>1657</pre>|
|input-mattcl|<pre>624</pre>|<pre>1483</pre>|