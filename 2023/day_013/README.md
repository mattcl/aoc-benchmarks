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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.6 | 1.5 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.6 | 1.01 ± 0.30 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.6 | 1.02 ± 0.31 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.7 | 1.5 | 1.04 ± 0.31 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.8 | 1.7 | 1.12 ± 0.33 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.8 | 1.8 | 1.12 ± 0.33 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.7 | 1.16 ± 0.35 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.8 | 1.7 | 1.17 ± 0.35 |
| mattcl-py | input-kcen | 15.6 ± 0.5 | 14.8 | 19.4 | 15.71 ± 3.39 |
| mattcl-py | input-lanjian | 15.7 ± 0.6 | 14.7 | 18.5 | 15.80 ± 3.43 |
| mattcl-py | input-pting | 15.7 ± 0.5 | 14.8 | 18.4 | 15.82 ± 3.42 |
| mattcl-py | input-mattcl | 15.8 ± 0.7 | 15.0 | 19.0 | 15.94 ± 3.47 |
| pting | input-kcen | 16.8 ± 0.6 | 16.1 | 19.2 | 16.93 ± 3.66 |
| pting | input-lanjian | 16.8 ± 0.7 | 15.5 | 20.3 | 16.93 ± 3.67 |
| pting | input-pting | 16.9 ± 0.6 | 15.8 | 19.7 | 17.02 ± 3.68 |
| pting | input-mattcl | 17.0 ± 0.6 | 16.1 | 20.0 | 17.17 ± 3.72 |
| kcen | input-lanjian | 20.1 ± 0.8 | 19.2 | 23.5 | 20.27 ± 4.39 |
| kcen | input-kcen | 20.2 ± 0.7 | 19.1 | 23.0 | 20.32 ± 4.39 |
| kcen | input-pting | 20.2 ± 0.6 | 19.4 | 22.9 | 20.36 ± 4.39 |
| kcen | input-mattcl | 20.4 ± 0.8 | 19.3 | 23.9 | 20.58 ± 4.46 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|