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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.31 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.6 | 1.01 ± 0.32 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.5 | 1.05 ± 0.33 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.16 ± 0.37 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.6 | 1.16 ± 0.36 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.7 | 1.16 ± 0.36 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.7 | 1.17 ± 0.36 |
| mattcl-py | input-kcen | 15.5 ± 0.6 | 14.6 | 18.4 | 17.10 ± 3.88 |
| mattcl-py | input-lanjian | 15.5 ± 0.6 | 14.5 | 18.4 | 17.11 ± 3.88 |
| mattcl-py | input-pting | 15.7 ± 0.7 | 14.7 | 18.6 | 17.32 ± 3.95 |
| mattcl-py | input-mattcl | 16.0 ± 3.3 | 15.0 | 54.1 | 17.63 ± 5.34 |
| pting | input-lanjian | 16.6 ± 0.5 | 15.7 | 19.1 | 18.31 ± 4.14 |
| pting | input-kcen | 16.8 ± 0.7 | 16.0 | 19.7 | 18.51 ± 4.21 |
| pting | input-pting | 16.9 ± 0.7 | 15.8 | 20.2 | 18.56 ± 4.22 |
| pting | input-mattcl | 17.0 ± 1.0 | 16.1 | 27.0 | 18.76 ± 4.33 |
| kcen | input-lanjian | 20.0 ± 0.7 | 19.0 | 23.2 | 22.03 ± 4.99 |
| kcen | input-kcen | 20.2 ± 0.8 | 18.9 | 22.8 | 22.20 ± 5.04 |
| kcen | input-pting | 20.2 ± 0.6 | 19.5 | 23.1 | 22.26 ± 5.03 |
| kcen | input-mattcl | 20.4 ± 1.4 | 19.3 | 34.6 | 22.48 ± 5.25 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|