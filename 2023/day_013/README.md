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
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.6 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.6 | 1.01 ± 0.31 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.32 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.31 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.6 | 1.11 ± 0.34 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.7 | 1.13 ± 0.34 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.13 ± 0.35 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.6 | 1.15 ± 0.34 |
| mattcl-py | input-kcen | 15.4 ± 0.7 | 14.4 | 18.2 | 16.61 ± 3.61 |
| mattcl-py | input-lanjian | 15.5 ± 0.6 | 14.4 | 18.2 | 16.67 ± 3.61 |
| mattcl-py | input-mattcl | 15.6 ± 0.6 | 14.5 | 18.6 | 16.78 ± 3.64 |
| mattcl-py | input-pting | 15.6 ± 0.7 | 14.9 | 18.9 | 16.83 ± 3.67 |
| pting | input-lanjian | 16.7 ± 0.6 | 15.9 | 19.6 | 17.98 ± 3.89 |
| pting | input-kcen | 16.9 ± 1.7 | 15.8 | 37.2 | 18.22 ± 4.29 |
| pting | input-mattcl | 17.0 ± 0.8 | 16.1 | 20.3 | 18.35 ± 4.01 |
| pting | input-pting | 17.0 ± 0.8 | 16.2 | 20.5 | 18.37 ± 4.01 |
| kcen | input-lanjian | 19.9 ± 0.7 | 18.9 | 22.4 | 21.43 ± 4.62 |
| kcen | input-pting | 20.1 ± 0.7 | 19.1 | 23.0 | 21.67 ± 4.67 |
| kcen | input-mattcl | 20.3 ± 0.7 | 19.0 | 23.2 | 21.85 ± 4.72 |
| kcen | input-kcen | 20.4 ± 3.8 | 18.8 | 64.5 | 21.98 ± 6.21 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|