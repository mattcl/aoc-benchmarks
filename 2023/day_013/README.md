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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.6 | 1.6 | 1.00 ± 0.29 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.6 | 1.01 ± 0.30 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.7 | 1.6 | 1.02 ± 0.29 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.7 | 1.13 ± 0.33 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.7 | 1.13 ± 0.33 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.7 | 1.13 ± 0.34 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.8 | 1.17 ± 0.35 |
| mattcl-py | input-pting | 15.8 ± 0.5 | 14.9 | 18.1 | 16.12 ± 3.31 |
| mattcl-py | input-kcen | 15.9 ± 0.7 | 14.6 | 18.5 | 16.25 ± 3.37 |
| mattcl-py | input-mattcl | 16.0 ± 0.8 | 15.0 | 19.3 | 16.32 ± 3.40 |
| mattcl-py | input-lanjian | 16.0 ± 0.8 | 15.0 | 18.9 | 16.35 ± 3.40 |
| pting | input-lanjian | 17.1 ± 0.8 | 16.1 | 20.1 | 17.45 ± 3.62 |
| pting | input-kcen | 17.1 ± 0.7 | 15.9 | 20.3 | 17.46 ± 3.61 |
| pting | input-pting | 17.1 ± 0.7 | 16.0 | 20.2 | 17.52 ± 3.63 |
| pting | input-mattcl | 17.3 ± 0.6 | 16.3 | 19.7 | 17.67 ± 3.64 |
| kcen | input-lanjian | 20.2 ± 0.6 | 19.5 | 22.6 | 20.66 ± 4.23 |
| kcen | input-kcen | 20.3 ± 0.7 | 18.8 | 23.5 | 20.76 ± 4.27 |
| kcen | input-mattcl | 20.4 ± 0.6 | 19.2 | 23.2 | 20.87 ± 4.28 |
| kcen | input-pting | 20.7 ± 2.8 | 19.4 | 52.9 | 21.18 ± 5.13 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|