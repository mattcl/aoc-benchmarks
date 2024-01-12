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
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.6 | 1.00 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.6 | 1.5 | 1.02 ± 0.32 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.5 | 1.02 ± 0.32 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.05 ± 0.33 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.6 | 1.11 ± 0.35 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.7 | 1.13 ± 0.35 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.8 | 1.14 ± 0.35 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.8 | 1.15 ± 0.36 |
| mattcl-py | input-pting | 15.8 ± 0.6 | 14.7 | 19.3 | 16.19 ± 3.70 |
| mattcl-py | input-kcen | 15.8 ± 0.6 | 14.7 | 18.0 | 16.23 ± 3.71 |
| mattcl-py | input-lanjian | 15.8 ± 0.6 | 14.9 | 18.6 | 16.25 ± 3.71 |
| mattcl-py | input-mattcl | 16.0 ± 0.7 | 14.9 | 19.5 | 16.41 ± 3.77 |
| pting | input-kcen | 17.0 ± 0.7 | 15.7 | 20.4 | 17.47 ± 4.00 |
| pting | input-pting | 17.2 ± 0.8 | 16.2 | 20.4 | 17.67 ± 4.07 |
| pting | input-lanjian | 17.3 ± 2.3 | 15.7 | 45.9 | 17.71 ± 4.64 |
| pting | input-mattcl | 17.3 ± 0.7 | 16.3 | 20.4 | 17.76 ± 4.08 |
| kcen | input-lanjian | 20.2 ± 0.7 | 19.1 | 23.0 | 20.73 ± 4.73 |
| kcen | input-kcen | 20.4 ± 1.6 | 19.2 | 37.8 | 20.94 ± 5.02 |
| kcen | input-pting | 20.5 ± 0.8 | 19.1 | 24.2 | 20.98 ± 4.80 |
| kcen | input-mattcl | 20.6 ± 0.6 | 19.6 | 22.7 | 21.13 ± 4.81 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|