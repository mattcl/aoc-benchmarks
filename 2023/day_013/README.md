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
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.5 | 1.3 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.5 | 1.4 | 1.05 ± 0.37 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.5 | 1.4 | 1.07 ± 0.38 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.5 | 1.08 ± 0.37 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.6 | 1.16 ± 0.40 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.6 | 1.17 ± 0.40 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.6 | 1.5 | 1.18 ± 0.39 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.6 | 1.6 | 1.20 ± 0.41 |
| mattcl-py | input-lanjian | 15.3 ± 0.5 | 14.4 | 17.8 | 18.86 ± 4.56 |
| mattcl-py | input-mattcl | 15.4 ± 0.5 | 14.6 | 18.3 | 18.96 ± 4.59 |
| mattcl-py | input-kcen | 15.4 ± 0.7 | 14.7 | 18.7 | 19.00 ± 4.63 |
| mattcl-py | input-pting | 15.5 ± 0.6 | 14.4 | 18.4 | 19.06 ± 4.63 |
| pting | input-kcen | 16.5 ± 0.6 | 15.6 | 19.0 | 20.32 ± 4.93 |
| pting | input-lanjian | 16.6 ± 0.7 | 15.8 | 19.5 | 20.46 ± 4.99 |
| pting | input-mattcl | 16.7 ± 0.7 | 15.8 | 19.8 | 20.59 ± 5.01 |
| pting | input-pting | 16.7 ± 0.8 | 15.8 | 20.6 | 20.63 ± 5.04 |
| kcen | input-kcen | 19.9 ± 0.7 | 18.9 | 23.2 | 24.49 ± 5.94 |
| kcen | input-lanjian | 19.9 ± 0.7 | 19.0 | 22.7 | 24.52 ± 5.95 |
| kcen | input-pting | 20.1 ± 0.7 | 18.8 | 23.3 | 24.74 ± 6.01 |
| kcen | input-mattcl | 20.1 ± 0.7 | 18.8 | 23.4 | 24.81 ± 6.02 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|