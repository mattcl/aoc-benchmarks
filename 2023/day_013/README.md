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
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.5 | 1.00 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.00 ± 0.30 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.6 | 1.01 ± 0.31 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.7 | 1.6 | 1.03 ± 0.33 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.8 | 1.12 ± 0.36 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.7 | 1.13 ± 0.35 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.14 ± 0.36 |
| lanjian | input-lanjian | 1.1 ± 0.3 | 0.7 | 2.6 | 1.17 ± 0.38 |
| mattcl-py | input-kcen | 15.9 ± 0.7 | 14.8 | 19.3 | 16.30 ± 3.72 |
| mattcl-py | input-lanjian | 15.9 ± 0.7 | 14.7 | 19.6 | 16.30 ± 3.73 |
| mattcl-py | input-mattcl | 16.0 ± 0.8 | 14.8 | 19.4 | 16.38 ± 3.76 |
| mattcl-py | input-pting | 16.3 ± 2.6 | 14.8 | 45.1 | 16.70 ± 4.62 |
| pting | input-lanjian | 17.0 ± 0.7 | 16.1 | 20.3 | 17.42 ± 3.98 |
| pting | input-kcen | 17.2 ± 0.8 | 16.3 | 20.4 | 17.57 ± 4.02 |
| pting | input-mattcl | 17.2 ± 0.6 | 16.4 | 20.7 | 17.62 ± 4.00 |
| pting | input-pting | 17.5 ± 2.6 | 16.2 | 43.6 | 17.94 ± 4.81 |
| kcen | input-lanjian | 20.2 ± 0.6 | 19.3 | 23.7 | 20.65 ± 4.67 |
| kcen | input-kcen | 20.4 ± 0.7 | 19.0 | 23.2 | 20.84 ± 4.73 |
| kcen | input-pting | 20.5 ± 0.8 | 19.0 | 24.2 | 21.00 ± 4.78 |
| kcen | input-mattcl | 21.0 ± 3.3 | 19.4 | 58.8 | 21.52 ± 5.88 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|