# Day 23 benchmarks

[link to problem](https://adventofcode.com/2023/day/23)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 23)

- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 5.8 ± 0.2 | 5.1 | 7.3 | 1.00 |
| mattcl | input-lanjian | 5.8 ± 0.2 | 5.2 | 6.4 | 1.01 ± 0.06 |
| mattcl-py | input-lanjian | 373.7 ± 11.8 | 357.5 | 386.2 | 64.49 ± 3.39 |
| mattcl-py | input-mattcl | 386.6 ± 11.9 | 376.5 | 406.2 | 66.71 ± 3.49 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>2250</pre>|<pre>6378</pre>|
|input-mattcl|<pre>2438</pre>|<pre>6658</pre>|