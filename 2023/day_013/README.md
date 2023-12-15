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
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.5 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.5 | 1.00 ± 0.32 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.31 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.7 | 1.5 | 1.02 ± 0.31 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.6 | 1.14 ± 0.35 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.7 | 1.15 ± 0.35 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.7 | 1.17 ± 0.36 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.7 | 1.7 | 1.20 ± 0.36 |
| mattcl-py | input-lanjian | 15.7 ± 0.8 | 14.5 | 19.2 | 16.17 ± 3.70 |
| mattcl-py | input-kcen | 15.7 ± 0.6 | 14.8 | 18.6 | 16.21 ± 3.68 |
| mattcl-py | input-pting | 15.8 ± 0.6 | 14.9 | 18.9 | 16.28 ± 3.70 |
| mattcl-py | input-mattcl | 15.8 ± 0.7 | 15.0 | 18.9 | 16.30 ± 3.72 |
| pting | input-lanjian | 16.7 ± 0.5 | 15.8 | 19.0 | 17.24 ± 3.90 |
| pting | input-kcen | 16.8 ± 0.6 | 15.7 | 20.1 | 17.32 ± 3.92 |
| pting | input-pting | 16.9 ± 0.7 | 15.8 | 19.9 | 17.50 ± 3.98 |
| pting | input-mattcl | 17.0 ± 0.6 | 16.2 | 19.3 | 17.60 ± 3.98 |
| kcen | input-lanjian | 20.1 ± 0.8 | 18.8 | 22.9 | 20.76 ± 4.72 |
| kcen | input-pting | 20.3 ± 0.7 | 19.2 | 22.7 | 20.95 ± 4.73 |
| kcen | input-kcen | 20.3 ± 2.4 | 19.0 | 48.2 | 20.97 ± 5.30 |
| kcen | input-mattcl | 20.4 ± 0.6 | 19.4 | 23.4 | 21.02 ± 4.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|