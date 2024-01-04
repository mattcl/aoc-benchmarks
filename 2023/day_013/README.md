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
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.5 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.6 | 1.03 ± 0.31 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.03 ± 0.33 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.7 | 1.6 | 1.04 ± 0.32 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.7 | 1.12 ± 0.34 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.7 | 1.12 ± 0.34 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.7 | 1.16 ± 0.35 |
| lanjian | input-pting | 1.4 ± 3.9 | 0.8 | 56.0 | 1.39 ± 3.96 |
| mattcl-py | input-kcen | 15.8 ± 0.6 | 14.5 | 18.9 | 16.02 ± 3.55 |
| mattcl-py | input-lanjian | 15.9 ± 0.7 | 14.9 | 18.7 | 16.11 ± 3.59 |
| mattcl-py | input-pting | 16.0 ± 0.8 | 14.8 | 19.5 | 16.25 ± 3.64 |
| mattcl-py | input-mattcl | 16.4 ± 3.8 | 14.6 | 56.8 | 16.65 ± 5.28 |
| pting | input-lanjian | 17.0 ± 0.7 | 16.2 | 19.5 | 17.25 ± 3.83 |
| pting | input-pting | 17.3 ± 0.7 | 16.2 | 20.8 | 17.55 ± 3.91 |
| pting | input-mattcl | 17.4 ± 0.8 | 16.2 | 20.9 | 17.64 ± 3.94 |
| pting | input-kcen | 17.4 ± 2.1 | 16.2 | 43.3 | 17.67 ± 4.42 |
| kcen | input-lanjian | 20.3 ± 0.7 | 19.1 | 23.7 | 20.58 ± 4.55 |
| kcen | input-kcen | 20.4 ± 0.7 | 19.1 | 22.9 | 20.65 ± 4.57 |
| kcen | input-pting | 20.5 ± 0.7 | 19.5 | 23.0 | 20.78 ± 4.59 |
| kcen | input-mattcl | 20.7 ± 0.7 | 19.7 | 24.2 | 20.95 ± 4.64 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|