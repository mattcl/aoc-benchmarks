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
| mattcl | input-pting | 0.8 ± 0.2 | 0.5 | 1.4 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.5 | 1.4 | 1.05 ± 0.33 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.5 | 1.05 ± 0.34 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.4 | 1.07 ± 0.34 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.6 | 1.19 ± 0.38 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.6 | 1.23 ± 0.39 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.6 | 1.24 ± 0.39 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.6 | 1.26 ± 0.40 |
| mattcl-py | input-lanjian | 15.6 ± 0.6 | 14.6 | 18.3 | 18.62 ± 4.11 |
| mattcl-py | input-mattcl | 15.6 ± 0.7 | 14.8 | 18.5 | 18.73 ± 4.15 |
| mattcl-py | input-pting | 15.7 ± 0.8 | 14.5 | 19.1 | 18.75 ± 4.17 |
| mattcl-py | input-kcen | 15.7 ± 2.5 | 14.8 | 48.4 | 18.81 ± 5.06 |
| pting | input-lanjian | 16.7 ± 0.7 | 15.6 | 19.8 | 19.93 ± 4.40 |
| pting | input-mattcl | 16.8 ± 0.6 | 15.9 | 19.8 | 20.14 ± 4.43 |
| pting | input-pting | 16.8 ± 0.6 | 15.8 | 20.3 | 20.14 ± 4.44 |
| pting | input-kcen | 16.9 ± 2.3 | 15.7 | 46.0 | 20.20 ± 5.18 |
| kcen | input-lanjian | 20.0 ± 0.7 | 18.9 | 22.9 | 23.99 ± 5.28 |
| kcen | input-pting | 20.1 ± 0.6 | 19.0 | 22.5 | 24.02 ± 5.26 |
| kcen | input-kcen | 20.1 ± 0.8 | 18.9 | 22.9 | 24.05 ± 5.30 |
| kcen | input-mattcl | 20.2 ± 0.8 | 19.4 | 23.9 | 24.23 ± 5.34 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|