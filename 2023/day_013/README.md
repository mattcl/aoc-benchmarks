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
| mattcl | input-pting | 1.0 ± 0.2 | 0.7 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.01 ± 0.28 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.6 | 1.01 ± 0.29 |
| mattcl | input-lanjian | 1.1 ± 2.4 | 0.7 | 35.0 | 1.11 ± 2.38 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.7 | 1.12 ± 0.32 |
| lanjian | input-lanjian | 1.2 ± 0.3 | 0.8 | 1.7 | 1.15 ± 0.34 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.8 | 1.8 | 1.15 ± 0.32 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.8 | 1.9 | 1.18 ± 0.32 |
| mattcl-py | input-kcen | 16.0 ± 0.7 | 14.9 | 18.8 | 15.63 ± 3.13 |
| mattcl-py | input-mattcl | 16.0 ± 0.7 | 14.7 | 18.7 | 15.64 ± 3.12 |
| mattcl-py | input-lanjian | 16.0 ± 0.6 | 15.0 | 18.8 | 15.65 ± 3.12 |
| mattcl-py | input-pting | 16.0 ± 0.7 | 15.0 | 19.0 | 15.70 ± 3.14 |
| pting | input-lanjian | 17.2 ± 0.8 | 16.1 | 20.5 | 16.83 ± 3.39 |
| pting | input-kcen | 17.2 ± 0.7 | 15.6 | 20.3 | 16.84 ± 3.36 |
| pting | input-pting | 17.3 ± 0.8 | 16.1 | 20.4 | 16.91 ± 3.39 |
| pting | input-mattcl | 17.4 ± 0.7 | 16.4 | 20.6 | 17.08 ± 3.41 |
| kcen | input-kcen | 20.3 ± 0.7 | 18.9 | 23.5 | 19.91 ± 3.96 |
| kcen | input-pting | 20.6 ± 0.7 | 19.1 | 23.2 | 20.17 ± 4.00 |
| kcen | input-mattcl | 20.7 ± 0.8 | 19.5 | 24.0 | 20.27 ± 4.03 |
| kcen | input-lanjian | 20.7 ± 4.4 | 19.4 | 72.5 | 20.29 ± 5.83 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|