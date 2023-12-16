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
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.6 | 1.00 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.5 | 1.01 ± 0.29 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.7 | 1.5 | 1.02 ± 0.29 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.7 | 1.7 | 1.03 ± 0.30 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.7 | 1.12 ± 0.31 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.8 | 1.7 | 1.14 ± 0.32 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.8 | 1.9 | 1.14 ± 0.33 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.8 | 1.6 | 1.15 ± 0.31 |
| mattcl-py | input-lanjian | 15.7 ± 0.7 | 14.7 | 18.9 | 15.57 ± 3.18 |
| mattcl-py | input-kcen | 15.7 ± 0.7 | 14.9 | 18.6 | 15.58 ± 3.18 |
| mattcl-py | input-pting | 15.7 ± 0.7 | 14.6 | 18.6 | 15.63 ± 3.19 |
| mattcl-py | input-mattcl | 15.8 ± 0.7 | 14.7 | 18.7 | 15.64 ± 3.20 |
| pting | input-lanjian | 16.7 ± 0.6 | 15.8 | 19.5 | 16.55 ± 3.35 |
| pting | input-kcen | 16.8 ± 0.6 | 16.0 | 19.1 | 16.67 ± 3.37 |
| pting | input-pting | 16.9 ± 0.6 | 16.1 | 19.9 | 16.76 ± 3.39 |
| pting | input-mattcl | 16.9 ± 0.7 | 15.8 | 20.4 | 16.79 ± 3.41 |
| kcen | input-lanjian | 20.0 ± 0.5 | 18.9 | 22.3 | 19.82 ± 3.98 |
| kcen | input-kcen | 20.0 ± 0.5 | 19.0 | 23.2 | 19.84 ± 3.99 |
| kcen | input-pting | 20.4 ± 0.9 | 19.4 | 23.3 | 20.26 ± 4.13 |
| kcen | input-mattcl | 20.7 ± 4.4 | 19.2 | 59.9 | 20.58 ± 6.00 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|