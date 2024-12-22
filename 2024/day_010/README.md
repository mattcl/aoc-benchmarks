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
| lanjian | input-kcen | 1.4 ± 0.2 | 0.9 | 2.1 | 1.00 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.9 | 2.4 | 1.01 ± 0.20 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.9 | 2.5 | 1.02 ± 0.20 |
| mattcl | input-kcen | 1.5 ± 0.2 | 1.0 | 2.7 | 1.04 ± 0.18 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.0 | 2.6 | 1.06 ± 0.22 |
| kcen | input-kcen | 1.5 ± 0.2 | 0.6 | 2.4 | 1.07 ± 0.22 |
| mattcl | input-lanjian | 1.5 ± 0.3 | 0.9 | 2.5 | 1.07 ± 0.23 |
| kcen | input-lanjian | 1.6 ± 0.3 | 1.0 | 2.7 | 1.10 ± 0.25 |
| kcen | input-mattcl | 1.6 ± 0.4 | 1.0 | 3.4 | 1.15 ± 0.29 |
| mattcl-py | input-kcen | 18.7 ± 0.7 | 17.4 | 21.9 | 13.18 ± 1.75 |
| mattcl-py | input-lanjian | 19.0 ± 0.6 | 17.7 | 22.3 | 13.44 ± 1.77 |
| mattcl-py | input-mattcl | 19.2 ± 0.7 | 17.7 | 21.9 | 13.54 ± 1.79 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>611</pre>|<pre>1380</pre>|
|input-lanjian|<pre>776</pre>|<pre>1657</pre>|
|input-mattcl|<pre>624</pre>|<pre>1483</pre>|