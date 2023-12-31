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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.6 | 1.6 | 1.02 ± 0.32 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.6 | 1.02 ± 0.32 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.6 | 1.03 ± 0.31 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.6 | 1.12 ± 0.36 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.13 ± 0.35 |
| lanjian | input-mattcl | 1.1 ± 0.3 | 0.7 | 1.7 | 1.14 ± 0.38 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.7 | 1.17 ± 0.36 |
| mattcl-py | input-lanjian | 15.8 ± 0.5 | 14.9 | 18.0 | 16.72 ± 3.77 |
| mattcl-py | input-mattcl | 16.0 ± 0.7 | 14.8 | 18.8 | 16.87 ± 3.83 |
| mattcl-py | input-pting | 16.0 ± 0.8 | 14.8 | 19.5 | 16.94 ± 3.87 |
| mattcl-py | input-kcen | 16.3 ± 3.9 | 14.7 | 57.2 | 17.24 ± 5.67 |
| pting | input-lanjian | 17.1 ± 0.7 | 16.2 | 19.8 | 18.09 ± 4.09 |
| pting | input-pting | 17.2 ± 0.6 | 16.2 | 20.1 | 18.17 ± 4.11 |
| pting | input-kcen | 17.2 ± 1.7 | 15.8 | 37.6 | 18.18 ± 4.44 |
| pting | input-mattcl | 17.3 ± 0.6 | 16.3 | 20.1 | 18.26 ± 4.13 |
| kcen | input-kcen | 20.2 ± 0.7 | 18.9 | 23.8 | 21.37 ± 4.82 |
| kcen | input-lanjian | 20.4 ± 0.9 | 18.8 | 23.1 | 21.58 ± 4.91 |
| kcen | input-mattcl | 20.5 ± 0.7 | 19.2 | 23.6 | 21.65 ± 4.88 |
| kcen | input-pting | 20.5 ± 0.8 | 19.3 | 23.8 | 21.68 ± 4.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|