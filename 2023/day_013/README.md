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
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.33 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.5 | 1.02 ± 0.32 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.4 | 1.04 ± 0.33 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.6 | 1.18 ± 0.38 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.7 | 1.19 ± 0.37 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.7 | 1.19 ± 0.38 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.21 ± 0.38 |
| mattcl-py | input-lanjian | 15.5 ± 0.6 | 14.6 | 18.6 | 17.28 ± 4.02 |
| mattcl-py | input-mattcl | 15.6 ± 0.5 | 14.7 | 18.6 | 17.35 ± 4.02 |
| mattcl-py | input-kcen | 15.6 ± 0.6 | 14.6 | 18.4 | 17.37 ± 4.04 |
| mattcl-py | input-pting | 15.7 ± 0.6 | 14.7 | 18.8 | 17.48 ± 4.07 |
| pting | input-kcen | 16.7 ± 0.6 | 15.7 | 19.3 | 18.58 ± 4.32 |
| pting | input-lanjian | 16.8 ± 0.7 | 16.0 | 20.3 | 18.66 ± 4.35 |
| pting | input-mattcl | 16.8 ± 0.7 | 15.9 | 19.8 | 18.75 ± 4.36 |
| pting | input-pting | 17.0 ± 2.3 | 16.0 | 45.9 | 18.89 ± 5.01 |
| kcen | input-lanjian | 20.0 ± 0.7 | 18.7 | 23.8 | 22.21 ± 5.15 |
| kcen | input-kcen | 20.1 ± 1.0 | 19.3 | 31.1 | 22.31 ± 5.24 |
| kcen | input-pting | 20.2 ± 0.7 | 18.9 | 22.9 | 22.51 ± 5.22 |
| kcen | input-mattcl | 20.3 ± 0.6 | 19.4 | 23.0 | 22.55 ± 5.22 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|