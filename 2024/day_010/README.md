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
| mattcl | input-lanjian | 1.3 ± 0.4 | 0.3 | 2.6 | 1.00 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.9 | 2.4 | 1.07 ± 0.35 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.9 | 2.4 | 1.07 ± 0.35 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.9 | 2.2 | 1.08 ± 0.34 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.7 | 2.3 | 1.10 ± 0.33 |
| kcen | input-lanjian | 1.5 ± 0.2 | 0.6 | 2.3 | 1.12 ± 0.36 |
| kcen | input-mattcl | 1.5 ± 0.2 | 0.8 | 2.7 | 1.13 ± 0.37 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 0.9 | 2.4 | 1.14 ± 0.37 |
| kcen | input-kcen | 1.5 ± 0.3 | 0.8 | 2.8 | 1.16 ± 0.40 |
| mattcl-py | input-kcen | 18.6 ± 0.6 | 17.7 | 21.3 | 14.28 ± 4.03 |
| mattcl-py | input-lanjian | 18.8 ± 0.6 | 17.4 | 21.9 | 14.43 ± 4.07 |
| mattcl-py | input-mattcl | 19.1 ± 0.7 | 17.5 | 23.3 | 14.67 ± 4.15 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>611</pre>|<pre>1380</pre>|
|input-lanjian|<pre>776</pre>|<pre>1657</pre>|
|input-mattcl|<pre>624</pre>|<pre>1483</pre>|