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
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-chancalan | 1.4 ± 0.2 | 0.7 | 2.1 | 1.00 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 0.8 | 2.1 | 1.07 ± 0.24 |
| mattcl | input-pting | 1.5 ± 0.2 | 0.7 | 2.2 | 1.07 ± 0.23 |
| mattcl | input-lanjian | 1.6 ± 0.2 | 0.9 | 2.3 | 1.11 ± 0.22 |
| lanjian | input-lanjian | 1.6 ± 0.2 | 0.6 | 2.0 | 1.12 ± 0.23 |
| lanjian | input-pting | 1.6 ± 0.2 | 0.8 | 2.1 | 1.12 ± 0.22 |
| lanjian | input-chancalan | 1.6 ± 0.2 | 0.9 | 2.2 | 1.13 ± 0.22 |
| lanjian | input-mattcl | 1.6 ± 0.2 | 0.8 | 1.9 | 1.13 ± 0.21 |
| pting | input-lanjian | 24.7 ± 0.7 | 23.5 | 28.0 | 17.11 ± 2.75 |
| pting | input-chancalan | 24.9 ± 0.7 | 24.0 | 28.2 | 17.25 ± 2.77 |
| pting | input-pting | 25.0 ± 0.7 | 23.9 | 28.0 | 17.32 ± 2.77 |
| pting | input-mattcl | 25.0 ± 3.1 | 23.8 | 58.3 | 17.35 ± 3.50 |
| chancalan | input-mattcl | 26.3 ± 0.7 | 25.0 | 28.8 | 18.23 ± 2.92 |
| chancalan | input-chancalan | 26.3 ± 0.7 | 25.1 | 28.9 | 18.23 ± 2.91 |
| chancalan | input-lanjian | 26.3 ± 0.8 | 24.8 | 29.4 | 18.27 ± 2.94 |
| chancalan | input-pting | 26.4 ± 0.7 | 25.4 | 29.5 | 18.31 ± 2.93 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|