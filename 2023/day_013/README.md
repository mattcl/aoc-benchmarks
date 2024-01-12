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
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.5 | 1.00 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.7 | 1.7 | 1.02 ± 0.30 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.6 | 1.03 ± 0.30 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.7 | 1.6 | 1.07 ± 0.31 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.7 | 1.15 ± 0.34 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.8 | 1.7 | 1.15 ± 0.35 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.8 | 1.15 ± 0.33 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.8 | 1.7 | 1.17 ± 0.35 |
| mattcl-py | input-kcen | 15.6 ± 0.6 | 14.4 | 18.4 | 15.77 ± 3.32 |
| mattcl-py | input-lanjian | 15.6 ± 0.6 | 14.6 | 18.5 | 15.81 ± 3.34 |
| mattcl-py | input-pting | 15.7 ± 0.7 | 14.9 | 20.0 | 15.94 ± 3.38 |
| mattcl-py | input-mattcl | 15.8 ± 0.7 | 14.7 | 19.3 | 16.00 ± 3.40 |
| pting | input-lanjian | 16.8 ± 0.8 | 15.5 | 20.4 | 16.97 ± 3.61 |
| pting | input-kcen | 16.8 ± 0.6 | 16.1 | 19.6 | 17.01 ± 3.58 |
| pting | input-pting | 16.9 ± 0.7 | 15.7 | 19.8 | 17.14 ± 3.62 |
| pting | input-mattcl | 17.1 ± 0.8 | 16.2 | 20.3 | 17.28 ± 3.67 |
| kcen | input-lanjian | 19.9 ± 0.5 | 18.9 | 22.5 | 20.13 ± 4.21 |
| kcen | input-mattcl | 20.3 ± 0.8 | 19.2 | 23.3 | 20.52 ± 4.33 |
| kcen | input-pting | 20.3 ± 0.8 | 19.0 | 23.3 | 20.55 ± 4.35 |
| kcen | input-kcen | 20.3 ± 3.5 | 18.8 | 61.4 | 20.61 ± 5.55 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|