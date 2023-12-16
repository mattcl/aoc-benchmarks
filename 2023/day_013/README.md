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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.33 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.32 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.5 | 1.02 ± 0.33 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.7 | 1.14 ± 0.37 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.7 | 1.15 ± 0.36 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.7 | 1.17 ± 0.37 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.6 | 1.7 | 1.18 ± 0.38 |
| mattcl-py | input-lanjian | 15.9 ± 0.6 | 14.7 | 18.9 | 17.58 ± 4.00 |
| mattcl-py | input-pting | 15.9 ± 0.6 | 14.8 | 19.3 | 17.67 ± 4.02 |
| mattcl-py | input-mattcl | 16.0 ± 0.6 | 14.9 | 19.0 | 17.69 ± 4.02 |
| mattcl-py | input-kcen | 16.0 ± 0.7 | 14.8 | 19.3 | 17.73 ± 4.05 |
| pting | input-lanjian | 17.2 ± 0.7 | 16.0 | 20.5 | 19.08 ± 4.35 |
| pting | input-mattcl | 17.4 ± 0.7 | 16.3 | 20.6 | 19.31 ± 4.39 |
| pting | input-kcen | 17.4 ± 0.8 | 16.1 | 20.8 | 19.31 ± 4.42 |
| pting | input-pting | 17.5 ± 0.7 | 16.5 | 21.0 | 19.36 ± 4.41 |
| kcen | input-kcen | 20.7 ± 0.7 | 19.6 | 24.1 | 22.91 ± 5.19 |
| kcen | input-lanjian | 20.7 ± 0.7 | 19.7 | 24.0 | 22.95 ± 5.19 |
| kcen | input-pting | 21.0 ± 0.6 | 19.6 | 23.5 | 23.26 ± 5.25 |
| kcen | input-mattcl | 21.1 ± 0.7 | 20.2 | 24.1 | 23.36 ± 5.29 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|