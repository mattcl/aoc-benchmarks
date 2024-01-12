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
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.6 | 1.02 ± 0.31 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.5 | 1.03 ± 0.29 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.7 | 1.6 | 1.05 ± 0.30 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.8 | 1.8 | 1.13 ± 0.33 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.7 | 1.13 ± 0.33 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.7 | 1.14 ± 0.32 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.8 | 1.7 | 1.17 ± 0.34 |
| mattcl-py | input-kcen | 15.5 ± 0.6 | 14.5 | 18.7 | 15.55 ± 3.27 |
| mattcl-py | input-lanjian | 15.5 ± 0.6 | 14.4 | 18.8 | 15.56 ± 3.28 |
| mattcl-py | input-pting | 15.6 ± 0.5 | 14.4 | 18.3 | 15.65 ± 3.27 |
| mattcl-py | input-mattcl | 15.6 ± 0.7 | 14.6 | 18.7 | 15.69 ± 3.31 |
| pting | input-lanjian | 16.6 ± 0.6 | 15.6 | 19.7 | 16.69 ± 3.51 |
| pting | input-kcen | 16.7 ± 0.7 | 15.6 | 19.5 | 16.79 ± 3.54 |
| pting | input-mattcl | 16.8 ± 0.6 | 15.8 | 19.8 | 16.89 ± 3.55 |
| pting | input-pting | 16.8 ± 0.7 | 15.8 | 20.1 | 16.90 ± 3.56 |
| kcen | input-kcen | 19.9 ± 0.7 | 18.8 | 22.7 | 20.02 ± 4.21 |
| kcen | input-lanjian | 20.0 ± 0.7 | 19.2 | 23.1 | 20.06 ± 4.21 |
| kcen | input-mattcl | 20.1 ± 0.7 | 19.2 | 22.9 | 20.21 ± 4.24 |
| kcen | input-pting | 20.2 ± 0.8 | 19.0 | 23.5 | 20.25 ± 4.27 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|