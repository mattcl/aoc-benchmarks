# Day 3 benchmarks

[link to problem](https://adventofcode.com/2023/day/3)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 3)

- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-pting | 1.6 ± 0.2 | 0.7 | 2.1 | 1.00 |
| mattcl | input-mattcl | 1.6 ± 0.3 | 0.7 | 2.3 | 1.04 ± 0.22 |
| mattcl | input-chancalan | 1.7 ± 0.2 | 0.9 | 2.3 | 1.08 ± 0.21 |
| mattcl | input-lanjian | 1.7 ± 0.2 | 0.8 | 2.2 | 1.09 ± 0.20 |
| pting | input-lanjian | 24.8 ± 0.7 | 23.7 | 27.5 | 15.85 ± 2.33 |
| pting | input-mattcl | 24.9 ± 0.9 | 23.7 | 28.0 | 15.93 ± 2.37 |
| pting | input-chancalan | 24.9 ± 0.8 | 23.7 | 28.3 | 15.95 ± 2.36 |
| pting | input-pting | 25.2 ± 2.5 | 23.8 | 50.2 | 16.10 ± 2.81 |
| chancalan | input-mattcl | 26.2 ± 0.8 | 25.2 | 29.4 | 16.74 ± 2.47 |
| chancalan | input-lanjian | 26.4 ± 0.9 | 24.9 | 29.2 | 16.85 ± 2.50 |
| chancalan | input-chancalan | 26.5 ± 0.8 | 25.4 | 29.3 | 16.94 ± 2.50 |
| chancalan | input-pting | 26.7 ± 1.1 | 25.3 | 29.4 | 17.08 ± 2.56 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|