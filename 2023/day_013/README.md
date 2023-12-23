# Day 13 benchmarks

[link to problem](https://adventofcode.com/2023/day/13)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 13)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-kcen | 1.0 ± 0.2 | 0.6 | 1.6 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.5 | 1.00 ± 0.32 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.6 | 1.6 | 1.01 ± 0.32 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.5 | 1.02 ± 0.32 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.8 | 1.10 ± 0.35 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.7 | 1.10 ± 0.36 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.14 ± 0.35 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.7 | 1.14 ± 0.36 |
| mattcl-py | input-pting | 15.8 ± 0.6 | 14.6 | 18.6 | 16.41 ± 3.77 |
| mattcl-py | input-mattcl | 15.9 ± 0.6 | 14.8 | 18.5 | 16.51 ± 3.80 |
| mattcl-py | input-lanjian | 15.9 ± 0.7 | 14.9 | 19.0 | 16.55 ± 3.83 |
| mattcl-py | input-kcen | 16.0 ± 3.0 | 14.6 | 55.8 | 16.57 ± 4.90 |
| pting | input-kcen | 17.0 ± 0.6 | 16.1 | 19.9 | 17.59 ± 4.04 |
| pting | input-lanjian | 17.0 ± 0.6 | 15.7 | 19.9 | 17.61 ± 4.05 |
| pting | input-mattcl | 17.2 ± 0.6 | 16.1 | 20.4 | 17.90 ± 4.11 |
| pting | input-pting | 17.2 ± 0.8 | 16.1 | 20.4 | 17.90 ± 4.14 |
| kcen | input-lanjian | 20.3 ± 0.7 | 19.3 | 23.1 | 21.03 ± 4.83 |
| kcen | input-mattcl | 20.4 ± 0.7 | 19.2 | 23.5 | 21.21 ± 4.86 |
| kcen | input-pting | 20.5 ± 0.7 | 19.0 | 23.6 | 21.23 ± 4.86 |
| kcen | input-kcen | 20.8 ± 5.4 | 19.0 | 72.7 | 21.63 ± 7.46 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|