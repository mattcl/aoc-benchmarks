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
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.7 | 1.01 ± 0.26 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.4 | 1.8 | 1.02 ± 0.27 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.9 | 1.08 ± 0.27 |
| mattcl-py | input-lanjian | 15.9 ± 0.6 | 14.7 | 18.4 | 14.23 ± 2.98 |
| mattcl-py | input-kcen | 16.0 ± 0.8 | 14.6 | 19.3 | 14.28 ± 3.02 |
| mattcl-py | input-mattcl | 16.0 ± 0.6 | 14.9 | 18.8 | 14.32 ± 2.99 |
| mattcl-py | input-pting | 16.0 ± 0.8 | 14.9 | 19.3 | 14.35 ± 3.04 |
| pting | input-kcen | 17.0 ± 0.6 | 15.7 | 20.0 | 15.23 ± 3.18 |
| pting | input-lanjian | 17.0 ± 0.7 | 15.7 | 20.4 | 15.24 ± 3.19 |
| pting | input-pting | 17.3 ± 0.7 | 16.3 | 20.2 | 15.43 ± 3.23 |
| pting | input-mattcl | 17.9 ± 5.0 | 16.2 | 62.6 | 16.04 ± 5.53 |
| kcen | input-lanjian | 20.3 ± 0.8 | 18.8 | 23.5 | 18.14 ± 3.79 |
| kcen | input-kcen | 20.3 ± 0.7 | 19.3 | 23.6 | 18.19 ± 3.80 |
| kcen | input-pting | 20.5 ± 0.8 | 19.3 | 23.6 | 18.37 ± 3.84 |
| kcen | input-mattcl | 20.8 ± 0.9 | 19.4 | 24.2 | 18.63 ± 3.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|