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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.31 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.5 | 1.06 ± 0.34 |
| mattcl | input-pting | 1.0 ± 0.3 | 0.6 | 2.9 | 1.06 ± 0.36 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.18 ± 0.37 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.8 | 1.19 ± 0.37 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.7 | 1.19 ± 0.37 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.6 | 1.21 ± 0.38 |
| mattcl-py | input-lanjian | 15.6 ± 0.7 | 14.7 | 19.4 | 17.06 ± 3.81 |
| mattcl-py | input-mattcl | 15.7 ± 0.6 | 14.8 | 18.7 | 17.17 ± 3.82 |
| mattcl-py | input-kcen | 15.7 ± 0.8 | 14.7 | 19.0 | 17.19 ± 3.87 |
| mattcl-py | input-pting | 15.8 ± 0.7 | 14.6 | 18.7 | 17.23 ± 3.87 |
| pting | input-lanjian | 16.7 ± 0.6 | 15.6 | 19.8 | 18.27 ± 4.06 |
| pting | input-kcen | 16.8 ± 0.6 | 15.8 | 19.6 | 18.35 ± 4.09 |
| pting | input-mattcl | 17.0 ± 0.8 | 15.8 | 19.9 | 18.65 ± 4.19 |
| pting | input-pting | 17.3 ± 3.2 | 15.8 | 58.4 | 18.87 ± 5.45 |
| kcen | input-lanjian | 19.9 ± 0.5 | 19.1 | 22.6 | 21.81 ± 4.82 |
| kcen | input-kcen | 20.1 ± 0.7 | 18.8 | 22.7 | 21.99 ± 4.89 |
| kcen | input-pting | 20.2 ± 0.6 | 19.3 | 22.8 | 22.05 ± 4.88 |
| kcen | input-mattcl | 20.4 ± 0.7 | 19.1 | 23.0 | 22.32 ± 4.96 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|