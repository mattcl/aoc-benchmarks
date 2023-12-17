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
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.6 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.5 | 1.01 ± 0.27 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.02 ± 0.30 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.7 | 1.7 | 1.03 ± 0.29 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.8 | 1.7 | 1.13 ± 0.32 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.8 | 1.8 | 1.15 ± 0.32 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.8 | 1.7 | 1.15 ± 0.32 |
| lanjian | input-mattcl | 1.2 ± 0.3 | 0.8 | 3.1 | 1.17 ± 0.35 |
| mattcl-py | input-kcen | 15.6 ± 0.6 | 14.4 | 18.5 | 15.62 ± 3.03 |
| mattcl-py | input-lanjian | 15.6 ± 0.7 | 14.6 | 19.2 | 15.64 ± 3.05 |
| mattcl-py | input-mattcl | 15.7 ± 0.7 | 14.6 | 18.5 | 15.72 ± 3.08 |
| mattcl-py | input-pting | 15.8 ± 0.7 | 14.7 | 19.2 | 15.83 ± 3.10 |
| pting | input-lanjian | 16.8 ± 0.8 | 16.0 | 20.5 | 16.87 ± 3.30 |
| pting | input-pting | 16.9 ± 0.7 | 15.8 | 20.5 | 16.93 ± 3.30 |
| pting | input-kcen | 16.9 ± 0.8 | 15.7 | 20.2 | 16.93 ± 3.32 |
| pting | input-mattcl | 17.0 ± 0.5 | 15.9 | 19.4 | 17.01 ± 3.28 |
| kcen | input-lanjian | 20.1 ± 0.6 | 19.0 | 23.3 | 20.10 ± 3.87 |
| kcen | input-pting | 20.1 ± 0.5 | 19.3 | 22.6 | 20.13 ± 3.87 |
| kcen | input-kcen | 20.2 ± 0.6 | 19.4 | 23.0 | 20.20 ± 3.89 |
| kcen | input-mattcl | 20.4 ± 0.7 | 19.2 | 22.8 | 20.46 ± 3.96 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|