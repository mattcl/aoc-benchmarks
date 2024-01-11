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
| mattcl | input-mattcl | 1.4 ± 0.3 | 1.0 | 2.5 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.3 | 1.0 | 2.4 | 1.01 ± 0.25 |
| lanjian | input-mattcl | 3.1 ± 0.4 | 2.2 | 5.7 | 2.17 ± 0.48 |
| lanjian | input-lanjian | 3.3 ± 0.4 | 2.4 | 5.8 | 2.29 ± 0.50 |
| mattcl-py | input-lanjian | 209.0 ± 3.0 | 203.3 | 212.5 | 145.83 ± 26.36 |
| mattcl-py | input-mattcl | 214.2 ± 4.2 | 210.1 | 226.5 | 149.47 ± 27.09 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>3677</pre>|<pre>609585229256084</pre>|
|input-mattcl|<pre>3776</pre>|<pre>625587097150084</pre>|