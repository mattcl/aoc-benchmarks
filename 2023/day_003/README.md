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
| mattcl | input-pting | 1.5 ± 0.2 | 0.7 | 2.1 | 1.03 ± 0.22 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 0.7 | 2.3 | 1.05 ± 0.23 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 0.8 | 2.2 | 1.08 ± 0.24 |
| lanjian | input-mattcl | 1.6 ± 0.2 | 0.4 | 1.9 | 1.09 ± 0.23 |
| lanjian | input-chancalan | 1.6 ± 0.2 | 0.7 | 2.2 | 1.14 ± 0.24 |
| lanjian | input-pting | 1.6 ± 0.2 | 0.7 | 2.2 | 1.15 ± 0.24 |
| lanjian | input-lanjian | 1.7 ± 0.2 | 0.8 | 2.0 | 1.19 ± 0.22 |
| pting | input-mattcl | 24.5 ± 0.9 | 23.5 | 27.9 | 17.28 ± 2.74 |
| pting | input-lanjian | 24.6 ± 0.9 | 23.4 | 27.4 | 17.32 ± 2.75 |
| pting | input-chancalan | 24.6 ± 0.7 | 23.6 | 27.3 | 17.35 ± 2.73 |
| pting | input-pting | 24.8 ± 1.5 | 23.5 | 38.8 | 17.45 ± 2.90 |
| chancalan | input-mattcl | 25.9 ± 0.8 | 24.9 | 28.8 | 18.28 ± 2.88 |
| chancalan | input-lanjian | 25.9 ± 0.8 | 25.2 | 29.2 | 18.28 ± 2.88 |
| chancalan | input-chancalan | 26.1 ± 0.8 | 25.0 | 29.2 | 18.37 ± 2.90 |
| chancalan | input-pting | 26.1 ± 0.9 | 25.0 | 29.3 | 18.38 ± 2.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|