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
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.6 | 1.00 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.6 | 1.01 ± 0.30 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.7 | 1.6 | 1.02 ± 0.29 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.03 ± 0.31 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.8 | 1.7 | 1.14 ± 0.32 |
| lanjian | input-lanjian | 1.1 ± 0.3 | 0.8 | 3.2 | 1.15 ± 0.36 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.7 | 1.16 ± 0.33 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.8 | 1.8 | 1.17 ± 0.34 |
| mattcl-py | input-kcen | 15.6 ± 0.5 | 14.7 | 18.5 | 15.76 ± 3.29 |
| mattcl-py | input-lanjian | 15.7 ± 0.6 | 14.8 | 18.8 | 15.82 ± 3.32 |
| mattcl-py | input-pting | 15.7 ± 0.6 | 14.7 | 18.9 | 15.89 ± 3.32 |
| mattcl-py | input-mattcl | 15.9 ± 2.6 | 14.5 | 49.9 | 16.08 ± 4.21 |
| pting | input-lanjian | 16.8 ± 0.7 | 16.0 | 20.5 | 16.99 ± 3.56 |
| pting | input-kcen | 16.8 ± 0.6 | 15.9 | 19.8 | 16.99 ± 3.56 |
| pting | input-pting | 16.9 ± 0.5 | 15.8 | 19.3 | 17.09 ± 3.56 |
| pting | input-mattcl | 17.1 ± 0.8 | 16.2 | 20.4 | 17.31 ± 3.65 |
| kcen | input-lanjian | 20.0 ± 0.6 | 18.9 | 23.1 | 20.23 ± 4.21 |
| kcen | input-kcen | 20.1 ± 0.7 | 19.0 | 23.2 | 20.27 ± 4.22 |
| kcen | input-pting | 20.2 ± 0.6 | 19.1 | 22.5 | 20.45 ± 4.24 |
| kcen | input-mattcl | 21.0 ± 4.6 | 19.1 | 60.8 | 21.17 ± 6.36 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|