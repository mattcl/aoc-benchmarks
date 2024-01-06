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
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.8 | 1.00 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.01 ± 0.29 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.03 ± 0.31 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.6 | 1.04 ± 0.31 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.7 | 1.10 ± 0.32 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.7 | 1.13 ± 0.32 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.8 | 1.7 | 1.13 ± 0.34 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.8 | 1.7 | 1.14 ± 0.33 |
| mattcl-py | input-lanjian | 16.0 ± 0.7 | 14.9 | 19.2 | 15.69 ± 3.29 |
| mattcl-py | input-mattcl | 16.0 ± 0.7 | 15.0 | 19.3 | 15.71 ± 3.29 |
| mattcl-py | input-kcen | 16.1 ± 0.9 | 14.6 | 19.4 | 15.79 ± 3.34 |
| mattcl-py | input-pting | 16.1 ± 0.8 | 14.7 | 19.5 | 15.79 ± 3.32 |
| pting | input-kcen | 17.1 ± 0.6 | 16.1 | 20.4 | 16.74 ± 3.47 |
| pting | input-lanjian | 17.1 ± 0.7 | 16.2 | 20.3 | 16.79 ± 3.51 |
| pting | input-pting | 17.2 ± 0.7 | 16.1 | 20.2 | 16.87 ± 3.51 |
| pting | input-mattcl | 17.3 ± 0.7 | 16.2 | 20.4 | 16.93 ± 3.53 |
| kcen | input-kcen | 20.3 ± 0.6 | 19.1 | 23.0 | 19.85 ± 4.11 |
| kcen | input-lanjian | 20.3 ± 0.7 | 19.3 | 22.8 | 19.88 ± 4.12 |
| kcen | input-pting | 20.5 ± 0.7 | 19.1 | 23.5 | 20.12 ± 4.18 |
| kcen | input-mattcl | 20.7 ± 0.6 | 19.4 | 23.2 | 20.25 ± 4.19 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|