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
| mattcl | input-kcen | 0.8 ± 0.2 | 0.5 | 1.5 | 1.00 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.5 | 1.4 | 1.00 ± 0.34 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.5 | 1.4 | 1.05 ± 0.36 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.5 | 1.5 | 1.06 ± 0.36 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.6 | 1.17 ± 0.39 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.6 | 1.6 | 1.19 ± 0.42 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.6 | 1.20 ± 0.41 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.6 | 1.6 | 1.21 ± 0.40 |
| mattcl-py | input-mattcl | 15.4 ± 0.5 | 14.6 | 18.1 | 18.83 ± 4.52 |
| mattcl-py | input-lanjian | 15.4 ± 0.7 | 14.4 | 18.7 | 18.86 ± 4.56 |
| mattcl-py | input-pting | 15.5 ± 0.7 | 14.5 | 18.4 | 18.96 ± 4.58 |
| mattcl-py | input-kcen | 15.6 ± 3.1 | 14.5 | 57.1 | 19.10 ± 5.93 |
| pting | input-lanjian | 16.6 ± 0.6 | 15.7 | 20.0 | 20.29 ± 4.88 |
| pting | input-pting | 16.9 ± 0.7 | 15.7 | 20.3 | 20.60 ± 4.97 |
| pting | input-mattcl | 16.9 ± 0.7 | 15.9 | 20.1 | 20.64 ± 4.97 |
| pting | input-kcen | 17.1 ± 2.8 | 15.5 | 52.1 | 20.86 ± 6.04 |
| kcen | input-kcen | 19.9 ± 0.7 | 18.8 | 23.2 | 24.29 ± 5.84 |
| kcen | input-lanjian | 19.9 ± 0.7 | 18.5 | 22.6 | 24.31 ± 5.85 |
| kcen | input-pting | 20.0 ± 0.9 | 18.9 | 23.2 | 24.47 ± 5.91 |
| kcen | input-mattcl | 20.1 ± 0.8 | 19.0 | 23.7 | 24.57 ± 5.92 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|