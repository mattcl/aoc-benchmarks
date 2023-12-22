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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.7 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.33 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.5 | 1.05 ± 0.34 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.4 | 1.05 ± 0.33 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.7 | 1.12 ± 0.37 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.7 | 1.13 ± 0.36 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.7 | 1.13 ± 0.37 |
| lanjian | input-mattcl | 1.4 ± 5.0 | 0.7 | 71.9 | 1.52 ± 5.46 |
| mattcl-py | input-kcen | 15.8 ± 0.7 | 14.5 | 18.9 | 17.21 ± 3.96 |
| mattcl-py | input-lanjian | 15.9 ± 0.7 | 14.8 | 19.3 | 17.24 ± 3.98 |
| mattcl-py | input-pting | 15.9 ± 0.6 | 14.7 | 18.3 | 17.27 ± 3.96 |
| mattcl-py | input-mattcl | 15.9 ± 0.7 | 14.9 | 19.2 | 17.31 ± 3.99 |
| pting | input-lanjian | 17.0 ± 0.6 | 15.8 | 20.4 | 18.48 ± 4.24 |
| pting | input-kcen | 17.1 ± 0.7 | 16.1 | 20.5 | 18.56 ± 4.27 |
| pting | input-pting | 17.2 ± 0.6 | 16.2 | 20.4 | 18.64 ± 4.28 |
| pting | input-mattcl | 17.2 ± 0.7 | 16.3 | 20.3 | 18.68 ± 4.29 |
| kcen | input-lanjian | 20.2 ± 0.6 | 19.3 | 22.4 | 21.96 ± 5.02 |
| kcen | input-pting | 20.3 ± 0.6 | 19.1 | 23.6 | 22.08 ± 5.04 |
| kcen | input-kcen | 20.4 ± 0.8 | 19.4 | 23.8 | 22.17 ± 5.10 |
| kcen | input-mattcl | 20.7 ± 0.7 | 19.6 | 23.3 | 22.46 ± 5.15 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|