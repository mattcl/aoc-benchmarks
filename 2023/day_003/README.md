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
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.4 | 2.2 | 1.00 |
| mattcl | input-lanjian | 1.5 ± 0.3 | 0.7 | 2.3 | 1.05 ± 0.26 |
| mattcl | input-chancalan | 1.5 ± 0.2 | 0.8 | 2.2 | 1.09 ± 0.24 |
| mattcl | input-pting | 1.6 ± 0.2 | 0.8 | 2.4 | 1.10 ± 0.25 |
| lanjian | input-pting | 1.7 ± 0.2 | 0.9 | 2.2 | 1.20 ± 0.25 |
| lanjian | input-chancalan | 1.7 ± 0.2 | 0.7 | 2.3 | 1.20 ± 0.24 |
| lanjian | input-lanjian | 1.7 ± 0.2 | 0.9 | 2.2 | 1.21 ± 0.26 |
| lanjian | input-mattcl | 1.7 ± 3.1 | 0.5 | 44.7 | 1.22 ± 2.20 |
| mattcl-py | input-lanjian | 22.2 ± 0.6 | 21.0 | 25.2 | 15.80 ± 2.75 |
| mattcl-py | input-chancalan | 22.3 ± 0.6 | 21.4 | 24.7 | 15.85 ± 2.76 |
| mattcl-py | input-mattcl | 22.3 ± 0.6 | 21.3 | 24.8 | 15.85 ± 2.76 |
| mattcl-py | input-pting | 22.4 ± 0.7 | 21.4 | 25.7 | 15.92 ± 2.78 |
| pting | input-lanjian | 24.4 ± 0.7 | 23.3 | 27.0 | 17.37 ± 3.03 |
| pting | input-mattcl | 24.4 ± 0.7 | 23.3 | 27.1 | 17.39 ± 3.03 |
| pting | input-chancalan | 24.7 ± 0.8 | 23.7 | 27.7 | 17.60 ± 3.07 |
| pting | input-pting | 25.0 ± 0.8 | 23.7 | 27.6 | 17.76 ± 3.11 |
| chancalan | input-mattcl | 26.0 ± 0.9 | 24.7 | 29.1 | 18.46 ± 3.23 |
| chancalan | input-chancalan | 26.0 ± 0.7 | 24.9 | 28.5 | 18.49 ± 3.21 |
| chancalan | input-lanjian | 26.1 ± 0.9 | 25.1 | 28.8 | 18.57 ± 3.25 |
| chancalan | input-pting | 26.1 ± 0.9 | 25.2 | 29.3 | 18.59 ± 3.26 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|