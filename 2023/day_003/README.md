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
| mattcl | input-pting | 1.5 ± 0.2 | 0.8 | 2.0 | 1.00 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 0.6 | 2.3 | 1.01 ± 0.21 |
| mattcl | input-chancalan | 1.6 ± 0.3 | 0.7 | 2.2 | 1.03 ± 0.23 |
| mattcl | input-mattcl | 1.6 ± 0.3 | 0.7 | 2.3 | 1.05 ± 0.23 |
| lanjian | input-mattcl | 1.6 ± 0.3 | 0.6 | 2.2 | 1.06 ± 0.22 |
| lanjian | input-pting | 1.7 ± 0.2 | 0.8 | 2.0 | 1.10 ± 0.18 |
| lanjian | input-chancalan | 1.7 ± 0.2 | 0.9 | 2.5 | 1.10 ± 0.19 |
| lanjian | input-lanjian | 1.8 ± 4.8 | 0.5 | 69.1 | 1.16 ± 3.16 |
| pting | input-lanjian | 24.6 ± 0.8 | 23.0 | 27.8 | 16.18 ± 2.25 |
| pting | input-mattcl | 24.7 ± 0.8 | 23.6 | 27.9 | 16.27 ± 2.26 |
| pting | input-chancalan | 25.0 ± 0.9 | 23.8 | 27.7 | 16.41 ± 2.29 |
| pting | input-pting | 25.0 ± 0.8 | 23.9 | 27.9 | 16.43 ± 2.27 |
| chancalan | input-mattcl | 26.3 ± 0.8 | 25.1 | 29.2 | 17.26 ± 2.39 |
| chancalan | input-lanjian | 26.3 ± 0.8 | 25.2 | 29.5 | 17.29 ± 2.39 |
| chancalan | input-chancalan | 26.3 ± 0.8 | 25.1 | 29.6 | 17.31 ± 2.39 |
| chancalan | input-pting | 26.5 ± 1.0 | 25.1 | 29.7 | 17.44 ± 2.44 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|