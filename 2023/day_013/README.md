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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.7 | 1.00 ± 0.33 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.5 | 1.03 ± 0.35 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.5 | 1.04 ± 0.34 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.6 | 1.14 ± 0.37 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.15 ± 0.37 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.6 | 1.16 ± 0.37 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.7 | 1.18 ± 0.38 |
| mattcl-py | input-lanjian | 15.5 ± 0.6 | 14.8 | 18.3 | 17.52 ± 4.18 |
| mattcl-py | input-kcen | 15.6 ± 0.8 | 14.5 | 19.4 | 17.62 ± 4.23 |
| mattcl-py | input-pting | 15.6 ± 0.6 | 14.7 | 18.9 | 17.63 ± 4.21 |
| mattcl-py | input-mattcl | 15.7 ± 0.8 | 14.7 | 19.5 | 17.67 ± 4.25 |
| pting | input-lanjian | 16.6 ± 0.5 | 15.5 | 19.6 | 18.73 ± 4.45 |
| pting | input-kcen | 16.7 ± 0.7 | 15.6 | 19.7 | 18.87 ± 4.50 |
| pting | input-pting | 16.9 ± 0.6 | 16.0 | 20.4 | 19.04 ± 4.54 |
| pting | input-mattcl | 17.0 ± 0.7 | 15.8 | 20.3 | 19.11 ± 4.56 |
| kcen | input-lanjian | 20.0 ± 0.6 | 18.9 | 22.4 | 22.49 ± 5.33 |
| kcen | input-pting | 20.1 ± 0.7 | 19.1 | 23.7 | 22.68 ± 5.40 |
| kcen | input-mattcl | 20.2 ± 0.6 | 19.2 | 22.8 | 22.76 ± 5.40 |
| kcen | input-kcen | 20.8 ± 5.3 | 18.8 | 68.0 | 23.41 ± 8.15 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|