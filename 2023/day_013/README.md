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
| mattcl | input-kcen | 0.8 ± 0.2 | 0.6 | 1.4 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.5 | 1.5 | 1.02 ± 0.34 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.4 | 1.04 ± 0.33 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.4 | 1.06 ± 0.36 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.6 | 1.21 ± 0.39 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.7 | 1.22 ± 0.40 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.7 | 1.23 ± 0.40 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.6 | 1.23 ± 0.39 |
| mattcl-py | input-kcen | 15.7 ± 0.5 | 14.6 | 17.9 | 18.58 ± 4.40 |
| mattcl-py | input-lanjian | 15.8 ± 0.6 | 14.7 | 18.8 | 18.69 ± 4.45 |
| mattcl-py | input-mattcl | 15.9 ± 0.5 | 14.8 | 18.9 | 18.73 ± 4.44 |
| mattcl-py | input-pting | 16.0 ± 0.7 | 14.6 | 18.7 | 18.86 ± 4.49 |
| pting | input-lanjian | 16.8 ± 0.6 | 15.8 | 19.9 | 19.89 ± 4.72 |
| pting | input-kcen | 17.1 ± 0.8 | 15.7 | 20.5 | 20.19 ± 4.84 |
| pting | input-pting | 17.2 ± 0.7 | 16.1 | 20.4 | 20.31 ± 4.84 |
| pting | input-mattcl | 17.2 ± 0.8 | 15.7 | 20.5 | 20.34 ± 4.86 |
| kcen | input-lanjian | 20.3 ± 0.8 | 18.8 | 23.5 | 23.92 ± 5.69 |
| kcen | input-kcen | 20.3 ± 0.7 | 19.4 | 22.8 | 24.01 ± 5.69 |
| kcen | input-pting | 20.5 ± 0.7 | 19.0 | 23.2 | 24.20 ± 5.74 |
| kcen | input-mattcl | 20.7 ± 0.8 | 19.2 | 24.0 | 24.40 ± 5.81 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|