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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.4 | 1.00 ± 0.33 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.33 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.32 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.10 ± 0.35 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.6 | 1.11 ± 0.36 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.6 | 1.6 | 1.12 ± 0.36 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.7 | 1.13 ± 0.36 |
| mattcl-py | input-lanjian | 15.7 ± 0.6 | 14.7 | 18.2 | 17.17 ± 4.03 |
| mattcl-py | input-kcen | 15.8 ± 0.7 | 14.7 | 18.7 | 17.28 ± 4.07 |
| mattcl-py | input-pting | 15.9 ± 0.6 | 14.8 | 19.0 | 17.30 ± 4.07 |
| mattcl-py | input-mattcl | 16.0 ± 2.3 | 14.6 | 45.5 | 17.51 ± 4.76 |
| pting | input-lanjian | 16.9 ± 0.6 | 16.0 | 19.9 | 18.46 ± 4.32 |
| pting | input-pting | 17.0 ± 0.7 | 16.0 | 20.0 | 18.53 ± 4.36 |
| pting | input-kcen | 17.0 ± 0.7 | 15.9 | 20.1 | 18.54 ± 4.36 |
| pting | input-mattcl | 17.4 ± 2.3 | 15.7 | 41.2 | 18.95 ± 5.04 |
| kcen | input-lanjian | 20.1 ± 0.6 | 18.9 | 23.8 | 21.96 ± 5.13 |
| kcen | input-kcen | 20.1 ± 0.6 | 18.9 | 23.1 | 21.97 ± 5.14 |
| kcen | input-pting | 20.4 ± 0.8 | 19.0 | 23.5 | 22.20 ± 5.21 |
| kcen | input-mattcl | 20.6 ± 0.8 | 18.9 | 23.9 | 22.43 ± 5.27 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|