# Day 21 benchmarks

[link to problem](https://adventofcode.com/2023/day/21)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 21)

- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.1 | 2.2 | 1.00 |
| mattcl | input-lanjian | 1.5 ± 0.3 | 1.1 | 2.4 | 1.01 ± 0.22 |
| lanjian | input-mattcl | 3.8 ± 0.5 | 2.9 | 7.7 | 2.50 ± 0.49 |
| lanjian | input-lanjian | 3.9 ± 0.4 | 3.1 | 6.7 | 2.55 ± 0.46 |
| mattcl-py | input-lanjian | 210.1 ± 3.2 | 205.6 | 219.1 | 138.70 ± 19.64 |
| mattcl-py | input-mattcl | 215.2 ± 4.2 | 210.0 | 222.6 | 142.07 ± 20.19 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>3677</pre>|<pre>609585229256084</pre>|
|input-mattcl|<pre>3776</pre>|<pre>625587097150084</pre>|