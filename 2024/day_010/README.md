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
| kcen | input-mattcl | 1.2 ± 0.4 | 0.4 | 2.4 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.3 | 0.4 | 2.4 | 1.01 ± 0.40 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.0 | 1.14 ± 0.36 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 1.0 | 2.4 | 1.14 ± 0.35 |
| lanjian | input-kcen | 1.4 ± 0.2 | 1.0 | 2.3 | 1.14 ± 0.37 |
| mattcl | input-kcen | 1.5 ± 0.2 | 0.8 | 2.5 | 1.16 ± 0.37 |
| kcen | input-kcen | 1.5 ± 0.2 | 0.9 | 2.4 | 1.17 ± 0.36 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 0.6 | 2.3 | 1.20 ± 0.39 |
| kcen | input-lanjian | 1.5 ± 0.3 | 1.2 | 2.7 | 1.22 ± 0.41 |
| mattcl-py | input-kcen | 18.7 ± 0.7 | 17.4 | 21.3 | 14.96 ± 4.29 |
| mattcl-py | input-mattcl | 18.9 ± 0.6 | 17.5 | 22.3 | 15.16 ± 4.34 |
| mattcl-py | input-lanjian | 19.0 ± 0.7 | 18.0 | 22.2 | 15.18 ± 4.35 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>611</pre>|<pre>1380</pre>|
|input-lanjian|<pre>776</pre>|<pre>1657</pre>|
|input-mattcl|<pre>624</pre>|<pre>1483</pre>|