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
| mattcl | input-pting | 1.0 ± 0.2 | 0.6 | 1.6 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.6 | 1.01 ± 0.32 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.6 | 1.01 ± 0.32 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.6 | 1.6 | 1.04 ± 0.33 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.7 | 1.10 ± 0.34 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.7 | 1.13 ± 0.35 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.6 | 1.14 ± 0.35 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.15 ± 0.35 |
| mattcl-py | input-lanjian | 15.9 ± 0.7 | 14.7 | 19.2 | 16.68 ± 3.69 |
| mattcl-py | input-pting | 15.9 ± 0.6 | 15.1 | 19.0 | 16.73 ± 3.69 |
| mattcl-py | input-mattcl | 15.9 ± 0.7 | 14.9 | 19.8 | 16.74 ± 3.70 |
| mattcl-py | input-kcen | 16.4 ± 4.8 | 14.7 | 66.4 | 17.21 ± 6.27 |
| pting | input-lanjian | 17.0 ± 0.7 | 15.6 | 20.1 | 17.86 ± 3.94 |
| pting | input-pting | 17.2 ± 0.7 | 16.0 | 20.2 | 18.03 ± 3.97 |
| pting | input-kcen | 17.2 ± 0.8 | 15.9 | 20.2 | 18.10 ± 4.03 |
| pting | input-mattcl | 17.3 ± 0.8 | 16.2 | 20.8 | 18.16 ± 4.03 |
| kcen | input-kcen | 20.2 ± 0.7 | 19.1 | 23.1 | 21.27 ± 4.67 |
| kcen | input-lanjian | 20.3 ± 0.8 | 19.4 | 23.1 | 21.30 ± 4.69 |
| kcen | input-pting | 20.5 ± 0.7 | 19.1 | 23.6 | 21.58 ± 4.75 |
| kcen | input-mattcl | 20.6 ± 0.6 | 19.7 | 23.6 | 21.62 ± 4.73 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|