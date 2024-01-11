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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.00 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.32 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.5 | 1.04 ± 0.32 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.7 | 1.6 | 1.05 ± 0.34 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.8 | 1.13 ± 0.35 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.7 | 1.14 ± 0.35 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.7 | 1.14 ± 0.34 |
| lanjian | input-pting | 1.1 ± 0.3 | 0.7 | 1.8 | 1.16 ± 0.37 |
| mattcl-py | input-lanjian | 15.9 ± 0.7 | 14.8 | 19.6 | 16.33 ± 3.68 |
| mattcl-py | input-pting | 16.0 ± 0.8 | 14.7 | 19.2 | 16.46 ± 3.73 |
| mattcl-py | input-mattcl | 16.0 ± 0.7 | 14.8 | 18.7 | 16.46 ± 3.71 |
| mattcl-py | input-kcen | 16.1 ± 2.8 | 14.5 | 52.7 | 16.55 ± 4.66 |
| pting | input-kcen | 17.1 ± 0.7 | 15.9 | 20.5 | 17.56 ± 3.95 |
| pting | input-lanjian | 17.1 ± 0.6 | 15.9 | 20.0 | 17.57 ± 3.94 |
| pting | input-pting | 17.3 ± 0.7 | 16.1 | 20.6 | 17.81 ± 4.02 |
| pting | input-mattcl | 17.4 ± 0.7 | 16.4 | 20.5 | 17.86 ± 4.02 |
| kcen | input-lanjian | 20.2 ± 0.7 | 18.7 | 23.5 | 20.77 ± 4.66 |
| kcen | input-kcen | 20.3 ± 0.7 | 18.8 | 23.1 | 20.89 ± 4.68 |
| kcen | input-pting | 20.5 ± 0.8 | 19.4 | 23.4 | 21.10 ± 4.73 |
| kcen | input-mattcl | 20.7 ± 0.7 | 19.4 | 23.4 | 21.31 ± 4.77 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|